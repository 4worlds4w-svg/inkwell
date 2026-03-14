![Inkwell Banner](banner.png)
<p align="center">
  <img src="https://img.shields.io/github/v/release/4worlds4w-svg/inkwell?label=version" />
  <img src="https://img.shields.io/github/downloads/4worlds4w-svg/inkwell/total" />
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey" />
  <img src="https://img.shields.io/badge/built%20with-Tauri%20v2-blue" />
  <img src="https://img.shields.io/badge/license-Free%20%2B%20Pro-green" />
</p>

# Inkwell

**Markdown editor that gets out of your way.**

Lightweight, beautiful, fast, and portable.

![Inkwell Screenshot](screenshot.png)

---

## Download

**[Download for Windows](https://github.com/4worlds4w-svg/inkwell/releases/tag/v1.1)** — `inkwell-v1.1-windows-x64.zip`

**[Download for macOS](https://github.com/4worlds4w-svg/inkwell/releases/tag/v1.1)** — `inkwell-v1.1-macos.dmg` *(built with actions - submit issues on this repo for now, if needed)*

**[Download for Linux](https://github.com/4worlds4w-svg/inkwell/releases/tag/v1.1)** — `inkwell-v1.1-linux-x64.tar.gz`

---

## Getting Started

**Windows:** Download and unzip. Run `inkwell.exe`. Start writing.

> Windows SmartScreen may warn you on first launch, this is expected for unsigned apps. Click **"More info"** → **"Run anyway"**.

**macOS:** Download and unzip. Open the `.dmg` and drag Inkwell to Applications.

> macOS Gatekeeper may block unsigned apps. If that happens, run:
> ```bash
> xattr -cr /Applications/Inkwell.app
> ```
> Then open normally.

**Linux:** Download and unzip, then:
```bash
chmod +x inkwell
./inkwell
```

---

## Features

**Editor** — Split view with a draggable divider. Live preview as you type. Current line highlight with accent-colored cursor.

**4 Themes** — Editorial (warm cream), Midnight (dark mode), Mono (black & white), Sepia (vintage warmth).

**3 Font Families** — Crimson Pro (serif), Inter (sans), IBM Plex Mono. Adjustable size from 14–24px.

**Focus Mode** — One click to hide everything except your words. Press Esc to return.

**Markdown** — Full GitHub Flavored Markdown. Syntax highlighting for 30+ languages. Copy buttons on code blocks. Styled tables, blockquotes, and checklists.

**Files** — Tabbed editing. Drag & drop. Auto-save on every keystroke. Recent files. Native save dialogs.

**Images** — Paste from clipboard or drag onto the editor. Large images auto-resized. Stored as data URLs, fully portable.

**Templates** — 10 built-in templates + save your own.

**Table of Contents** — Auto-generated from headings. Click to jump. Active section highlighted.

**Version History** — Auto-snapshots every 5 minutes. One-click restore. Diff viewer shows line-by-line changes.

**Find & Replace** — Ctrl+F with replace single or replace all. Match highlighting and navigation.

**Typewriter Mode** — Keeps the cursor line centered while typing. Toggle in toolbar.

---

## Pro License

Inkwell is **free to use forever**. Write, preview, switch themes, use templates, all of it.

**PDF and HTML exports** require a one-time Pro license.

**[Get a Pro license on Gumroad →](https://4worlds.gumroad.com/l/inkwell)**  (FREE for the first 100 people)

---

## Technical Details

| | |
|-|-|
| **Size** | ~11 MB (Windows) · ~8.5 MB (Linux/macOS) |
| **Built with** | Rust + Tauri v2 |
| **Startup** | ~ 1 second |
| **Tested with** | 10k+ words .md files |
| **Data storage** | Local. |

---

## What's Coming

| Version | Features |
|---------|----------|
| v1.2 | Workspace & File Tree, LaTeX math |
| v1.3 | Mermaid diagrams, Command palette |
| v1.4 | Custom themes, manual update check |

---

## Philosophy

Inkwell is the first release from **[4Worlds](https://4worlds.dev)**, a small independent software studio building tools that respect the people who use them.

There's no cloud, telemetry, accounts, or subscriptions. Just software you own, on hardware you control.

We ship tools we use and we'd want to use ourselves.

We also believe the best tools are quiet, fast, and permanent. Inkwell is our first release, with more to come.

In this age of rapid acceleration, we believe that the most important narratives are usually the ones least talked about. That includes privacy.

Our mission is to raise awareness and facilitate workflows aligned with this ethos.

---

## Feedback

Found a bug? Have a suggestion? We'd love to hear from you.

- **Open an issue** on this repo
- **Email us** at studio@4worlds.dev

We build on all platforms but can't test every setup, macOS reports especially welcome.
