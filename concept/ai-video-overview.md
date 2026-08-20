# AI Video — Product Overview

> For Buddy Agent internal use.
> type: concept | feature: ai-video | keywords: AI Video, generate video, text to video, image to video, video generation, text to video, image to video, make an image move, short video
> Entry: **AI Video** on the **All Agents** page (`/agents`) / in the sidebar **New** popover, or `/agents?type=video_generation_agent` (the home page's first-row icon strip no longer shows AI Video directly)

## Why use AI Video

Want a video — a product demo, a social clip, an animated cover, or turning a still image into moving footage? Normally that means knowing how to shoot, edit, or animate. AI Video turns all of that into one sentence: describe the scene you want, or upload an image to bring it to life, wait a moment, and you get a video you can use right away. Not happy with it? Just say another line and it generates a new version.

Core value: **Go from a single sentence, or a single image, to a ready-to-use video — without needing to know how to shoot or edit.**

## What it can do

- **Text to Video**: Describe the scene and action you want in natural language to generate a video directly
- **Image to Video**: Pick a model that "requires an input image," attach a starting image, and bring it to life (attach the image via the Assets panel or the "+" menu in the input box — there is no control named Image to Video)
- **Multiple models to choose from**: Several built-in video generation models you can switch manually; the **first item** in the model selector is Auto-select (let the system pick for you), but it **defaults to a specific model** (not Auto) — the actual UI takes precedence
- **Adjust output parameters**: Frame size/resolution, aspect ratio, **duration**, generation count, With Audio, and Fast Mode are all set in the **Setting** popover on the parameter bar (duration is a slider + seconds input whose range varies by model; some models derive duration from the input material. Which options are adjustable varies by the selected model)
- **Keep refining**: Not satisfied with the result? Just say another line and let the AI produce a new version

## How it differs from Genspark Design video

There are two places in the platform where you can make "video," for different purposes:

| | **AI Video** (this product) | **Genspark Design — Video** |
|---|---|---|
| What it is | A standalone video generation Agent that calls real video generation models | Motion/animation design inside the design tool Canvas |
| Typical output | Realistic video clips, turning images into moving footage, short clips | Logo motion, UI animation, multi-shot timeline animation |
| Entry | `/agents?type=video_generation_agent` | `/agents?type=design` (pick Video) |
| Pick this when… | You want to get a video from a single sentence or a single image | You want a design-driven animation, motion graphic, or an MP4-exportable design piece |

> Quick rule of thumb: want to "generate a video" → AI Video; want to "make a moving design/animation" → Genspark Design.

## About Credits

- **Generating video costs credits** — each generation calls a real video generation model, billed by the **model, duration, resolution, and whether audio is included** you select; different combinations vary widely.
- **Duration is open to every plan**: Duration is adjusted in the **Setting** popover (slider + seconds input) and is no longer unlocked by membership tier — picking a longer duration won't trigger an upgrade prompt; the selectable range is determined by the chosen model. Longer durations generally cost more credits.
- **Whether free accounts can produce a video follows the UI prompts**: **the model selected by default is a high-quality (premium) one** — for free/expired accounts, the upgrade prompt may still appear at the **video generation step** after submission and no video is produced; the prompt may also pop up while generation is in progress. Whether it works follows what the UI shows.
- **Failed generations are not charged** the credits for that attempt; no final charge is counted until generation finishes.
- Pricing, membership tiers, and benefit comparisons are governed by the **live pricing page** ([genspark.ai pricing page](https://www.genspark.ai)).

## Quick guides by scenario

| What you want to do | See this |
|---------|-------|
| Generate a video from a text description | [Create a video](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-video-create.md) |
| Upload/pick an image to bring it to life | [Image to Video](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-video-image-to-video.md) |
