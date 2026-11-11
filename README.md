# GPT Import Chat

GPT Import Chat is a free Chrome, Edge and Brave extension to **export, back up and transfer ChatGPT conversations** as local files. Keep a readable copy of a chat or move its text into another tool that accepts JSON or Markdown.

[Download v0.4.0](https://github.com/eaglewithorange-AAA/gpt-import-chat/releases/download/v0.4.0/osg-chat-bridge-v0.4.0.zip) · [Release notes](https://github.com/eaglewithorange-AAA/gpt-import-chat/releases/tag/v0.4.0) · [Report an issue](https://github.com/eaglewithorange-AAA/gpt-import-chat/issues)

## Features

- **ZIP backup** with conversation JSON, Markdown, capture metadata, a scan report and integrity checks.
- **TXT and PDF export** for the collected conversation or a selected message range.
- **Adjustable scanning** with pause, resume, preview and a verification pass for gaps detected during capture.
- **Local recovery checkpoints** for resuming collection in the same chat after a reload.
- **English and Russian controls.** Original message text, observed order and available dates are preserved.
- **Local processing.** The extension reads messages displayed in the open chat tab and saves the export on your device. No separate service or API key is required.

## Install

1. [Download the release ZIP](https://github.com/eaglewithorange-AAA/gpt-import-chat/releases/download/v0.4.0/osg-chat-bridge-v0.4.0.zip) and extract it.
2. Open `chrome://extensions`, `edge://extensions` or `brave://extensions`.
3. Enable **Developer mode** and choose **Load unpacked**.
4. Select the extracted `osg-chat-bridge` folder containing `manifest.json`. The v0.4.0 package appears as **OS G — Мост памяти / Chat Bridge** in the browser.
5. Reload your ChatGPT tab before using the extension.

## Export a conversation

1. Open the ChatGPT conversation and scroll to the first message you want to collect.
2. Click the extension icon to open the panel, then choose **Start**.
3. Review the captured range and run **Verify** to check for detected gaps.
4. Save a **ZIP** for JSON and Markdown, or choose **TXT** or **PDF** for a readable copy.

## Capture limits

The export covers messages the extension can read from the visible conversation branch. A verification pass cannot establish complete server history. Images and binary attachments are outside the export, and some glyphs may display differently in PDF. Transfer uses the exported files. Direct import back into ChatGPT is unverified.

Originally released as **OS G Chat Bridge**, part of **OS G — The Flying Dutchman**. Created by [eaglewithorange-AAA](https://github.com/eaglewithorange-AAA).
