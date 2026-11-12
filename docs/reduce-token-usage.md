---
layout: default
title: How to Reduce Claude Code and Codex Token Usage
description: Spend fewer tokens in Claude Code and Codex. Einstein answers questions that were already solved from memory, keeps chats short and keeps the thread after compaction.
permalink: /reduce-token-usage/
---

If the cause of an error was already found in a past chat, a new investigation means reading files, running checks and explaining everything again, and paying for it. Einstein helps Claude Code and Codex find the earlier result and use it in the current task.

![Einstein Map saves tokens: 1,000× cheaper answers to questions already solved, up to 5× fewer tokens per request, 100% of the conversation stays after compaction]({{ '/assets/token-savings.png' | relative_url }})

## How much it saves

Measured on our own Claude Code logs, August–October 2026:

| | Without Einstein | With Einstein |
|---|---|---|
| A question that was already solved | about 2.4M tokens to research it again | about 2K tokens from memory: **up to 1,000× cheaper** |
| Context per request | 332K tokens on average in long chats | 71K with a new chat for each task: **up to 5× fewer** |
| After context compaction | details are lost and the agent drifts | the whole conversation stays in Einstein |

Actual savings depend on the task and on the history you have accumulated.

## Three habits that save tokens

1. **Ask memory first.** *“Before checking again, find the earlier discussion of this error. What did we try and how did the check end?”* If the code has changed since then, re-check the old solution.
2. **Start a new chat for each task.** Einstein shows the agent where you left off, so a fresh chat does not mean starting from zero.
3. **Compact earlier.** Set auto-compaction at about 350K tokens on 1M-context models. Einstein reminds the agent what was in the chat, so it keeps the thread.

## Where memory helps most

- You come back to a project after a break.
- A similar error has happened before.
- The agent is about to re-test an option that was rejected earlier.
- Another agent continues the work and needs the history of decisions.

## What about cost?

You pay nothing for the memory itself. Einstein Free is free, needs no API key and spends no tokens on summarizing or compressing chats. Only a short record found by search goes into the agent's context.

<p class="cta">
  <a href="https://github.com/reekeg-sv/einstein-map/releases/tag/v0.19.33">Download Einstein Free</a>
  <a class="second" href="{{ '/search-conversation-history/' | relative_url }}">How to find a past command</a>
</p>

<p class="all-guides"><a href="{{ '/#guides' | relative_url }}">← All guides</a></p>
