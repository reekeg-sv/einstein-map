---
layout: default
title: Search Your Claude Code and Codex Conversation History
description: Find an old fix, command or decision in your Claude Code and Codex conversation history with two or three words. Local search, no API key, free for Mac and Windows.
permalink: /search-conversation-history/
---

You remember that you already fixed this error, but not in which chat. Einstein Free finds the right place by the content of both agents' conversations on your computer.

## Search with a few words

Ask your agent: *“Find in our past conversations how we fixed [error text].”* Or run it yourself:

```sh
einstein find "connection refused"
```

Each result shows the date, the agent and a fragment of the conversation. To open the conversation around a result, use `einstein context` with the result's id.

## What to search for

- The exact command that fixed a failure.
- The name of a file or library you discussed.
- The reason for a decision, or for rejecting another option.

## Tips

- Use two or three distinctive words. A single common word returns too much.
- Search covers Claude Code and Codex conversations together.
- The archive and the search stay on your computer, and no API key is needed.

<p class="cta">
  <a href="https://github.com/reekeg-sv/einstein-map/releases/tag/v0.19.34">Download Einstein Free</a>
  <a class="second" href="{{ '/shared-memory-codex-claude-code/' | relative_url }}">Next: shared memory for both agents</a>
</p>

<p class="all-guides"><a href="{{ '/#guides' | relative_url }}">← All guides</a></p>
