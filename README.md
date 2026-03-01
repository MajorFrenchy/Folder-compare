# Folder-compare
Compare the content of 2 folders / Drag and drop

# 📂 FolderDiff

A lightweight, single-file HTML tool to compare two folders and instantly see which subfolders are missing — no install, no server, no dependencies.

Built for anyone managing large collections of folders across multiple locations (backups, media libraries, game tables, etc.).

---

## ✨ Features

- **Click to browse** — select any folder directly from your file system
- **Missing folder detection** — instantly see what's in Folder A but not Folder B
- **Extra folder detection** — optionally show what's in Folder B but not Folder A
- **Filter & search** — quickly find specific folders in the results
- **Copy list** — copy all missing/extra folder names to clipboard in one click
- **Case sensitive toggle** — compare folder names exactly or case-insensitively
- **No install required** — just open the HTML file in any browser

---
<br>
<img src="![Screenshot](https://raw.githubusercontent.com/MajorFrenchy/Folder-compare/master/screenshot/sc01.jpg)" 
     style="width: 50%; height: auto;" 
     alt="VPX Merging Tool">

<br>

## 🚀 Usage

1. Download `compare_folders.html`
2. Open it in your browser (Chrome or Edge recommended)
3. Click the **Reference Folder** box and select your source folder
4. Click the **Target Folder** box and select the folder you want to check
5. Hit **Compare**

Results show immediately — missing folders highlighted in red, with a count summary at the top.

---

## 📋 Example Use Cases

- Checking a backup folder matches your original
- Verifying a media library is complete across two drives
- Comparing VPinball table collections between machines
- Any scenario where you need to know "what's missing?"

---

## ⚠️ Limitations

- **Browser file API limitation:** The browser can only detect subfolders that contain at least one file inside them. Completely empty subfolders will not be detected.
- Compares folder **names only** — not file contents or sizes
- Only checks one level deep (immediate subfolders)

---

## 🛠️ Tech

Pure HTML, CSS, and vanilla JavaScript. No frameworks, no build step, no server.
Uses the [`webkitdirectory`](https://developer.mozilla.org/en-US/docs/Web/API/HTMLInputElement/webkitdirectory) attribute to read folder contents directly in the browser.

---

## 📄 License

MIT — do whatever you want with it.
