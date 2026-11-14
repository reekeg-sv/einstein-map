---
layout: default
title: How to Add Persistent Memory to OpenAI Codex
description: Persistent memory for OpenAI Codex. Search past Codex conversations, get hints from previous chats in a new session and share history with Claude Code. Free for Mac and Windows.
permalink: /codex-persistent-memory/
---

In a long project it matters to remember not only the next step but also why it was chosen. Einstein gives Codex access to your past conversations: the decisions, checks, commands and agreements that will be useful in a new session.

## What Einstein Free adds to Codex

- Search across your saved Codex history.
- Hints from previous chats in a new session.
- Access to Claude Code conversations on the same computer.
- A reminder of what was in the chat after context compaction, so Codex keeps the thread.

## How to connect Einstein to Codex

1. [Download Einstein Free](https://github.com/reekeg-sv/einstein-map/releases/tag/v0.19.34) for Mac or Windows and extract the archive.
2. Ask Codex: **“Read INSTALL-AI.md and install Einstein only for Codex.”** Leave out “only for Codex” if you also use Claude Code.
3. Open `/hooks`, review and approve the Einstein entries.
4. Start a new chat and ask about something you have already discussed.

## Check it on your project

Ask: *“What did we decide about [task name] and why? Find the earlier discussion.”* A hint appears when there is a matching record in your history.

## Maps for multi-step work

With Pro, the agent keeps facts, plans and the state of work in a project map. Ask it to write a decision into the map, and it will be easy to come back to. Pro is currently free: [einsteinmap.com/pro](https://einsteinmap.com/pro).

## Questions

**Do I need an OpenAI API key?**
No. Memory search runs on your computer and needs no separate key. Your Codex subscription and limits apply as usual.

**Does it work with Codex on Windows?**
Einstein Free has a package for Windows 10/11 (x86_64).

<p class="cta">
  <a href="https://github.com/reekeg-sv/einstein-map/releases/tag/v0.19.34">Download Einstein Free</a>
  <a class="second" href="https://einsteinmap.com/pro">Pro project maps</a>
</p>

<p class="all-guides"><a href="{{ '/#guides' | relative_url }}">← All guides</a></p>
