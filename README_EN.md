# Hope Editor

[中文](README.md) · **English**

## In one sentence

Open, edit, and read Markdown, TXT, PDF, and HTML files directly on your Mac, with a two-page book mode for long documents.

## When it helps

- You want a local document tool with no account and no cloud upload.
- You often read AI-generated Markdown, HTML reports, or long notes.
- You want live Markdown editing and preview in one window.
- You prefer reading a PDF or long article as facing pages.

[Download the latest release](https://github.com/HopeeeeZhu/hope-file-editor/releases/latest)

> The current build is for Apple Silicon Macs and requires macOS 10.13 or later. Intel Macs are not supported yet.

![Hope Editor overview](docs/images/hope-editor-overview.jpg)

## Install in one minute

1. Open the latest release page above.
2. Download the `.dmg` file from **Assets**.
3. Open the file and drag Hope Editor into Applications.
4. On the first launch, right-click the app in Finder and choose **Open**.

The app is not signed with an Apple Developer ID. If macOS still blocks it, go to **System Settings → Privacy & Security → Open Anyway**. As a last resort:

```bash
xattr -cr '/Applications/hope的编辑器.app'
```

## What you can do

- Open Markdown, TXT, PDF, and HTML documents.
- Edit Markdown and TXT with a live preview.
- Browse nearby documents from the folder sidebar.
- Read long documents in two-page book mode.
- Search the current document or all `.md` and `.txt` files in its folder.
- Work with multiple documents in tabs.
- Switch between light and dark themes and adjust text size.

## Common shortcuts

| Shortcut | Action |
| --- | --- |
| `⌘O` | Open a file |
| `⌘S` | Save the current file |
| `⌘F` | Search the current document |
| `Enter` | Next search result |
| `Shift + Enter` | Previous search result |
| `⌘W` | Close the current document |

## Privacy

No login or internet connection is required. Reading, editing, and saving all happen locally. Web links open in your default browser.

## Current release

- Version: v0.6.3
- Package size: about 8.5 MB
- Platform: macOS 10.13+, Apple Silicon (arm64)
- Signing: no Apple Developer ID; the first launch requires manual confirmation
