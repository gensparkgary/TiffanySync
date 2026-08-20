# AI Slides — Standard / Ultra Tiers

> For Buddy Agent internal use.
> type: concept | feature: ai-slides | keywords: Ultra, Standard, Tier, Mode, Tier, Model, Switch, New Chat

## Why There Are Two Tiers

The two tiers let you make a trade-off based on what this particular deck is for — whether you need a finished piece ready to present, or just want a quick look at the direction:
- **Ultra**: For a delivery-ready, finished deck — polished layout and content, ideal for high-stakes scenarios (pitch decks, client proposals). The first time you pick Ultra, a confirmation dialog pops up to explain the higher credit cost. Uses **1.0× credits**
- **Standard**: For getting a first draft faster to check the direction — faster speed and lower credit cost, ideal for quick drafts or everyday content. Uses **0.5× credits**

| Dimension | Ultra | Standard |
|------|-------|----------|
| Quality | Highest, refined layout | Basic, faster |
| Credit Cost | 1.0× credits | 0.5× credits |
| Best For | Important presentations, high-quality needs | Quick drafts, batch generation |

> The credit multiplier (Standard 0.5× / Ultra 1.0×) is visible directly in the Mode selector.

## How to Choose a Tier

On the `/ai_slides` creation page, use the **Mode selector** (the UI panel title shows "Mode") to switch between Standard and Ultra. Ultra is selected by default (marked Recommended).

## Important Limitation: You Can't Switch After Starting a Chat

**Once you send the first message under a given tier, the chat is locked to that tier and can't be switched midway.**

Why: switching models causes inconsistent AI behavior across turns (different models understand and edit the same deck differently), which hurts generation quality.

**If you need to change tiers**: click **New Chat** → the conversation context is cleared and the Mode selector is unlocked → choose the new tier → continue editing. Your Slides content won't be lost.

![Mode selector (Standard / Ultra, Ultra by default)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36116/2a90df72.png)

## Next Steps

- [AI Slides Overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-overview.md)
- [Creative Mode Image Models](https://page.gensparksite.com/manual/buddy-guides/v1/en/slides-create-creative.md)
