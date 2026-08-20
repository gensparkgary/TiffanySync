# AI Translate — Choosing Languages and Engines

> For Buddy Agent internal use.
> type: howto | feature: ai-translate | keywords: target language, source language, detection, Auto detect, Swap, swap, engine, Mixture-of-Agents, DeepL, Google Translate, model
> User loop: set the target language → see the detected source language → flip it with one click (swap arrow) → choose MoA or a single engine

## Why read this

The two settings that control your translation: **what language to translate into** and **which engine to use**. Get these right and the output fits your needs better.

## Prerequisites

- Entry point: open the **All Agents** directory (`/agents`) → pick **Translation**, or `/agents?type=moa_translator`

## 1. Pick the target language

Click the **target language** selector below the input box and choose the language you want to translate into. It covers dozens of languages and distinguishes regional variants:

- **English (US) / English (UK)**
- **Portuguese (Brazil) / Portuguese (Portugal)**
- **Chinese (Simplified) / Chinese (Traditional)**

![Target language selector: dozens of languages including regional variants](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36086/c6726882.png)

> The exact languages available follow what the selector shows.

## 2. Source language auto-detection

You **don't need to pick the source language manually** — the AI detects it automatically from the text you enter and shows the detected language in the language bar. When you haven't entered anything yet or it can't be identified, it shows **"Auto detect"**.

## 3. One-click reverse translation (swap arrow)

Once a translation is done and the source language is detected, click the **swap arrow (→)** in the middle of the language bar to swap the source and target languages — handy for instantly translating back. (It's an arrow icon, with no "Swap" text.)
![Click the swap arrow to swap source/target languages and translate back](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36086/d7f53ff2.png)

> If the detected language can't be used as a target language (a few languages), the detected language isn't shown and you can't swap — that's normal.

## 4. Pick the engine / model

The engine/model selector below the input box determines what does the translating. **The default is a single engine/AI model (follow what the UI shows); if you want a multi-model best-of synthesis, manually pick Mixture-of-Agents**:

| Choice | What it does | Best for |
|------|------|------|
| **Mixture-of-Agents** (recommended, pick manually) | Runs multiple engines at once, then AI synthesizes the best result | When you want the most reliable translation |
| **DeepL** | Direct translation using the DeepL engine alone | When you want DeepL's raw result |
| **Google Translate** | Direct translation using the Google engine alone | When you want Google's raw result |
| **AI model** (follow what the UI shows) | Translation using a single AI model | When you want a particular model's style |

![Engine selector: Mixture-of-Agents or a single engine/model](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36086/bfb37070.png)

> The exact AI models available follow what the UI shows (visible options may differ by account/organization). **Only AI models and Mixture-of-Agents support "follow-up requests" to revise the translation** (see [Refine and Reuse](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-translate-refine-and-reuse.md)); DeepL / Google Translate only do direct translation and don't accept follow-up requests.
> Credits: translating with Mixture-of-Agents / AI models consumes credits; plain direct translation with DeepL / Google Translate may not be billed (in testing, the balance didn't change after a single-engine run) — follow the actual balance change.

## FAQ

### Why does the detected source language sometimes not show?
A few detected languages can't be used as a target language; in that case the detected language isn't shown and you can't swap. Just change the input or the target language.

### Mixture-of-Agents and a single engine give different results?
That's normal. MoA is an AI synthesis of multiple engine results, while a single engine is that engine's raw direct translation. To compare, expand the MoA result to see each engine's individual translation.

### After picking DeepL, can I ask it to be "more formal"?
No. DeepL / Google Translate only do direct translation and don't accept follow-up requests. To add requirements, use an AI model or Mixture-of-Agents.

### Next steps
- The full translation workflow → [Translate text](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-translate-text.md)
- Add follow-up requests to revise the translation, rerun, and copy → [Refine and Reuse](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-translate-refine-and-reuse.md)
