# AI Video — Generate Videos

> For Buddy Agent internal use.
> type: howto | feature: ai-video | keywords: generate video, text to video, text to video, write prompt, choose model, aspect ratio, duration, Auto Prompt, play, download
> User loop: Enter AI Video → write a prompt (optionally choose a model / adjust aspect ratio, size & duration in Setting) → generate → get a playable, downloadable video you can keep iterating on

## Why Start Here

Describe the scene and action you want, wait a moment, and you get a ready-to-use video—no filming or editing skills required.

## Prerequisites

- Entry point: the **AI Video** card in the Content Creation section of the **All Agents** page (`/agents`), or **AI Video** in the sidebar **New** hover popover, which takes you to `/agents?type=video_generation_agent`. Note: **the home page's first-row icon strip no longer shows AI Video directly** (the entry moved into the home section popover and the locations above).
- Login required; generating videos consumes credits (varies by model / duration / resolution—see the interface for specifics)

## 1. Enter AI Video

Once on the AI Video landing page you'll see: a prompt input box at the top, and below it a parameter bar **Model | Setting | Auto Prompt | Assets** (aspect ratio, resolution, and **duration** are all tucked inside the **Setting** popover—see Section 4; to attach images/media, use the **Assets** panel on the right or the "+" menu in the input box).

![AI Video landing page parameter bar: Model · Setting · Auto Prompt · Assets (this older screenshot still shows a standalone Duration item; duration has since moved into the Setting popover)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51197/5696f3aa.png)

## 2. Write the Video You Want

Describe it in natural language in the input box. It works better when you spell out the **subject, action, camera, and mood**. Examples:

- "A golden retriever running on a beach at sunset, slow motion, cinematic"
- "Aerial drone shot flying over a misty mountain forest at dawn"
- "A cup of coffee with steam rising, cozy cafe, soft morning light"

After you submit, you enter the generation chat panel and the AI starts generating the video.

### (Optional) Turn On Auto Prompt

With the **Auto Prompt** toggle on, the AI automatically expands your short description into a more complete generation prompt, which usually improves results.

## 3. Choose a Model (Optional)

Click the model selector to pick a video generation model. The **first item** in the selector is **Auto-select Models** (which lets the system pick a model for your task), but **the default selection is a specific high-quality video model** (not Auto)—you can keep the default, switch to Auto-select, or choose another model. Different models excel at different styles, durations, and capabilities; some are labeled "requires input image" (for image-to-video—see [Image to Video](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-video-image-to-video.md)). **The default and available models are whatever the interface shows.**

![Model selector: the first item in the list is Auto-select Models, but the default selection is a specific model (radio button filled)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36031/234cb108.png)

> Want to know which video models are in the current interface and what each is good for → see [current-models.md](https://page.gensparksite.com/manual/buddy-guides/v1/en/current-models.md), and rely on what the interface actually shows.

## 4. Adjust Output Parameters (Optional)

The visual parameters are all tucked inside the **Setting** popover on the parameter bar (**which options are adjustable varies by the selected model—rely on the interface**):

| Item in Setting | What it does |
|------|------|
| **Video Size (resolution)** | Resolution tier, e.g. 720p / 1080p / 4k (available tiers follow what the UI shows) |
| **Aspect Ratio** | Frame aspect ratio, **options vary by model** |
| **Duration** | Video length: models with selectable durations show a **slider + a seconds input** (the selectable range varies by model); models whose duration is derived from the input material show "Based on input" |
| **Generation count** | How many videos to generate per run (available counts follow what the UI shows) |
| **With Audio** | Whether to generate with audio (on/off) |
| **Fast Mode** | Faster generation mode (on/off) |

![Setting popover: Video Size (720p / 1080p / 4k) · Aspect Ratio · With Audio · Fast Mode (the current version of the popover also includes the Duration slider and Generation count)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51197/e1474ff6.png)

> **Duration is open to every plan**: duration is no longer unlocked by membership tier—any account can drag the duration slider within the range the selected model supports, and picking a longer duration will not trigger an upgrade prompt. The selectable range is determined by the chosen model.

> ⚠️ **Whether free accounts can produce a video follows the UI prompts**: **the default selection is a high-quality (premium) model**—for free/expired accounts, a "Manage Your Plan" upgrade prompt can still pop up at the **video generation step** after you submit, and no video is produced. Whether you can generate directly follows what the UI shows.

## 5. Submit to Generate

After you submit, you enter the generation chat panel and the AI starts generating. **Generation is asynchronous**—video generation is usually slower than image generation, so you'll wait a bit, and you can see progress along the way. **Generation consumes credits; you're only charged on success, and failures are refunded.** Note: **when free/expired accounts use the default high-quality model, the upgrade prompt ("Manage Your Plan") may not pop up until generation is already underway**—at which point no video is produced, and you continue as the UI prompts.

## 6. Play, Download, Keep Iterating

- Once generation is done, you can **play** a preview directly in the results area.
- To save it, **download** the video file from the result.
- Not happy? **Just say another line** to have the AI adjust (change the camera, the action, the duration, etc.), and it produces another version.

![The finished video playing in the Assets panel on the right, with play / volume / fullscreen controls, ready to preview and download](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36031/a07c27fc.png)

## FAQ

**Q: How long does it take to generate a video?**
Slower than generating an image; you'll usually wait a while (depending on the chosen model and duration). The page shows generation progress; once it reaches the done state you can play it.

**Q: Why can't I select a longer duration?**
Duration is adjusted in the **Setting** popover, and the slider's range is determined by the **selected model**—if you can't reach a longer duration, the current model usually doesn't support it; try another model. Duration selection itself is no longer limited by membership tier; some models derive duration from the input material (shown as "Based on input") and can't be adjusted manually.

**Q: Can I generate a video from an image?**
Yes—choose a model labeled "requires input image," then attach the image via the Assets panel or the "+" menu in the input box. See [Image to Video](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-video-image-to-video.md).

**Q: Am I charged credits if generation fails?**
A failed generation refunds that attempt's credits; no final charge is applied until generation completes.

**Q: Can I add music/voiceover to the video?**
Some models support generating with audio (rely on what the interface shows). Which models support it and whether there's an extra charge depend on the interface and real-time pricing.

## Next Steps

- [Image to Video](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-video-image-to-video.md): upload/pick an image and bring it to life
- [Product Overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-video-overview.md)
