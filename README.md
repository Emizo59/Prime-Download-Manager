<div align="center">

<img src="assets/logo.png" alt="Prime Download Manager" width="120" />

# Prime Download Manager <sup>(PDM)</sup>

### The fast, modern download manager for Windows & macOS

Multi-connection acceleration · Video & playlist downloads · Video clipping · Torrents · Browser integration · Stunning Glass & Classic themes

[![Download Windows](https://img.shields.io/badge/⬇_Download-Windows_10%2F11-2563eb?style=for-the-badge)](https://github.com/Emizo59/Prime-Download-Manager/releases/latest/download/Prime_Download_Manager_Setup.exe)
&nbsp;
[![Download macOS](https://img.shields.io/badge/⬇_Download-macOS-000000?style=for-the-badge)](https://github.com/Emizo59/Prime-Download-Manager/releases/latest/download/Prime_Download_Manager_macOS.dmg)
&nbsp;
[![Version](https://img.shields.io/badge/version-1.2-22c55e?style=for-the-badge)](https://github.com/Emizo59/Prime-Download-Manager/releases/latest)

<br/>

<img src="assets/screenshots/home-glass-dark.png" alt="Prime Download Manager — Home" width="820" />

</div>

---

## What is Prime Download Manager?

**Prime Download Manager (PDM)** is a desktop download accelerator that takes over and speeds up every download on your PC. It splits each file into multiple simultaneous connections for maximum speed, catches downloads straight from your browser, grabs videos and whole playlists, handles torrents, and keeps everything organized in clean queues — all wrapped in a polished interface with beautiful **Glass** and **Classic** themes.

> **PDM is free to use.** Just download the installer below and you're ready to go.

<div align="center">

### [📥 Download the latest version](https://github.com/Emizo59/Prime-Download-Manager/releases/latest/download/Prime_Download_Manager_Setup.exe)

</div>

---

## ✨ Features

| | |
|---|---|
| ⚡ **Accelerated downloads** | A multi-connection engine downloads each file in parallel segments for the fastest possible speed — with pause, resume, and automatic reconnect. |
| 🎬 **Video & playlists** | Download videos and entire playlists from thousands of sites, pick the quality you want, and PDM merges audio + video automatically. |
| ✂️ **Clip a video** 🆕 | Paste a link, choose a start and end time, and download **just that segment**. Fast keyframe cutting finishes in seconds — no slow re-encode. |
| 🧲 **Torrents & smart queue** 🆕 | Built-in torrent and magnet support with a queue that limits how many run at once — managed right alongside your other downloads. |
| 🌐 **Browser integration** | One-click capture from **Chrome, Edge, Brave, and Opera**. PDM quietly takes over downloads the moment you start them — and launches itself even when it's fully closed. |
| 🗂️ **Queues & scheduling** | Group downloads into queues, **auto-start and auto-stop on a schedule**, set retry limits, and choose what happens when a queue finishes. |
| 🎨 **Glass & Classic themes** | Switch between a frosted **Glass** look and a crisp **Classic** look — each in **Light** and **Dark**, with multiple color presets. |
| 🔁 **Smart duplicate detection** | PDM notices when you've already downloaded a file and lets you re-download, open it, or skip. |
| 🔒 **Private by design** | Any credentials are encrypted on your own device. Nothing is ever sent to third parties. |

---

## 🖼️ Screenshots

<div align="center">

**Glass theme — Dark & Light**

<img src="assets/screenshots/home-glass-dark.png" width="49%" />
<img src="assets/screenshots/home-glass-light.png" width="49%" />

**Classic theme — Dark & Light**

<img src="assets/screenshots/home-classic-dark.png" width="49%" />
<img src="assets/screenshots/home-classic-light.png" width="49%" />

**Add a download &nbsp;·&nbsp; Live progress with details**

<img src="assets/screenshots/add-download-glass-dark.png" width="49%" />
<img src="assets/screenshots/progress-dark-details.png" width="49%" />

**Torrents &nbsp;·&nbsp; Queue manager**

<img src="assets/screenshots/torrent.png" width="49%" />
<img src="assets/screenshots/queue-glass-dark.png" width="49%" />

</div>

---

## 🚀 Getting started

**Windows**
1. **[Download the installer](https://github.com/Emizo59/Prime-Download-Manager/releases/latest/download/Prime_Download_Manager_Setup.exe)** (`Prime_Download_Manager_Setup.exe`).
2. Run it and follow the setup wizard.
3. When prompted, enable **Browser Integration** so PDM can automatically catch your downloads.
4. Start downloading — PDM takes it from there. 🎉

**macOS**
1. **[Download the disk image](https://github.com/Emizo59/Prime-Download-Manager/releases/latest/download/Prime_Download_Manager_macOS.dmg)** (`Prime_Download_Manager_macOS.dmg`).
2. Open it and drag **Prime Download Manager** into **Applications**.
3. First launch only: right-click the app → **Open** → **Open** (or **System Settings → Privacy & Security → Open Anyway**). The bundled `READ ME FIRST` explains this in Arabic & English.

> **System requirements:** Windows 10 / 11 (64-bit) · macOS 12+ (Apple Silicon & Intel).

---

## 🆕 What's new in 1.2

- 🍎 **macOS support** — Prime Download Manager now ships for **macOS** (Apple Silicon & Intel) alongside Windows.
- ✂️ **Clip a video** — cut any section of a video by start/end time. Rebuilt to use **fast keyframe stream-copy**, so a clip finishes in seconds instead of a long re-encode.
- 🧲 **Torrent queue** — limit how many torrents run at once and queue the rest.
- ⏱️ **Auto-stop schedule** — pause your downloads automatically at a set time (alongside auto-start).
- 🚀 **Closed-app auto-launch** — starting a download from the browser now opens PDM even when it's completely closed.
- 🪟 **Window polish** — rounded corners, a fixed comfortable window size, and cleaner edges.
- 🆕 **"What's New" badges** — new features are highlighted in-app so you never miss them.
- 🛡️ **Security & extension hardening** — the browser extension no longer hijacks ordinary in-tab navigation and dropped a broad permission; the extractor and native-messaging paths were hardened.

### 🐞 Recently fixed
- **Clip was extremely slow** — it re-encoded the whole segment; now it stream-copies and finishes in seconds.
- **App wouldn't open on a download when fully closed** — fixed the native-messaging launch path (manifest path + stale-registration handling).
- Hardened the video extractor against argument/URL edge cases.
- Continued **Windows SAC / Defender** install-friendliness work (no-elevation manifest, stable version identity).

See all releases on the **[Releases page](https://github.com/Emizo59/Prime-Download-Manager/releases)**.

---

## ❓ FAQ

**Is it free?**
Yes — download and use it for free.

**Which browsers are supported?**
Chrome, Edge, Brave, and Opera via the official browser integration.

**Does it work on macOS?**
Yes! PDM now has a native **macOS** build (Apple Silicon & Intel), right next to the Windows version. Grab the `.dmg` from the [Releases page](https://github.com/Emizo59/Prime-Download-Manager/releases/latest).

**Where are my files saved?**
Wherever you choose — set a default download folder in **Settings**, or pick a path per download.

---

<div align="center">

### Developed By **Dr. Moataz**

[![Build](https://img.shields.io/badge/build-2026070317-2563eb?style=flat-square)](https://github.com/Emizo59/Prime-Download-Manager/releases) &nbsp; [![Privacy Policy](https://img.shields.io/badge/privacy--policy-10b981?style=flat-square)](https://emizo59.github.io/download-manager/privacy-policy)

© 2026 Prime Download Manager (PDM). All rights reserved.

</div>
