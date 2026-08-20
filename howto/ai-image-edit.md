# AI Image — Editing & Refinement

> For Buddy Agent internal use.
> type: howto | feature: ai-image | keywords: edit image, edit, inpaint, inpaint, erase, background removal, expand, unblur, sharpness enhancement, regenerate, Recreate, Quick Apps
> User loop: pick an image (generated / uploaded / from history) → choose an editing tool → refine → get the fixed image

## Why use the editing tools

When a generated image is just slightly off, you don't have to start over — you can redraw a region to swap out a chunk, erase unwanted objects, expand the canvas outward, cut out the background, sharpen a blurry image, or simply regenerate a new version. Editing images normally takes dedicated software; here you can do it all in one place.

## Prerequisites

- Entry point: the **Quick Apps** (quick editing tools) on the `/ai_image` landing page, or open an image from Recents / a generation result
- Every edit regenerates the image and **consumes credits** (paid members can use some models credit-free — see the UI and your membership tier for specifics)

## 1. Pick an image to edit

Three starting points:
- **Quick Apps**: the quick-edit tiles on the landing page; tap a tool, then upload/select an image to jump straight into the editing view
- **Generation result**: edit an image you just generated
- **Recents history**: open a past image, then choose an editing tool from the detail view
![Open an image's detail viewer; the toolbar at the top holds the editing tools: ① Edit tools (Quick Apps: Draw to Edit / Remove Background / Erase / Expand / Image Unblur) ② Image to Video ③ the current image](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35959/f11f4aa5.png)

## 2. Quick Apps: five one-click / semi-automatic editing tools

The Quick Apps on the landing page offer five common editing tools:

| Tool | What it does | How to use |
|------|--------|------|
| **Background Remover** | Cut out the background | One click — removes the background automatically |
| **Magic Eraser** | Erase unwanted objects in the image | Brush over the area to erase → generate |
| **Magic Redraw** | Locally redraw a region, replacing a chunk with what you describe | Brush over the area + write a line on what to change it to → generate |
| **Photo Unblur** | Boost sharpness / enhance detail | One click — sharpens automatically |
| **Image Expand** | Expand the canvas (paint outward) | Choose the expansion direction/ratio → generate |

> **Photo Unblur is the sharpness-enhancement entry point**: under the hood it calls a sharpness-enhancement model (see the UI for the exact model name, or [current-models.md](https://page.gensparksite.com/manual/buddy-guides/v1/en/current-models.md)). To sharpen an image / enhance detail, just use Photo Unblur — AI Image has no separate "Upscale" action button.

### How to use the brush tools (Magic Eraser / Magic Redraw)
Once in the editing view, use the brush to paint over the area you want to work on (brush size is adjustable, with undo/redo/reset). **Magic Eraser** erases immediately after you brush; **Magic Redraw** still requires you to write a line on "what to change it to" before generating.

### One-click tools (Background Remover / Photo Unblur)
Run them directly after selecting an image — no brushing needed.

### Expand (Image Expand)
Choose which direction to expand and what ratio to expand to; the AI fills in the newly added canvas area.

## 3. Continue from a single image's detail view

Open an image from Recents or a generation result; the detail view has a toolbar plus a row of conversational actions:

| Action | What it does |
|------|--------|
| **Draw to Edit** | Brush an area + describe it to redraw locally (same pipeline as Magic Redraw) |
| **Remove Background** | One-click background cutout |
| **Erase** | Brush to erase unwanted objects (same pipeline as Magic Eraser) |
| **Expand** | Choose a direction/ratio to expand the canvas |
| **Image Unblur** | Boost sharpness / enhance detail (the entry point for the sharpness-enhancement capability — same backend as Quick Apps' Photo Unblur) |
| **Image to Video** | Use this image as a starting point to generate a video (jumps to video generation) |
| **Recreate** (conversation row) | Regenerate another version with the same settings (a different result) |
| **Remix** (conversation row) | Keep tweaking on top of this image |

> **There is no standalone "Upscale" button**: to boost sharpness / enhance detail, use **Image Unblur** (in the detail toolbar) or **Photo Unblur** in Quick Apps — both go through the sharpness-enhancement model.
>
> **Image to Video** hands the image off to the video generation capability (jumps to `/agents?type=video_generation_agent` with the source image attached) — an extension that turns a static image into motion; for the details of video generation, refer to the video product.

## 4. About credits

Every edit (redraw / erase / cutout / sharpen / expand / Recreate) is essentially **regenerating an image**, so **all of them consume credits** — there's no split where "annotation is free and only generation is charged"; the moment the final result triggers a generation, it's billed. Members can use some models credit-free — see the UI and your membership tier. Failed generations refund the credits.

## FAQ

**Q: Will editing overwrite the original image?**
No — every edit produces a new image, and the original stays in Recents.

**Q: What's the difference between Magic Eraser and Magic Redraw?**
Both start by brushing over a region. Magic Eraser simply "erases" the brushed content; Magic Redraw "replaces it with the new content you describe," so you need to write an extra line on what to change it to.

**Q: Are one-click operations like background cutout and sharpening free?**
No — they also regenerate the image, so they deduct credits (except for member-free models).

**Q: How do I sharpen / upscale an image?**
Use **Image Unblur** (in the detail toolbar) or **Photo Unblur** (in Quick Apps) — both go through the sharpness-enhancement model. AI Image has no separate "Upscale" action button.

**Q: Can I turn an image into a video?**
Yes — use **Image to Video** in the image detail view; it generates a video starting from this image.

## Next steps

- [Generate images](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-image-generate.md): create from a prompt / upload a local image to edit
- [Product overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-image-overview.md)
