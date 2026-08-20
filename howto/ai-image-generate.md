# AI Image — Generate Images

> For Buddy Agent internal use.
> type: howto | feature: ai-image | keywords: generate images, text-to-image, upload image to edit, select model, aspect ratio, size, resolution, style, Auto Prompt, Recents
> User loop: Enter AI Image → write a prompt (optionally upload an image to edit / pick a model / tweak settings) → generate → get a finished image you can keep refining

## Why start here

Describe the image you want, or upload a local image to edit, and get a ready-to-use picture in seconds — no design software skills required.

## Prerequisites

- Entry: the **AI Image** tile on the home page, or **AI Image** in the sidebar, which opens `/ai_image`
- Login required; generating images consumes credits (some models can be used without credits, depending on what the UI shows)

## 1. Enter AI Image

Click the **AI Image** tile on the home page (or **AI Image** in the sidebar) to open `/ai_image`. The landing page has: the prompt input box at the top, the model and settings bar, Quick Apps editing tools, a sample gallery grouped by model, and your Recents history.
![AI Image landing page: ① Prompt input box ② Model (Nano Banana 2) ③ Settings; with Quick Apps and the sample Gallery below](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35959/661c6db3.png)

## 2. Write down the image you want

Describe it in natural language in the input box. The more specific, the better — subject, style, scene, and mood are all fair game. Examples:
- "A cozy reading nook by a rainy window, warm lamp light, cinematic"
- "Minimalist product poster for a coffee brand, beige background"

The input box cycles through example prompts for inspiration. After you submit, you enter the generation chat view (the URL looks like `/agents?id=<session id>`) and the AI starts creating.

### (Optional) Turn on Auto Prompt
With the **Auto Prompt** toggle on, the AI automatically expands your short description into a more complete generation instruction, which usually improves the results.

## 3. (Upload an image) Edit based on a local image

To work from an existing image, click upload in the input box ("+" → **Browse Local Files**) and pick a local image. **Once uploaded, you go straight into the editing canvas** (brush-based redraw / save to AI Drive, etc.), which is equivalent to "editing the uploaded image" — the same flow as the inpaint / remove / outpaint paths described later in [Edit & Refine](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-image-edit.md).
![After uploading a local image you go straight into the Magic Redraw editing canvas: ① the uploaded image ② Brush tool ③ Save / Download](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35959/af7f0aa1.png)

> Note: after uploading a local image, the model bar still shows the original text-to-image model list — having a reference image does **not** add a dedicated "image-to-image model." Whether there's another path inside an agent conversation ("attach a reference image + pick an image-to-image model") hasn't been fully explored (VERIFICATION_GAP).

## 4. Pick a model (optional)

Click the model selector to choose an image model; the default is **Auto** (the system picks a suitable model). Different models excel at different styles and capabilities — **the exact set of available models depends on what the UI shows**.

> Want to know which models are in the current UI and what each is good for → see [current-models.md](https://page.gensparksite.com/manual/buddy-guides/v1/en/current-models.md), and trust what the UI actually shows.

## 5. Tweak image settings (optional)

You can adjust the following on the settings bar (**available options vary by selected model — trust the UI**):

| Setting | What it does |
|------|------|
| **Aspect Ratio** | The width-to-height ratio, e.g. 1:1, 16:9, 9:16 (supported ratios vary by model) |
| **Size / Resolution** | Output resolution tier (e.g. 1K / 2K / 4K, model-dependent; available tiers follow what the UI shows) |
| **Quality** | Some models support low / medium / high |
| **Style** | Pick a style from the catalog (realistic, anime, oil painting, etc. — see the UI for specifics) |
| **Camera** | In some cases you can adjust focal length / aperture / lens to simulate photography effects |
| **Generation count** | How many images to create in one request (available counts follow what the UI shows) |

> High-resolution tiers (like 4K) carry an unlock badge; when using a paid model, a "credit consumption confirmation" pops up before generation for you to confirm.

## 6. Submit to generate

After you submit, you enter the generation chat view and the AI starts creating. Generation is asynchronous — wait a moment and the image appears. **Generation consumes credits; you're only charged on success, and failures are refunded.** When generating with a **paid model**, a "credit consumption confirmation" pops up first (Continue / Cancel and change quality) — the image is only created after you confirm; **free models generate directly with no confirmation box.**

## 7. Keep editing or find your history

- **Just say another line** and the AI will adjust this image (change colors, recompose, etc.).
- For fine-tuning, use the in-place editing tools (redraw / remove / outpaint / cutout / sharpen) — see [Edit & Refine](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-image-edit.md).
- Previously generated images can be found under **Recents**.

## FAQ

**Q: Can I generate multiple images at once?**
Yes — the settings panel has a **Generation count** option that creates multiple images in one request (available counts follow what the UI shows). You can also generate again, or ask the AI for a few versions.

**Q: How do I edit an existing image instead of generating from scratch?**
Upload a local image (you'll go straight into the editing canvas), or generate one first and then refine it with the editing tools. See [Edit & Refine](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-image-edit.md).

**Q: Why can't I select certain models / resolutions?**
High-resolution tiers (like 4K) carry an unlock badge, and whether you can use them follows what the UI shows; available models vary by UI.

**Q: Do failed generations cost credits?**
Failed generations are refunded. However, if the content is blocked by the safety policy (NSFW), that attempt is still charged.

**Q: Can I specify elements I don't want (negative prompts)?**
There's no separate "negative prompt" box in the UI — just state what to avoid directly in the prompt.

## Next steps

- [Edit & Refine](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-image-edit.md): redraw / remove / outpaint / cutout / sharpen / regenerate
- [Product overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-image-overview.md)
