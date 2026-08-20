# AI Pods — Language & Creation Options

> For Buddy Agent internal use.
> type: howto | feature: ai-pods | keywords: language, multilingual, host, single host, two hosts, speaker, style, duration, regenerate cover, cover image, edit podcast
> User loop: specify language/hosts/style/duration in the generation request → get pods that match your preferences → regenerate the cover when needed
> Help Center：https://www.genspark.ai/helpcenter/ai-pods

## Why use creation options

- **Customize every preference in one sentence**: language, how many hosts, what style, how long — write it all into your request, no item-by-item clicking.
- **Make it for different audiences**: generate Chinese/English and other language versions of the same topic, or switch styles to make a tutorial version or a casual chat version.
- **Don't like the cover? Swap it**: after generating, you can regenerate just the cover image without redoing the whole episode.

## Prerequisites

- Set when creating a podcast in AI Pods (entry point: see [Create AI Pods](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-pods-create.md))
- These preferences are written into the prompt in **natural language** — they're not separate dropdown controls
- Regenerating a cover consumes one image-generation credit; language/hosts/style are billed as part of the generation itself

## Steps

### 1. Specify the language in your request

Just say which language to use right in the prompt, e.g. "Make an episode in Chinese…" or "Make it in Japanese." AI Pods supports generation in multiple languages (default is English).

> The supported languages follow what the interface / actual generation shows.

### 2. Specify the number of hosts

The default is a **two-host dialogue**. For single-host narration, state "single host" in your request.

- **Single host**: one host narrates directly
- **Two hosts (default)**: two hosts have a natural conversation

> Note: If you request more than 2 hosts, the AI usually generates the script first and then synthesizes the audio in segments — a more complex flow. For typical use, single or two hosts is recommended.

### 3. Specify the style

Describe the style you want in your request, such as conversational, educational, entertaining, or professional.

### 4. Specify the duration

State the approximate length in your request (e.g. "about 5 minutes"), and the AI will control the script length accordingly.

### 5. Regenerate the cover image

After generation completes, if you don't like the cover you can **regenerate the cover image** (everything else stays the same). **There's no dedicated "regenerate cover" button** — send a **follow-up request** in the input box at the bottom of the result page (placeholder "Enter your pods request here"), such as "Regenerate the cover image with a different design," and the AI will regenerate and replace the cover.
![Send a "Regenerate the cover image" follow-up request in the bottom input box to regenerate the cover](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36052/04d9babc.png)

### 6. What if you want to change other content

Aside from the cover, AI Pods **currently doesn't support in-place editing of the script/audio**. To change content (a new angle, added points, restructuring), **generate a new episode with an updated prompt**.

> Published or past podcasts may have a "Continue in AI Pods" entry point that pulls it back into the agent to keep adjusting through conversation — but this still means regenerating with a new conversation, not in-place editing.

## FAQ

**How do I make a Chinese podcast?**
Just say "Make a podcast about… in Chinese" in your request. Multiple languages are supported (follow what the interface shows).

**Can I request more than three hosts?**
Two hosts is the default, single host is available. Requesting more than 2 makes the flow more complex (usually scripting first, then synthesizing in segments). For typical cases, single or two hosts is recommended.

**Can I directly edit a specific sentence in the script after generating?**
No, in-place edits aren't possible. Aside from regenerating the cover, make any other changes by regenerating a new episode with an updated prompt.

**Does regenerating the cover cost credits?**
Yes — it's an image generation. Preferences like language/hosts/style aren't charged extra; they're counted as part of the generation itself.

## Next steps

- Haven't generated one yet? Start with [Create AI Pods](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-pods-create.md)
- Happy with it? Publish / share / export → [Publish & Export](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-pods-publish-and-export.md)
