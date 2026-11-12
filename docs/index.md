---
layout: default
title: Einstein Map — Persistent Memory for Codex and Claude Code
description: Persistent memory for OpenAI Codex and Anthropic Claude Code. Continue work across chats, search past conversations, keep the thread after context compaction and save tokens. Free for Mac and Windows.
permalink: /
---

<p align="center"><img src="{{ '/assets/einstein-map-icon.png' | relative_url }}" width="140" alt="Einstein Map icon"></p>

**Continue work across chats, find past decisions, and switch between OpenAI Codex and Anthropic Claude Code with one shared memory.** Less re-explaining, less re-searching and less repeated context means fewer tokens and less money spent.

Einstein Free is completely free: no account, no subscription, no separate API key and nothing extra to pay for tokens or compaction. It works on Mac and Windows, and your conversation history stays on your computer.

<p class="cta">
  <a href="https://github.com/reekeg-sv/einstein-map/releases/download/v0.19.33/einstein-free-0.19.33-hybrid-macos-arm64.tar.gz">Download Free for Mac</a>
  <a href="https://github.com/reekeg-sv/einstein-map/releases/download/v0.19.33/einstein-free-0.19.33-hybrid-windows-x86_64.zip">Download Free for Windows</a>
  <a class="second" href="https://einsteinmap.com/pro">Get Pro — free</a>
</p>

![Einstein Map saves tokens: 1,000× cheaper answers to questions already solved, up to 5× fewer tokens per request, 100% of the conversation stays after compaction]({{ '/assets/token-savings.png' | relative_url }})

## What Einstein does

- **Memory across sessions.** Come back to earlier decisions, commands and agreements when you start a new chat.
- **Shared memory for Codex and Claude Code.** Start a task in one agent and continue in the other on the same computer, without retelling.
- **Hints from past work.** Einstein remembers what was discussed and tells your AI agent where you left off, what was already checked and which options were rejected.
- **Search your conversation history.** Find an old fix, command or file with a few words, or just ask the agent: *“Find how we solved this before.”*
- **The thread survives compaction.** Einstein reminds the agent what was in the chat, so it does not lose the thread. We recommend compacting at about 350K tokens on 1M-context models.
- **Project maps in Pro.** Facts, plans, decisions and the state of work in one place, so a multi-step project does not fall apart.

## Guides

- [How to Continue a Claude Code Conversation in a New Session]({{ '/continue-claude-code-conversation/' | relative_url }})
- [How to Add Persistent Memory to OpenAI Codex]({{ '/codex-persistent-memory/' | relative_url }})
- [Search Your Claude Code and Codex Conversation History]({{ '/search-conversation-history/' | relative_url }})
- [How to Reduce Claude Code and Codex Token Usage]({{ '/reduce-token-usage/' | relative_url }})
- [Free Shared Memory for Codex and Claude Code]({{ '/shared-memory-codex-claude-code/' | relative_url }})

## Install in three steps

1. Download the package for your system and extract it. Keep the whole `einstein.dist` folder together.
2. Ask your AI agent: **“Read INSTALL-AI.md in this folder and install Einstein.”**
3. In Codex, open `/hooks` and approve the Einstein entries. Start a new chat.

Full instructions, checksums and the Pro setup are in the [README on GitHub](https://github.com/reekeg-sv/einstein-map). Help: [einsteinmap.com/help](https://einsteinmap.com/help).
