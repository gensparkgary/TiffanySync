# AI Translate — Product Overview

> For Buddy Agent internal use.
> type: concept | feature: ai-translate | keywords: AI Translate, Translation, Mixture-of-Agents, MoA, DeepL, Google Translate, Multi-model, Target language
> Entry: **All Agents** directory (`/agents`) → **Translation**, or `/agents?type=moa_translator`

## Why use AI Translate

When translating a piece of text, any single translation tool tends to have its own weak spots: some nail the terminology but sound stiff, others read fluently but occasionally drift off. AI Translate's approach is to **have several top translation engines each produce their own version, then let AI synthesize the best of them** — giving you a translation that's more accurate and more natural. That's **Mixture-of-Agents (MoA)**.

Core value: **multiple translation engines cross-check each other, AI synthesizes the best result, and you get a translation more reliable than any single tool — plus you can add requirements in natural language to match your tone.**

## What you can do

- Translate text into **dozens of languages** (including regional variants like English US/UK, Portuguese Brazil/Portugal, Chinese Simplified/Traditional, etc.)
- Use **Mixture-of-Agents** to blend multiple engines (select it manually in the engine picker), or pick a single engine/AI model
- **Auto-detect** the language you type, and click the **swap arrows** to translate in reverse with one click
- After translating, **add requirements** in natural language ("more formal," "more casual," "keep proper nouns") and let AI revise
- **Copy** the translation with one click

## What is Mixture-of-Agents

When you select **Mixture-of-Agents**, AI Translate will:

1. Call multiple translation engines/AI models at once, each producing its own version
2. Have an AI model **synthesize** all the versions into a single final translation, along with a **Reflection** explaining how it made its choices

You can also expand to compare each engine's individual translation.

> The engine picker defaults to a single engine/AI model (whichever the UI shows). Not sure what to choose → **manually select Mixture-of-Agents** and let AI blend and pick the best automatically. Want the raw output of just one engine (e.g., DeepL) → select it on its own in the engine picker.

## Translation engines / models

In the engine picker you can choose **Mixture-of-Agents** (blended) or a single engine/AI model on its own (such as DeepL, Google Translate, and AI models).

| Choice | Best for |
|------|------|
| **Mixture-of-Agents** | When you want the most reliable translation and want AI to automatically blend multiple engines and pick the best |
| **Single engine / AI model** | When you want the raw output of one specific engine, or want it faster |

> The actual engines and AI models available depend on what the UI shows (visible options may differ by account/organization). **Only AI models and Mixture-of-Agents support "adding requirements" to revise translations**; pure engines (like DeepL/Google) only do direct translation.

## Credit consumption

Translating with **Mixture-of-Agents or an AI model consumes credits** (based on the actual AI workload, as reflected by your credit balance before and after). Mixture-of-Agents runs multiple models simultaneously and then aggregates them, so it uses more compute than a single engine. Plain direct translation with **DeepL / Google Translate** may not consume credits (in testing, a single engine showed no balance change for one run). The exact amount depends on the actual change in your balance.

## Quick guides by scenario

| What you want to do | See this |
|---------|-------|
| Translate a piece of text (from input to translation) | [Translate text](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-translate-text.md) |
| Choose the target language, see the source language, translate in reverse, pick an engine | [Choose languages and engines](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-translate-languages-and-engines.md) |
| Make the translation match your tone, run it again, copy it | [Refine and reuse](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-translate-refine-and-reuse.md) |

## FAQ

### What's the difference between AI Translate and a regular translation website?
Regular tools only give you one engine's result at a time; AI Translate's Mixture-of-Agents runs multiple engines at once and synthesizes the best result, and you can add requirements in natural language to make the translation match your tone.

### Can it translate a whole document / PDF / Word file?
Right now AI Translate only supports **text translation** (paste/type text into the input box). Uploading documents or files for full-document translation isn't supported yet.

### Which languages does it support?
It covers dozens of languages and distinguishes regional variants (e.g., English US/UK, Portuguese Brazil/Portugal, Chinese Simplified/Traditional). The exact languages available depend on what the target-language picker shows.

### Does translating cost credits?
Translating with Mixture-of-Agents or an AI model consumes credits, with the former using relatively more since it runs multiple models at once. Plain direct translation with DeepL / Google Translate may not consume credits (in testing, a single engine showed no balance change for one run). The exact amount depends on your balance before and after.
