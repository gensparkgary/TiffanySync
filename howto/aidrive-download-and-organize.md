# AI Drive — Downloading to the Drive, Compression & Trash

> For Buddy Agent internal use.
> type: howto | feature: aidrive | keywords: Drive, Downloader, Download For Me, download, video download, compress, decompress, delete, trash, restore, Restore All
> User loop: Use Downloader to paste a URL/description → select files → Save to AI Drive; select files to compress/decompress; delete files → Trash → Restore All to recover

## Why use these features

- **Pull resources from the web straight into your Drive**: Paste a link or describe what you need, and the AI finds and downloads it to your Drive — no need to save to your local computer first and then upload.
- **Bundle and unpack**: Compress multiple files into a single package for download with one click; archives you receive can be decompressed right in the Drive.
- **Recover from mistakes**: Deletions go to the Trash first and can be restored.

## Prerequisites

- Sign-in required
- Entry point: `https://www.genspark.ai/aidrive/files`

## Steps

### 1. Use Downloader to download resources to your Drive

Inside the Drive, click **"Download For Me"** to open the downloader (dialog title "Download into AI Drive").

Downloading takes two steps:

1. In the input field, **paste an HTTP/HTTPS link** or **describe in natural language what you want to download** ("Paste a HTTP/HTTPs link or tell me what to download"), then click **Confirm**.
2. Under "Select Files to Download," pick the files you want to save, choose a destination ("Save to:"), and click **"Save to AI Drive"** — the file downloads and appears in your Drive.
![Downloader: paste URL/description → Confirm → Select Files → Save to AI Drive](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35761/68ce0f1d.png)

### 2. Compress and decompress

Select files or folders, then use the action buttons:
- **Compress**: Compress into a .zip archive in your Drive (confirm "Confirm Compression")
- **Decompress**: Decompress a .zip archive in your Drive into a folder (confirm "Decompress Archive?")

Compression and decompression are background tasks, and progress is shown on the page.

### 3. Download files

Select a file and click **"Download."** When multiple files are selected, you'll first confirm "Compress and Download (into a single ZIP)," then they're bundled into a single zip and downloaded to your local machine together.

### 4. Delete to Trash

Select a file and click **"Delete,"** then confirm ("Move to trash"). The file moves to the **Trash** rather than being permanently deleted right away. Deleting a folder shows an extra warning (it removes all files inside the folder). Files in the Trash are **automatically and permanently cleared after 30 days** (each item is labeled "Will be permanently deleted on <date>").

### 5. Restore / permanently delete from Trash

Open the Trash at `https://www.genspark.ai/aidrive/trash`. You can:
- **Restore All**: Restore all files in the Trash back to their original locations
- **Delete All**: Empty the Trash (permanent deletion, cannot be recovered)
![Trash: Restore All / Delete All (auto-cleared after 30 days)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35761/fe3fd1ce.png)

## Notes

- Downloading, compressing, decompressing, deleting, and restoring **do not consume credits** (file management itself is free).
- Downloader's **direct-link (HTTP/HTTPS) downloads** were tested and **incur no charge**; the "smart/AI download" mode driven by natural-language descriptions was not tested this round — whether it is billed is to be determined by actual usage.
- Files downloaded to your Drive still take up Drive storage space.

## FAQ

**Q: What can Downloader download?**
Web files, videos, audio, images, documents, and other common online resources. You can either paste a link or describe what you want in natural language.

**Q: Can permanently deleted files be recovered?**
No. Once you empty the Trash with "Delete All," or once a file has sat in the Trash for 30 days and been automatically cleared, the action is irreversible. Only files still in the Trash can be recovered with **Restore All**.

**Q: What if compression or download fails?**
These are background tasks, and the page shows their status. You can retry, or check whether the link is valid ("Invalid URL").

## Next steps

- [Upload and organize files](https://page.gensparksite.com/manual/buddy-guides/v1/en/aidrive-get-started.md)
- [Share files with others](https://page.gensparksite.com/manual/buddy-guides/v1/en/aidrive-share.md)
- [Let AI work with files in your Drive](https://page.gensparksite.com/manual/buddy-guides/v1/en/aidrive-use-with-ai.md)
- [AI Drive overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/aidrive-overview.md)

---

## Screenshot checklist

| # | Screenshot ID | Capture location | What must be visible in the screenshot | Purpose |
|---|---------|---------|-------------------|------|
| 1 | `downloader` | Downloader dialog | Input field (paste URL/description), Select Files, Save to AI Drive | Show downloading to the Drive |
| 2 | `trash` | `/aidrive/trash` | Restore All / Delete All, 30-day auto-clear notice | Show the Trash |
