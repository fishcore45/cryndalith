CRYNDALITH
A privacy-first, fully client-side personal media & file link vault.
CRYNDALITH is a beautiful, in development single-file HTML web app that lets you organize and store direct links to your videos, images, and files — entirely in your browser.
No accounts. No servers. No tracking. No data leaves your device.

✨ Features

100% Local & Private — Everything is stored in your browser's localStorage
Pure Client-Side — No backend, no uploads, no third-party dependencies
Three Categories:
Video Links (.mp4, .webm, direct streams)
Image Links (jpg, png, webp, etc.)
General Files (PDF, ZIP, audio, documents, etc.)

Export / Import your entire collection as a clean JSON file
Progressive Web App (PWA) — Installable on desktop and mobile
Cyberpunk / VHS aesthetic with scanlines, noise, and glitch styling
Persistent across sessions — Your vault stays even after closing the browser
Mobile-friendly and works offline once installed


How It Works

Open the index.html file in any modern browser
Paste direct links to your media or files
Everything is saved automatically in your browser
Optionally export your collection as myvault.json for backup or sharing
Load collections from a URL or local JSON file

Important: Only direct file links work (no YouTube, Google Drive preview links, etc.). The links must point straight to the raw file.

Privacy & Security

No data is ever sent to any server
All content stays on your device
You are fully responsible for the legality of the links you store
Recommended for personal use and legal content only


Installation (PWA)

Open the HTML file
Click the install icon in your browser (or use "Add to Home Screen" on mobile)
The app will work offline and receive automatic updates when you modify the file


File Structure
textcryndalith-file-vault/
├── index.html          ← Main application (single file)
├── manifest.json       ← PWA configuration
├── sw.js               ← Service Worker (for offline support)
└── README.md

Usage Tips

Use direct raw links (e.g. https://example.com/video.mp4)
For best performance, host large media on reliable file hosts (Catbox, Pixeldrain, etc.)
Export your vault regularly as a backup
You can share the exported JSON with trusted people (they can load it via the "Load Collection" feature)


Disclaimer
This tool is provided as-is for personal use.
The author is not responsible for any misuse or for the content of the links added by users.

License
This project is open-source and free to use, modify, and distribute for personal and non-commercial purposes.
