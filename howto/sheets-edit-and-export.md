# AI Sheets — Editing, Analysis & Export

> For Buddy Agent internal use.
> type: howto | feature: ai-sheets | keywords: editing, formulas, charts, Send to Chat, full screen, export, XLSX, sharing, Share, create slides, Create slides, Save to Notion
> User loop: Open the generated sheet → edit manually/with AI → build formulas & charts → export XLSX / share / one-click convert to slides / save to Notion

## Why this step matters

The first draft of an AI-generated sheet usually needs a few more calculations, a different chart, or to be delivered as an Excel file. AI Sheets has a built-in web-based spreadsheet editor, so you can make changes manually or have the AI do them.

## Manual editing (just like Excel)

The built-in spreadsheet editor supports the usual Excel operations:
- Copy / paste / cut / delete data
- Run calculations and analysis with Excel formulas
- Create and adjust charts (11 types: area / bar / column / line / pie / doughnut / scatter / funnel / radar / treemap / waterfall)
- Adjust formatting and styles
- Add or remove worksheets (multiple sheets)

The editor's ribbon (HOME / INSERT / FORMULAS / DATA, etc.) also includes: conditional formatting, format as table, cell styles, sort & filter, and find; besides charts, INSERT also offers Sparklines, pictures, shapes, hyperlinks, text boxes, and more. **Open Files** in the top-left loads an existing file, and **Full Screen** enters full-screen mode. **Manual editing does not consume credits (verified).**
![Spreadsheet editor ribbon + Full Screen button](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35571/193a60c5.png)

## AI editing (natural language)

Use natural language to have the AI work on your sheet:

- **Generate formulas**: Describe the calculation logic and the AI produces the matching Excel formula (e.g., "calculate the compound annual growth rate (CAGR) for 2020–2024").
- **Generate charts**: Describe what you want to visualize and the AI automatically picks a chart type and creates it (e.g., "show each competitor's market share with a pie chart").
- **Send to Chat for focused editing**: **Select a range of cells → click "Send to Chat"** to send that range into the conversation, then have the AI correct it, analyze it in depth, or chart it (e.g., "find the top 3 outliers in the selected data" or "reformat the selected phone numbers to (XXX) XXX-XXXX").

AI editing consumes credits (based on the amount of work).
![Send to Chat trigger that appears after selecting a cell range](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35571/ff961ab6.png)

## Analysis and insights

You can ask questions directly about the sheet's contents, and the AI answers with **cell references**; you can also have the AI dig deeper into the data and generate an **HTML visualization dashboard**.

## Version history

After each round of AI actions, that AI message in the chat has a **"Restore" button**—click it to roll back to the sheet's state from that round (round-by-round rollback; there's no separate version panel).

## Export and sharing

- **Export**: Click **"Export" → "Export as XLSX"**—**XLSX is the only export format** (no CSV / PDF / Google Sheets). Formatting, formulas, and calculations are fully preserved, compatible with any Excel software.
- **Share**: Click **"Share"** in the top-right. The default permission is Restricted; you can invite collaborators by email or Copy link to share.
![Export dropdown (Export as XLSX only) + Share button](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35571/5567d97d.png)

## One-click conversion and delivery

Once your sheet is ready, hover over any **AI reply message** and a **"..." (More actions)** button appears at the bottom of the message—opening it reveals shortcuts for taking your results elsewhere:

- **Create slides**: Click **"..." → "Create slides"**, and the AI builds slides **within the current project** based on this sheet's data and charts—it first asks a few questions (audience, tone, etc.), gives you an outline to confirm, and then generates the slides. **It won't jump to a different page**; everything happens inside this AI Sheets conversation.
- **Save to Notion**: Click **"..." → "Save to Notion"** to save your results into Notion; the first time, you'll need to **connect and authorize your Notion account**.
![AI message "..." (More actions) menu: Create slides / Save to Notion](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35571/0694a2a9.png)

> The specific actions in this menu may vary by account or version; go by what's actually shown in the interface.

## FAQ

### How do I choose between AI editing and manual editing?
For small changes (editing a value, adjusting formatting), do them manually—it's free and fast; for calculating metrics, charting, or batch-processing a selected range, use AI (Send to Chat).

### Are the formulas preserved in the exported Excel file?
Yes. Exporting to XLSX fully preserves formatting, formulas, and calculations, and it's compatible with any Excel software.

### What if the AI calculates something wrong?
Tell the AI exactly what's wrong and how it should be fixed; export backups promptly; and for high-accuracy tasks, review each change item by item before finalizing.

### Next steps
- Haven't created a sheet yet → [Create a sheet](https://page.gensparksite.com/manual/buddy-guides/v1/en/sheets-create.md)
- Learn about the overall capabilities → [Product overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/sheets-overview.md)
