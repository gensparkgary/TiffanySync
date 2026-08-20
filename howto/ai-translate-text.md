# AI Translate — Translate Text

> For Buddy Agent internal use.
> type: howto | feature: ai-translate | keywords: Translation, AI Translate, Translation, Text, Mixture-of-Agents, target language, copy
> User loop: Open AI Translate → pick target language → enter text → send → get translation → copy

## Why start here

Paste some text, pick the language to translate into, and in seconds you'll get a translation that's cross-checked across multiple translation engines and refined by AI to pick the best result — more accurate and natural than any single translation tool.

## Prerequisites

- Entry point: open the **All Agents** directory (`/agents`) → select **Translation**, or go directly to `/agents?type=moa_translator`
- Translation consumes credits (check your balance before and after to confirm)

## 1. Open AI Translate

In the **All Agents** directory, click the **Translation** card to enter (lands on `/agents?type=moa_translator`), or open that address directly. The landing page has an input box in the middle, with the language bar (source language / target language) and the engine/model selector **below the input box**.
![AI Translate landing page: input box + language bar below + engine selector](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36086/d7827621.png)

## 2. Pick the target language

Click the **target language** selector below the input box and choose the language to translate into. The list covers dozens of languages and distinguishes regional variants (e.g. English (US) / English (UK), Portuguese (Brazil) / (Portugal), Chinese (Simplified) / (Traditional)).

> You don't need to pick the source language manually — AI **auto-detects** the language you enter. See [Languages and engines](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-translate-languages-and-engines.md) for details.

![Target language selector: includes regional variants like US/UK, Simplified/Traditional](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36086/c6726882.png)

## 3. Pick an engine (Mixture-of-Agents recommended)

The engine/model selector below the input box defaults to a single engine/AI model (as shown in the UI). For results cross-checked across multiple engines and refined by AI to pick the best, **manually select Mixture-of-Agents** — this is AI Translate's core selling point. If you only want the raw result from a specific engine (like DeepL), select that one.

> See [Languages and engines](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-translate-languages-and-engines.md) for the full guide to engine selection.

## 4. Enter text and send

Paste or type the text you want to translate into the input box, then click send.

## 5. View the translation

Once translation completes:

- **Mixture-of-Agents mode**: gives the final synthesized translation, plus an expandable panel showing **each engine's individual translation** for comparison, along with a **Reflection** explaining how the AI weighed and combined them.
- **Single-engine mode**: shows that engine's translation directly.

![Mixture-of-Agents translation: synthesized result + per-model comparison + Reflection](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36086/17825088.png)

## 6. Copy the translation

Click the **Copy** button on the translation to copy it to your clipboard and paste it anywhere.
![Click Copy to copy the translation, with a Copied confirmation](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36086/79c586f9.png)

## FAQ

### Do I need to manually pick which language the input is?
No. The AI auto-detects the source language. See [Languages and engines](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-translate-languages-and-engines.md) for details.

### What if I'm not happy with the translation?
You can follow up in natural language to ask for changes ("make it more formal"), or click "Try Mixture-of-Agents" on a single-engine result to rerun it with multiple models. See [Refine and reuse](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-translate-refine-and-reuse.md).

### Can I translate a whole document?
Currently only text translation is supported; uploading documents/files isn't supported yet.

### Does translation cost credits?
Translating with Mixture-of-Agents or an AI model consumes credits (in testing, one run deducts a small amount — confirm by comparing your balance before and after). Plain direct translation with DeepL / Google Translate may not cost credits (in testing a single-engine run showed no balance change) — the actual balance change is what counts.

### Does it auto-generate a title after translating? Can I share it?
Yes. After translating, the system automatically generates a title for the session and shows it in the top bar, with a **Share** button next to it for sharing.

### Next steps
- Pick languages, see the detected source language, reverse translation, pick engines → [Languages and engines](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-translate-languages-and-engines.md)
- Make translations match the tone, rerun, copy → [Refine and reuse](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-translate-refine-and-reuse.md)
- Not sure about the overall capabilities → [Product overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-translate-overview.md)
