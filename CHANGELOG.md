# Changelog

All notable changes to Inkwell will be documented here.

## [v1.5.0] — 2026-05-06

### New Features
- **SQLite Persistence** — workspace state, files, recent files, templates, themes, and version history now live in a real local database (`inkwell.db`) instead of browser localStorage. Faster, more reliable, no storage cap.
- **Automatic migration** on first launch v1.4 users upgrade cleanly with no data loss.

### Improved
- Polished native save dialog
- Search no longer lags on large files (debounced input, removed full re-render)

### Bug Fixes
- Window dragging restored

[v1.5.0]: https://github.com/4worlds4w-svg/inkwell/releases/tag/v1.5.0

---


## [v1.4.0] — 2026-03-30

### New Features
- **Typst PDF Engine** — replaced WebView2 print-to-PDF with a native Rust typesetting engine. Professional typography, chapter breaks, math equations, and Mermaid diagrams in PDFs. Cross-platform — no browser dependency.
- **Clickable TOC links in PDFs** — exported PDFs now include navigable headings via Typst labels.

### Improved
- Preview TOC links now scroll to heading instead of opening browser
- Ctrl+O (open file) and Ctrl+Shift+P (export PDF) keyboard shortcuts restored
- Consistent error types across all export functions

### Security
- HTML export title escaped (XSS fix)

### Platforms
- Microsoft Store launch as "Inkwell Editor"

[v1.4.0]: https://github.com/4worlds4w-svg/inkwell/releases/tag/v1.4.0

---

## [v1.3.0] — 2026-03-24

### New Features
- **Command Palette** (Ctrl+K) — fuzzy search all 22 actions, keyboard navigation, shortcut hints
- **Custom Theme Creator** — 6 color pickers, live preview, derived colors computed automatically

### Improved
- HTML and PDF exports now include syntax highlighting, KaTeX math fonts, Mermaid diagram SVGs, and H2-based chapter breaks for PDF
- PDF export no longer freezes the UI during generation

### Security
- Improved input sanitization and file operation safety across the board

[v1.3.0]: https://github.com/4worlds4w-svg/inkwell/releases/tag/v1.3.0

---

## [v1.2.1] — 2026-03-21

### Platforms
- Linux: added .desktop file and bundled icon for proper app launcher integration

[v1.2.1]: https://github.com/4worlds4w-svg/inkwell/releases/tag/v1.2.1

---

## [v1.2] — 2026-03-17

### New Features
- **Workspace & File Tree** — open any folder, browse .md files from the sidebar, persists between sessions
- **Mermaid Diagrams** — flowcharts, sequence diagrams, and more in fenced code blocks with live rendering
- **LaTeX Math (KaTeX)** — inline `$...$` and display `$$...$$` equations
- **Custom Title Bar** — no OS chrome, fully themed window with drag/snap/minimize/maximize/close

### UX
- Unified brand identity across all 4 themes with signature rust accent

[v1.2]: https://github.com/4worlds4w-svg/inkwell/releases/tag/v1.2

---

## [v1.1] — 2026-03-12

### New Features
- **Find & Replace** (Ctrl+F) — search with replace single or replace all, highlights matches in preview
- **Typewriter mode** — keeps cursor line centered while typing, toggle in toolbar, persists across sessions
- **History diff viewer** — two tabs in version history modal: Preview (rendered markdown) and Changes (line-by-line diff with green/red highlights, context collapsing, +added/−removed stats)

### UX
- Split divider — wider grab area, more visible, double-click to reset to 50/50
- Search bar closes on outside click, clears inputs on reopen

[v1.1]: https://github.com/4worlds4w-svg/inkwell/releases/tag/v1.1

---

## [v1.0.1] — 2026-02-27

### Bug Fixes
- PDF export no longer fails silently on macOS — error messages are now shown to the user
- Fixed line highlight misalignment on macOS
- Fixed unreachable code compiler warning on macOS builds

### UX
- Added Save button in the sidebar Actions section

### Platforms
- Added macOS support (DMG)

[v1.0.1]: https://github.com/4worlds4w-svg/inkwell/releases/tag/v1.0.1

---

## [v1.0.0] — 2026-02-26

Initial release.

### Editor
- Split view with draggable divider and live preview
- Current line highlight with accent-colored cursor
- Tabbed editing with drag & drop support
- Auto-save on every keystroke
- Recent files and native save dialogs

### Themes & Fonts
- 4 themes: Editorial, Midnight, Mono, Sepia
- 3 font families: Crimson Pro, Inter, IBM Plex Mono
- Adjustable font size (14–24px)

### Markdown
- Full GitHub Flavored Markdown support
- Syntax highlighting for 30+ languages
- Copy buttons on code blocks
- Styled tables, blockquotes, and checklists

### Features
- Focus mode — hide everything except your words
- 10 built-in templates + custom templates
- Auto-generated table of contents with click-to-jump
- Version history with auto-snapshots every 5 minutes
- Document search with match highlighting
- Image paste from clipboard and drag-to-editor
- PDF and HTML export (Pro)

### Platforms
- Windows (11 MB)
- Linux (8.5 MB)

[v1.0.0]: https://github.com/4worlds4w-svg/inkwell/releases/tag/v1.0.0
