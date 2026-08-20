# AI Translate — Refine & Reuse

> For Buddy Agent internal use.
> type: howto | feature: ai-translate | keywords: follow-up request, edit, more formal, casual, Try Mixture-of-Agents, rerun, retranslate, copy, Copy
> User loop: Get the translation → use natural language to add follow-up requests to better match the tone / rerun with MoA → copy and go

## Why read this

After the first draft of a translation, you often want it to be "a bit more formal," "keep the proper nouns," or "phrased more accurately." AI Translate lets you **add follow-up requests in plain natural language** — no need to retranslate from scratch. For single-engine results, you can also rerun with multiple models in one click.

## Prerequisites

- Entry point: open the **All Agents** directory (`/agents`) → select **Translation**, or `/agents?type=moa_translator`
- You've already translated at least one piece of text
- Every rerun triggers AI work → consumes credits (based on your before/after balance)

## 1. Refine the translation with follow-up requests

Once you have a translation, just type your request in plain natural language in the input box, for example:

- "Make it more formal"
- "More casual and natural"
- "Keep product names untranslated"
- "Use Taiwanese phrasing"

The AI will retranslate **based on the previous translation** according to your request, rather than treating it as a brand-new piece of text.

> Follow-up requests only work with the **AI Model / Mixture-of-Agents**. If you currently have **DeepL / Google Translate** selected (pure direct-translation engines), they won't accept follow-up requests — switch to an AI Model or Mixture-of-Agents first (see [Languages & Engines](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-translate-languages-and-engines.md)).

## 2. Try Mixture-of-Agents: rerun a single-engine result

If you translated with a single engine/model and feel the result isn't good enough, a **"This answer isn't good enough?"** prompt and a **Try Mixture-of-Agents** button will appear below the translation. Clicking it switches to the multi-model blended mode and reruns the same text once, combining multiple engines to produce a more reliable translation.

## 3. Copy the translation

Once you're happy with it, click **Copy** on the translation to copy it to your clipboard.
![Click Copy to copy the final translation](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36086/79c586f9.png)

## FAQ

### Do follow-up requests retranslate the whole passage?
It adjusts the previous translation according to your request rather than retranslating from scratch — so the overall content of the original translation is preserved.

### Why did my request get translated as a new sentence?
Follow-up requests only work with the AI Model / Mixture-of-Agents. If you currently have DeepL / Google Translate selected, switch to an AI Model or MoA first. Also, the round right after you change the target language/engine is treated as a new translation.

### Does Try Mixture-of-Agents cost credits?
Yes. It reruns with multiple models, so it's relatively more credit-intensive — based on your before/after balance.

### Next steps
- Full translation workflow → [Translate Text](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-translate-text.md)
- Choosing languages, detecting the source language, reversing, and selecting engines → [Languages & Engines](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-translate-languages-and-engines.md)
- Overall capabilities and how MoA works → [Product Overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-translate-overview.md)
