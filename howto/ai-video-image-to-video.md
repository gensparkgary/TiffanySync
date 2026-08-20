# AI Video — Image to Video

> For Buddy Agent internal use.
> type: howto | feature: ai-video | keywords: image to video, image to video, make an image move, upload image, reference image, animate, turn a still into video, models that require image input
> User loop: Open AI Video → pick a model that "requires image input" → attach a starting image via the Assets panel or the input box "+" → (optional) describe the motion → generate → get a video that brings that image to life

## Why use Image to Video

You already have an image you like (a photo, product shot, illustration, or poster) and want it to move — Image to Video uses that image as the starting frame to generate a video, saving you from describing the whole scene from scratch.

## Prerequisites

- Entry: the **AI Video** card in the Content Creation section of the **All Agents** page (`/agents`), or **AI Video** in the sidebar **New** hover popover, which opens `/agents?type=video_generation_agent` (the home page's first-row icon strip no longer shows AI Video directly)
- Login required; generating a video consumes credits (amount varies by model/duration/resolution — go by what the UI and your membership tier show)

## 1. Pick a model that "requires image input"

Image to Video isn't a button on the parameter bar — at its core, it means **picking a model that supports image input**. Open the model selector and choose a model the UI marks as supporting/requiring image input: image-to-video-only models are labeled "This model only supports image-to-video generation" or "requires N input images"; models that take both text and images are labeled **"Supports up to N input images"**. **Which models support it and how they're labeled is whatever the UI shows.**

> ⚠️ **Attaching an image won't filter models for you**: after you attach an image, the model selector **won't** automatically keep only the models that support image-to-video, nor will it gray out the others — you need to **actively pick** a model marked as requiring image input.

> Want to know which models are good for image-to-video and what each is best for → see [current-models.md](https://page.gensparksite.com/manual/buddy-guides/v1/en/current-models.md), and go by what the UI actually shows.

## 2. Attach a starting image

There are two paths to attach an image (there's no entry called "Image to Video"):

- **Assets panel on the right**: open the **Assets** drawer and click **+ Upload** to upload an image/media.
- **The "+" menu next to the input box**: click the **"+"** next to the input box → **Browse Local Files** (a local image) or **Choose from AI Drive** (pick from your drive).

Once attached, the input box/conversation area carries this image as the starting frame.

![Model selector: for Image to Video, actively pick a model that requires image input here (the first item is Auto-select; the default is a specific model). Attaching an image won't auto-filter this list](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36031/234cb108.png)

## 3. Describe the motion (optional but recommended)

In the input box, write how you want the image to **move** — camera push/pull, subject action, wind, lighting changes, and so on. Even for image-to-video, describing the motion clearly noticeably improves the result. Examples:

- "Slow zoom in, gentle camera push toward the subject"
- "The character turns and smiles, hair moving in the wind"

You can also turn on **Auto Prompt** to let AI automatically expand the motion description.

## 4. Adjust ratio and duration (optional)

Same as text-to-video: ratio, resolution, **duration**, With Audio, and Fast Mode are all adjusted in the **Setting** popover on the parameter bar (options vary by the selected model; when you upload an image, the ratio often auto-matches the image). Duration is a **slider + a seconds input** (the selectable range varies by model; some models derive duration from the input material) and is **open to every plan** — picking a longer duration won't trigger an upgrade prompt.

## 5. Generate, play, download

After submitting, you enter the generation chat panel, where AI generates a video based on this image. **Generation consumes credits; you're only charged on success, with refunds on failure.** Note: **for free/expired accounts using default/premium models, the upgrade wall may pop up mid-generation**, no video is produced, and membership is required. Once done, you can play and download it directly, or just say something to have it produce another version.

![The finished video plays in the Assets panel on the right, where you can preview, download, or just say something in the conversation to have it produce another version](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36031/a07c27fc.png)

## FAQ

**Q: How is this different from text-to-video?**
Text-to-video generates from a pure text description; image-to-video uses an image as the starting frame and brings it to life — better suited for "I already have an image I like and want to animate it." Both live on the same AI Video landing page; the only difference is **the model you pick** (for image-to-video, choose a model that requires image input) and **whether you attach an image**.

**Q: I attached an image — why didn't the model list change?**
That's normal — attaching an image **won't** auto-filter the model list or gray out unsupported models. Image-to-video relies on you **actively picking** a model marked as "requires image input" (the UI labels it).

**Q: Where do I attach the image? There's no "Image to Video" button?**
There's no control called "Image to Video." Attach an image via **+ Upload** in the **Assets** panel on the right, or via the **"+"** next to the input box → Browse Local Files / Choose from AI Drive.

**Q: Do I need to write a text description?**
Image-to-video works without an extra description, but clearly writing "how it should move" (camera, action) usually gives better results; you can also turn on Auto Prompt to expand it automatically.

**Q: Can I use multiple images?**
Some models support multiple input images (labeled "Supports up to N input images" — go by what the UI shows). How multiple images are used is decided by the model based on how many you attach — typically 1 image is the starting frame, 2 are first/last frames, and more act as reference images (rules vary slightly by model; go by the UI description). In most cases a single starting image is enough.

## Next steps

- [Generate a video](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-video-create.md): generate a video from a text description (including model / Setting parameters / duration / Auto Prompt details)
- [Product overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-video-overview.md)
