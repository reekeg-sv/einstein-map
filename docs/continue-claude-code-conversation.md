---
layout: default
title: How to Continue a Claude Code Conversation in a New Session
description: Give Claude Code memory across sessions and after context compaction. Einstein finds earlier decisions, commands and errors, so a new chat continues where you left off.
permalink: /continue-claude-code-conversation/
---

Yesterday you found the cause of a bug and chose a fix. Today you start a new chat and want to continue from that decision. Einstein helps Claude Code find the earlier conversation and bring the details you need back into the current work.

## What you can bring back

- The decision you stopped at and the reason you chose it.
- A command, a path or an error message from a past conversation.
- A test result and the option you already tried.

## Claude Code memory after context compaction

When a long chat is compacted, the conversation is replaced by a short summary, and an exact command or an important detail can drop out of it. Einstein keeps the thread: it reminds the agent what was in the chat, so Claude Code does not drift away from the task. The whole conversation also stays in your saved history and can be found by search.

Because nothing is lost, you can compact earlier. **We recommend an auto-compaction threshold of about 350K tokens** on models with a 1M-token context window. Every request in a long chat carries the whole context again, so a smaller context is cheaper and your limits last longer.

## Try it on your own task

1. [Download Einstein Free](https://github.com/reekeg-sv/einstein-map/releases/tag/v0.19.34) for Mac or Windows and extract the archive.
2. Ask Claude Code: **“Read INSTALL-AI.md and install Einstein.”**
3. Start a new chat and ask: *“Find where we stopped when fixing [error name]. Which options did we already try?”*

## Questions

**Do I need to do anything before compaction?**
No. Conversations are saved as they happen, and Einstein searches what has been saved.

**Can Einstein bring back a deleted chat?**
No. Einstein relies on saved conversations: it cannot restore history that was deleted before it was saved.

**Does it cost tokens?**
The memory itself is free. Einstein searches your chats directly on your computer, and only a short hint goes into the agent's context.

<p class="cta">
  <a href="https://github.com/reekeg-sv/einstein-map/releases/tag/v0.19.34">Download Einstein Free</a>
  <a class="second" href="{{ '/search-conversation-history/' | relative_url }}">Next: search your conversation history</a>
</p>

<p class="all-guides"><a href="{{ '/#guides' | relative_url }}">← All guides</a></p>
