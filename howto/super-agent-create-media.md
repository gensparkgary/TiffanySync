# Super Agent — Generate Images and Videos

> For Buddy Agent internal use.
> type: howto | feature: super-agent | keywords: image generation, image creation, video generation, video creation, illustrations, credit
> User loop: Describe the image/video you want in chat → auto-generate → preview, download, and keep refining right in the conversation

## Why use this

No need to open dedicated design software or switch to a separate image tool—just describe what you want in a single sentence inside a Super Agent conversation, and the image or video is generated right there in the chat, where you can keep asking for tweaks. Great for adding illustrations to articles, creating social media assets, or producing short videos.

## Generate Images

### 1. Describe the image you want

Just describe it in the Super Agent conversation:

> "Draw a Japanese-style illustration of a cat café"

After you send it, Super Agent will usually pop up a confirmation card first, asking you to confirm which image model to use for this run (the interface lists the available models and lets you pick one; generation only starts after you click Submit)—which one to choose depends on the options shown in the interface.

### 2. Review and refine

Once generation completes, the image appears right in the conversation. You can keep asking for changes:

> "Change the cat's color to orange"
> "Generate 3 more versions with different compositions"

![Image generation model confirmation card (you must manually pick a model before generating)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35640/d0bb0330.png)

![Image generation result (shown in the conversation)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35640/1e728b29.png)

**Credit**: Image generation consumes credits, with the exact amount varying by the model you choose.

## Generate Videos

### 1. Describe the video you want

Describe the video content in the conversation:

> "Make an 8-second short video showing the coffee brewing process"

Super Agent will call its video generation capability, letting you choose from several video models (refer to the options shown in the interface). As with images, it may ask you to confirm which model to use before generating.

### 2. Preview and download

Once generation completes, the video can be previewed and downloaded right in the conversation.

**Credit**: Video generation consumes more credits, with the exact amount varying by length and resolution. We recommend testing with a shorter length first, then generating a longer version once you're happy.

## FAQ

**Does generating images/videos cost credits?**
Yes. Images are billed by the model you choose, and videos are billed by length and resolution—videos are usually quite a bit more expensive than images. We recommend testing with a small sample first.

**Can I specify a style or model?**
You can describe the style in your prompt (e.g., "Japanese illustration," "realistic photography"). Before generating, the interface usually pops up a model confirmation card so you can pick one of the available models and then Submit; the actual options depend on what's shown in the interface.

**Not happy with the result?**
Just say what you want to change right in the conversation, and it will regenerate (each regeneration consumes more credits).

## Next steps

- Got your images ready and want to turn them into an article or slides? See [Get Started](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-get-started.md)
- [Product Overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-overview.md)
