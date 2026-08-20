# AI Drive — Let AI Work with Your Cloud Files

> For Buddy Agent internal use.
> type: howto | feature: aidrive | keywords: cloud drive, Super Agent, AI entry point, agent file read/write
> User loop: select a file in the drive → click the Super Agent entry on the file → enter Super Agent with the file → produce output back to the drive

## Why Start with AI From Your Cloud Files

- **No more back-and-forth shuffling**: Hand a file in your drive off to AI with one click—no need to download it locally first and re-upload it to another product.
- **Send straight to Super Agent**: Super Agent automatically plans and coordinates the right tools to handle the file (research, organize, build a presentation, generate a video, and more).
- **Output returns to the drive automatically**: Files processed by AI land back in your drive, all in one place.

## Prerequisites

- Sign-in required
- The file you want to process is already in your drive (entry point: `https://www.genspark.ai/aidrive/files`)

## Steps

### 1. Find the Super Agent Entry on a File

Hover over the row of the target file (**not a folder**) in your drive, and a **"Super Agent"** button will appear on that row.
![Super Agent entry shown when hovering over a file row](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35761/ed67a0de.png)

### 2. Click Super Agent to Hand the File to AI

Click **"Super Agent"**, and the system opens Super Agent with this file (in a new tab). There you enter your specific request and run it—Super Agent automatically plans and coordinates the right tools to handle it (research, organize, build a presentation, generate a video, and more), and the output is saved back to the drive.

> Note: The AI entry on cloud files currently has **only "Super Agent"**—it coordinates research, presentation building, video generation, and more on its own, so there's no need to separately choose "AI Slides / Deep Research / Image to Video" within the drive. If you want to use a specific product directly, open that product first and then upload or select the file.

## How Agents Use Your Cloud Files

Beyond manually starting from a file, Genspark's agents (Super Agent, Genspark Code, and others) **can read and write to your drive directly** while running tasks:
- Tell an agent to "download materials to my AI Drive," "read a file in my drive," or "save the output to AI Drive," and it will operate on your drive files directly.
- Files produced by Genspark Code, downloaded materials, and generated reports can all land in the drive and be reused across tasks.

## Notes

- **Handing a file to AI is billed according to the downstream product's rules** (the credit rules of Super Agent / Slides / Deep Research, etc.)—those charges belong to that product, not to the drive itself. The drive's core file management (upload/download/organize) remains free.
- The Super Agent entry is **unavailable** when the file is empty (0 bytes)—the button is grayed out and the cursor shows not-allowed.

## FAQ

**Q: Does it cost money for AI to process cloud files?**
Storing the file in the drive costs nothing; once you hand it to Super Agent / Slides or another AI to process, it's billed according to that product's rules.

**Q: Which files work with this entry?**
All **non-folder** files work (hover over the file row and the Super Agent button appears); folders and 0-byte empty files are not supported. Super Agent decides how to handle the file based on its content.

**Q: Where do the files produced by the agent go?**
They're usually saved to your drive, where you can find them all in one place (see the [Overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/aidrive-overview.md)).

## Next Steps

- [Upload and organize files](https://page.gensparksite.com/manual/buddy-guides/v1/en/aidrive-get-started.md)
- [Share files with others](https://page.gensparksite.com/manual/buddy-guides/v1/en/aidrive-share.md)
- [AI Drive overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/aidrive-overview.md)

---

## Screenshot List

| # | Screenshot ID | Capture Location | What Must Be Visible in the Screenshot | Purpose |
|---|---------|---------|-------------------|------|
| 1 | `ai-options` | File row hover | Super Agent button (including the disabled state for 0-byte files) | Show starting AI from a file |
