# 🎬 YT Drop — YouTube Downloader

<img width="3594" height="1830" alt="image" src="https://github.com/user-attachments/assets/b1a042fa-8a12-43e9-ac8c-d0219e27056d" />


A lightweight, browser-based tool that generates [yt-dlp](https://github.com/yt-dlp/yt-dlp) commands for downloading YouTube videos. No extensions, no accounts, no limits — just paste a URL and go.

![HTML](https://img.shields.io/badge/HTML-single%20file-orange)
![yt-dlp](https://img.shields.io/badge/powered%20by-yt--dlp-red)
![License](https://img.shields.io/badge/license-MIT-blue)

---

## ✨ Features

- **Paste & generate** — auto-detects YouTube URLs from your clipboard
- **Video downloads** — choose quality (360p to 1080p or best) and format (MP4, MKV, WebM)
- **Audio-only** — extract MP3, M4A, or Opus from any video
- **Playlist support** — download entire playlists with organized folder structure
- **One-click .bat** — download a Windows batch file and just double-click it
- **No installation** — single HTML file, works in any browser

---

## 🚀 Quick Start

### 1. One-time setup

Install [Python](https://python.org), then run:

```bash
pip install yt-dlp
```

### 2. Open the app

Download `youtube-downloader.html` and open it in any browser (Chrome, Firefox, Edge, etc.)

### 3. Download a video

1. Paste a YouTube URL into the input box
2. Select your quality and format
3. Click **Generate Download Script**
4. Either:
   - Copy the command → paste into Command Prompt → press Enter
   - Download the `.bat` file → double-click it

Files are saved to your **Downloads** folder automatically.

---

## 📋 Requirements

| Requirement | Notes |
|-------------|-------|
| Python 3.7+ | [python.org](https://python.org) |
| yt-dlp | `pip install yt-dlp` |
| ffmpeg (optional) | Required for format merging (1080p MP4). [Install guide](https://ffmpeg.org/download.html) |

> **Tip:** For best quality (1080p), install ffmpeg. Without it, yt-dlp will download the best single-file format available.

---

## 🖥️ How It Works

YT Drop is a pure HTML/CSS/JS app — no server, no backend. It generates a `yt-dlp` command based on your selected options, which you run locally on your PC.

```
[Browser UI] → generates → [yt-dlp command] → runs in → [Command Prompt] → downloads to → [Downloads folder]
```

---

## 📁 File Structure

```
yt-drop/
└── youtube-downloader.html   # The entire app — single file
└── README.md
```

---

## 🔧 Updating yt-dlp

YouTube changes frequently. If downloads break, update yt-dlp:

```bash
pip install -U yt-dlp
```

---

## ⚠️ Disclaimer

This tool is intended for **personal use only**. Please respect YouTube's [Terms of Service](https://www.youtube.com/t/terms) and only download content you have the right to download (e.g. your own videos, Creative Commons licensed content, or content explicitly allowed by the creator).

---

## 🙏 Credits

Powered by [yt-dlp](https://github.com/yt-dlp/yt-dlp) — the community-maintained YouTube download library.
