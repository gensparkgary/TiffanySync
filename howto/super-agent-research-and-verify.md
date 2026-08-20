# Super Agent — Deep Research & Fact Check

> For Buddy Agent internal use.
> type: howto | feature: super-agent | keywords: Deep Research, Fact Check, research, verification, report
> User loop: Has a research need → picks Deep Research or Fact Check → writes a good brief / submits content → gets a structured report or verification verdict

## Why use these two paths

Regular chat is great for quick Q&A, but **report-level research** requires gathering large amounts of material and cross-verifying it, while **fact-checking** requires comparing claims against sources one by one. Genspark turns these two tasks into dedicated capabilities: Deep Research helps you research a topic thoroughly and organize it into a report, and Fact Check helps you verify, sentence by sentence, whether the facts in a piece of content are correct.

## Deep Research

**Best for**: in-depth, report-level research on topics that involve gathering large amounts of material and cross-verification.

### 1. Enter Deep Research

The simplest way is to **describe your deep research need directly in a Super Agent conversation**, and it will automatically enable the deep research capability. You can also open **Deep Research** on its own from the **All Agents** list in the left sidebar.

![Deep Research landing page](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35640/958151a8.png)

### 2. Write a research brief

Don't just drop a single question. Write a short outline that tells the AI what to research and which aspects to cover:

> "I'm researching market entry strategies for the Southeast Asian SaaS market. Please research: (1) SaaS adoption rates and growth in the top 5 markets; (2) local payment methods and pricing strategies; (3) case studies of Chinese SaaS companies that have already entered; (4) the main risks and barriers. Produce a structured research report."

The more specific you are, the higher the research quality.

### 3. Wait for the research to finish

Deep Research searches a large number of web pages, analyzes data, and cross-verifies information. Along the way you can watch real-time search and analysis progress (Parallel Search / Parallel Read), and it ultimately produces a structured report with numbered sources. The time it takes depends on the complexity of the topic: simple queries usually take a few minutes, while complex, report-level topics take longer.

![Deep Research real-time progress (Parallel Search / Read)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35640/794ad3b4.png)

### 4. Turn the research into other formats

Once the research is done, you can simply ask Super Agent to convert the results into a deliverable format:

> "Turn this research into a PPT" (automatically calls AI Slides)
> "Organize the key data into a table" (automatically calls AI Sheets)

## Fact Check

**Best for**: verifying the accuracy of factual statements in documents, articles, and reports.

The simplest way is to **just say "help me verify the accuracy of this content" directly in a Super Agent conversation**, and it will enter the fact-checking flow. You can also open the fact-check entry point on its own from the **All Agents** list in the left sidebar (the corresponding item in the UI is named **Fact Check**).

### 2. Submit the content to check

Paste the text directly or upload a file, and specify what to focus on:

> "Check all the data citations and statistics in this article, flag anything inaccurate, and provide the correct sources."

### 3. Review the check results

The AI first identifies each factual statement in the text, then for each one gives: Statement → Analysis → Evidence → a conclusion marked **✅ Support / ❌ Against** to indicate whether it holds → with a source link (Cite as). For statements found to be unsupported, it points out what's wrong and provides the correct data.

![Fact Check per-statement verdicts + source links](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35640/73934187.png)

## How to choose between Deep Research and Fact Check

| You want to... | Use |
|---------|----|
| Research a topic thoroughly from scratch and produce a report | Deep Research |
| Verify whether the facts in an existing piece of content are correct | Fact Check |

> Not sure? Start with Deep Research to produce a report, then use Fact Check to verify the key data in that report.

## FAQ

**How do I get it to do deep research?**
Two ways: ① describe your research need in a Super Agent conversation, and it automatically enables deep research (the most direct way); ② open Deep Research from the All Agents list in the left sidebar.

**How long does the research take?**
It depends on the complexity of the topic: simple queries take a few minutes, while complex, report-level topics take longer. You can watch the progress in real time.

**How do I read the check results?**
For each fact, it gives analysis and evidence, marks whether it holds with ✅ Support / ❌ Against, and attaches source links; for statements that don't hold, it points out the correct data.

## Next steps

- Want to turn your research straight into a finished deliverable? See "Specifying the output format" in [Getting Started](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-get-started.md)
- Want to save your research conclusions? See "Save files to AI Drive" in [Real-world actions](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-actions.md)
- [Product overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/super-agent-overview.md)
