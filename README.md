<div align="center">

# WorkPilot

**One cockpit for all your AIs. Turn yourself into a team.**

Runs on the AI subscriptions you already pay for — **no API keys, no per-token billing.**

[![Download](https://img.shields.io/badge/Download-macOS%20(Apple%20Silicon)-black?logo=apple)](https://github.com/boice-kazuya/workpilot-releases/releases/latest)
[![Release](https://img.shields.io/github/v/release/boice-kazuya/workpilot-releases?label=latest)](https://github.com/boice-kazuya/workpilot-releases/releases/latest)
![Notarized](https://img.shields.io/badge/Apple-Notarized-blue)

[**⬇ Download**](https://github.com/boice-kazuya/workpilot-releases/releases/latest) · [Website](https://workpilot.space) · [日本語版 README](./README.ja.md)

</div>

<!-- [Phase 2] hero banner goes here: docs/img/hero.png (light/dark <picture>) -->

WorkPilot is a desktop AI workspace for Mac that takes your instructions all the way to **finished work** — videos, images, articles, code, and audio. Not another chat window that hands you drafts: a cockpit that ships.

## Six modes, one window

| | Mode | What comes out |
|---|---|---|
| 💬 | **Chat** | Thinking, research, decisions — with your own knowledge attached |
| 🖼 | **Image** | Visuals from your product photos and references |
| 🎬 | **Video** | Generate → edit on a timeline → export |
| 📝 | **Article** | SEO outline → draft → published to WordPress |
| 🎵 | **Audio** | Voice-over and music |
| 💻 | **Code** | Plan, build, fix, deploy — Claude-Code-grade |

<!-- [Phase 2] demo.gif goes here (one 20s loop: instruction → steps → finished output) -->

## Why WorkPilot

### 🧠 All your AI engines in one place — on the plans you already have

Switch between **Claude, ChatGPT, Kimi, and Gemini** per thread, or write one instruction like *"script with Claude, thumbnail with GPT, upload with Claude"* and WorkPilot splits it into steps and runs each on the right engine. It signs in through each vendor's own CLI login — **no API keys, no metering**. Your plan usage (5-hour and weekly windows) sits at the bottom of the screen at all times, and long research runs automatically drop to a cheaper model so you don't burn your quota on web browsing.

### 👥 An AI team, not a single assistant

Assemble a team from **17 role presets** (planner, researcher, writer, reviewer, marketer, designer, coder, video director, analyst, legal…) plus your own agents. A commander orchestrates the flow — or write your own numbered playbook (*"1: pick theme, 2: script (GPT), 3: review…"*) and the team follows it faithfully. Rename any role to match how your company talks, give it a photo, **coach it** with feedback it remembers, and **export an agent to a file** to hand to a teammate (secrets are scanned for before it leaves your Mac).

### 🫧 "mee" — your AI double

mee watches how *you* actually write and decide, turns that into a profile you can review line by line, and then **rides along in every conversation** — drafting in your voice, judging by your criteria. It can answer on your behalf while you're away, and keep working toward a goal on autopilot. Nothing is written to your profile without your approval.

### 🎒 Gear up once, never re-explain

Attach **Knowledge** (docs, specs, product photos), **Skills** (reusable procedures — say *"turn this flow into a skill"* and it's saved), **Connections**, and a **Persona** to any thread. Save combinations as **Gear Sets** and re-arm with one tap.

- **Knowledge** ingests PDFs, Word, Excel, PowerPoint, URLs, and photos (**OCR included**), then auto-optimizes them into **OKF** (the open knowledge format) — plain files, no lock-in.
- **Skills** can be imported from your existing **Claude Code / Codex** setup in one click. Each one tracks when it was last used, can be shelved instead of deleted, and has an **A/B "does this actually help?" test** built in.
- **Connections** live in one place: MCP servers, your own APIs, SSH servers, and email.
- 🛡 **House rules** you write once are enforced on every answer, with a decision log you can audit.

### 🔁 Loops — work that runs without you

Talk through a job once, then press **"make a loop from this thread"**: WorkPilot carries over what you agreed, asks only for what's genuinely missing, and schedules it.

- Runs on a schedule, in the background. If your Mac was asleep, it catches up on the missed run.
- Close the app mid-run? It **resumes from where it stopped** — no lost work.
- Each cycle produces a report and files you can open, and results can be **emailed to you**.
- It **learns from its own runs** and flags gaps a human would miss.

### 🚢 Ships, not drafts

Generate a video, cut it on a timeline with footage from your phone, and export. Write an SEO article and post it to WordPress. Build and fix code with plan-then-execute, parallel jobs, one-click rollback, and per-environment deploy permissions. Track it all with a **built-in task list** and `wp://` **place links** that drop you back exactly where you left off.

Anything that *publishes* — upload, post, deploy, send — asks for your approval first. Everything else just runs.

### 📱 Mobile cockpit

Away from your desk? Talk to your Mac from your phone in a **full-screen voice mode** built to be usable while driving: you speak, work happens, a summary comes back. Photos and clips you shoot go straight into your projects.

### 🗂 Plays well with Obsidian and Claude Code

Point WorkPilot at your **Obsidian vault** and your knowledge, notes, and agent profiles live as plain Markdown inside it — so **Claude Code reads the exact same files**. Everything WorkPilot writes stays under `<vault>/WorkPilot/`, and unlike an MCP bridge it works whether or not Obsidian is running.

### 🤝 Shared spaces for small teams

Share knowledge, threads, and code over a plain folder or NAS — **no server required**. Join with a single code. Leaders keep production deploys to themselves; staff get staging.

## How it's different

| | A normal AI chat | WorkPilot |
|---|---|---|
| **Cost** | API metering, or yet another subscription | **Your existing plans, as-is. No extra bill.** |
| **Output** | Suggestions and text | Video, images, articles, code, audio — **exported and published** |
| **Engines** | Locked to one vendor | Claude / ChatGPT / Kimi / Gemini, **picked per step** |
| **Memory** | Explain yourself every time | Knowledge, skills, rules and persona you **equip** |
| **Initiative** | Answers when asked | **Loops run on a schedule** and keep going |
| **Your data** | On someone else's servers | **On your Mac** (sharing uses your folder/NAS) |

## Download & install

**[⬇ Download the latest DMG](https://github.com/boice-kazuya/workpilot-releases/releases/latest)**

1. Open the DMG and drag **WorkPilot** into **Applications**
2. Double-click to launch — the app is **notarized by Apple**, so no security warnings
3. Connect one AI engine (Settings → Connections) and start working

First run gives you a guided tour, and a built-in **"How do I…?" Q&A thread** is one click away from the top bar. Updates arrive in-app: one button, done.

## Requirements

- macOS on **Apple Silicon** (arm64)
- At least one of the following, on your own account:
  - **Claude** subscription (Anthropic) or API key
  - **ChatGPT** subscription (OpenAI) or API key
  - **Kimi** subscription (Moonshot AI)
  - **Gemini** API key (free tier works)
- Optional: Higgsfield (video), ElevenLabs (voice), Suno (music), Obsidian, WordPress

Memory use is tuned for ordinary Macs, not just maxed-out ones.

## Privacy & trust

- **Your data stays on your Mac.** Conversations, knowledge, and outputs are stored locally; team sharing uses *your* folder or NAS, not our servers
- **Nothing publishes without you.** Uploads, posts, deploys, and sends always require explicit approval
- **No surprise bills.** No API metering — it runs on your existing flat-rate plans, with usage gauges always visible
- **Secrets are checked before anything leaves.** Exporting an agent or sharing code scans for API keys, personal paths, and contact details first
- **Notarized by Apple** with a Developer ID signature

## Built in the open, shipped daily

**111 public releases in the four weeks since this repo went up** (Aug 19 – Sep 15, 2026). Bugs reported in the morning are often fixed the same day, and every release ships with plain-language notes about what changed and why.

## Get notified when it ships

New builds land most days. Two ways to keep up without checking back:

- **[⭐ Star this repo](https://github.com/boice-kazuya/workpilot-releases)** — new releases surface in your GitHub home feed, and it's the clearest signal that this is worth continuing.
- **Watch → Custom → Releases** — GitHub emails you the moment a new build is published.

Found a bug or want a feature? [Open an issue](https://github.com/boice-kazuya/workpilot-releases/issues) — same-day fixes are normal. Questions and ideas belong in [Discussions](https://github.com/boice-kazuya/workpilot-releases/discussions).

## FAQ

<details>
<summary><b>Do I need an API key?</b></summary>

No. WorkPilot uses each vendor's official CLI login, so your existing Claude / ChatGPT / Kimi subscription works as-is. API keys are supported if you prefer them, but they're never required.
</details>

<details>
<summary><b>Will it run up a bill while I'm not looking?</b></summary>

No metered API calls. You're spending your flat-rate plan's quota, and the remaining quota for the current 5-hour and weekly window is displayed at the bottom of the screen. Long research runs automatically switch to a cheaper model.
</details>

<details>
<summary><b>Can it post or deploy without asking me?</b></summary>

No. Anything that publishes — uploading, posting, deploying, sending email — stops and asks first. Everything else runs unattended so you're not clicking "approve" all day.
</details>

<details>
<summary><b>Is my data sent anywhere?</b></summary>

Conversations, knowledge, and outputs are stored on your Mac. Team sharing writes to a folder or NAS that you own. Prompts go to the AI vendor you chose, and nowhere else.
</details>

<details>
<summary><b>Windows or Intel Mac?</b></summary>

Apple Silicon only for now. A Windows build is in progress.
</details>

<details>
<summary><b>Is the source code available?</b></summary>

Not currently. This repository distributes the app; the source is private. Bug reports and feature requests are very welcome in [Issues](https://github.com/boice-kazuya/workpilot-releases/issues).
</details>

## About this repository

This is the **distribution repository** (releases only — source code is not published here).
Website: **[workpilot.space](https://workpilot.space)** · Issues: **[report a bug or request a feature](https://github.com/boice-kazuya/workpilot-releases/issues)**

---
© BOICE INC.
