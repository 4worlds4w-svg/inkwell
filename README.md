![Inkwell Banner](banner.png)
<p align="center">
  <img src="https://img.shields.io/github/v/release/4worlds4w-svg/inkwell?label=version" />
  <img src="https://img.shields.io/github/downloads/4worlds4w-svg/inkwell/total" />
  <img src="https://img.shields.io/badge/platform-Windows%20%7C%20macOS%20%7C%20Linux-lightgrey" />
  <img src="https://img.shields.io/badge/built%20with-Tauri%20v2-blue" />
  <img src="https://img.shields.io/badge/license-Free%20%2B%20Pro-green" />
</p>

# Inkwell

**The sovereign markdown editor.**

Lightweight, beautiful, fast, and portable.

![Inkwell Screenshot](screenshot.png)

---

## Download

**[Download for Windows](https://github.com/4worlds4w-svg/inkwell/releases/download/v1.5.0/inkwell.exe)** — `inkwell.exe`

**[Download for macOS](https://github.com/4worlds4w-svg/inkwell/releases/download/v1.5.0/Inkwell_1.5.0_aarch64.dmg)** — `Inkwell_1.5.0_aarch64.dmg`

**[Download for Linux](https://github.com/4worlds4w-svg/inkwell/releases/download/v1.5.0/Inkwell_1.5.0_amd64.deb)** — `Inkwell_1.5.0_amd64.deb`


Or via winget:

```bash
winget install 4Worlds.Inkwell
```

Or from the Microsoft Store:

<a href="https://apps.microsoft.com/detail/9PFTZ8H9X04K">
  <img src="https://get.microsoft.com/images/en-us%20dark.svg" alt="Get it from Microsoft" width="200" />
</a>


---

## Getting Started

**Windows:** Download and unzip. Run `inkwell.exe`. Start writing.

> Windows SmartScreen may warn you on first launch, this is expected for unsigned apps. Click **"More info"** → **"Run anyway"**.

**macOS:** Download the `.dmg` and drag Inkwell to Applications.

> macOS Gatekeeper may block unsigned apps. If that happens, run:
> ```bash
> xattr -cr /Applications/Inkwell.app
> ```
> Then open normally.

**Linux:** Download and extract, then:
```bash
chmod +x inkwell
./inkwell
```

---

## Features

**Typst PDF Engine** — Native Rust typesetting for PDF exports. Professional typography, chapter breaks, math equations, and Mermaid diagrams. Cross-platform, no browser dependency.

**SQLite Persistence** — Workspace state, files, templates, themes, and history live in a local database (`inkwell.db`). Faster, more reliable, no browser storage limits.

**Command Palette** — Press Ctrl+K to fuzzy-search all actions. Full keyboard navigation with shortcut hints.

**Custom Themes** — Build your own theme with 6 color pickers and live preview.

**Workspace & File Tree** — Open any folder, browse and switch between .md files from the sidebar. Persists between sessions.

**Mermaid Diagrams** — Write flowcharts, sequence diagrams, and more in fenced code blocks. Live rendering in the preview pane.

**LaTeX Math (KaTeX)** — Inline `$...$` and display `$$...$$` equations rendered beautifully. Full KaTeX support.

**Custom Title Bar** — No OS chrome. The entire window is Inkwell, themed edge to edge.

**Editor** — Split view with a draggable divider. Live preview as you type. Current line highlight with accent-colored cursor.

**4 Themes** — Editorial (warm cream), Midnight (warm charcoal), Mono (cool steel), Sepia (aged parchment). All unified by Inkwell's signature accent.

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

**[Get a Pro license on Gumroad →](https://4worlds.gumroad.com/l/inkwell)**

---

## Technical Details

| | |
|-|-|
| **Size** | ~44 MB (Windows) · ~18 MB (macOS · Linux) |
| **Built with** | Rust + Tauri v2, vanilla JS (zero dependencies) |
| **Startup** | < 1 second |
| **Tested with** | 65k+ word documents |
| **Data storage** | 100% local, zero telemetry |

---

## Philosophy

[Inkwell](https://inkwell.4worlds.dev/) is the first release from **[4Worlds](https://4worlds.dev)**, a small independent software studio building tools that respect the people who use them.

There's no cloud, telemetry, accounts, or subscriptions. Just software you own, on hardware you control.

We ship tools we use and we'd want to use ourselves.

We also believe the best tools are quiet, fast, and permanent. Inkwell is our first release, with more to come.

In this age of rapid acceleration, we believe that the most important narratives are usually the ones least talked about. That includes privacy.

Our mission is to raise awareness and facilitate workflows aligned with this ethos.

---

## Feedback

- **[Documentation](https://inkwell.4worlds.dev)** — guides, features, shortcuts
- **[Discussions](https://github.com/4worlds4w-svg/inkwell/discussions)** — feature requests, ideas, or just say hi
- **Open an issue** on this repo
- **Email us** at studio@4worlds.dev

We build on all platforms but can't test every setup, macOS reports especially welcome.

## Star History

<a href="https://www.star-history.com/?repos=4worlds4w-svg%2Finkwell&type=timeline&legend=top-left">
 <picture>
   <source media="(prefers-color-scheme: dark)" srcset="https://api.star-history.com/image?repos=4worlds4w-svg/inkwell&type=timeline&theme=dark&legend=top-left" />
   <source media="(prefers-color-scheme: light)" srcset="https://api.star-history.com/image?repos=4worlds4w-svg/inkwell&type=timeline&legend=top-left" />
   <img alt="Star History Chart" src="https://api.star-history.com/image?repos=4worlds4w-svg/inkwell&type=timeline&legend=top-left" />
 </picture>
</a>
