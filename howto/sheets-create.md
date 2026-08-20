# AI Sheets — Creating Spreadsheets

> For Buddy Agent internal use.
> type: howto | feature: ai-sheets | keywords: create, generate spreadsheet, find data, financial statements, stock prices, upload files, MCP, Supabase, data analysis
> User loop: Enter AI Sheets → Describe your needs/select mode → AI finds data and generates → Get a spreadsheet with data and formulas

## Why Start Here

Describe what you want to analyze, and AI automatically finds the data, builds the table, computes formulas, and creates charts—no need to enter data row by row yourself.

## Prerequisites

- Entry point: the **AI Sheets** tile under the Office Suite category on the homepage, or go directly to `/agents?type=sheets_agent_new`
- Generation consumes credits (in practice, roughly a few hundred credits per run—check your balance before and after to confirm)

## 1. Enter AI Sheets

Click the **AI Sheets** tile under Office Suite on the homepage (landing on `/agents?type=sheets_agent_new`), or click the "+" (New) in the sidebar and select AI Sheets. The landing page shows: the welcome message "Unleash the Power of AI Sheets" + an input box + three capability descriptions (automatically find data / transform existing data / freely analyze and visualize); **the spreadsheet editor is already loaded when you enter the page** (it doesn't appear only after generation).
![AI Sheets landing page: input box + three capability descriptions + spreadsheet editor already loaded on the right](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35571/0e4d9151.png)

## 2. Describe the Analysis You Want

Describe your needs in natural language in the input box. Examples:
- "Compile NVIDIA's financial statements from FY2021 to FY2025" (have AI search the web for financial reports and build a table)
- "Analyze sales trends from the uploaded Excel and visualize by region" (analyze based on an uploaded file)

AI automatically decides what to do—clean data, write formulas, run code for statistical analysis, create charts—and the process is transparent and visible. 

## 3. Give AI Data

| Method | How to do it |
|------|--------|
| **AI automatically searches the web** | Simply state what data you want in your request, and AI pulls it from sources like financial reports (SEC), stock prices, academic sources, products, and web pages |
| **Upload files** | Upload Excel / PDF / Word / images in the chat, and AI automatically extracts and analyzes them |
| **Paste a Google Sheets link** | Paste the Google Sheets URL directly into the chat box as text (there is no dedicated import-link button) (the sheet must have link sharing enabled, i.e. Share → Anyone with the link); AI imports the whole workbook including all tabs   |
| **Reference your past projects** | Just say it in the chat, e.g. "based on my last sales analysis sheet"—AI can list and read your own past Genspark projects (sheets/docs/slides, including meeting notes)   |
| **Connect data sources via Connectors** | Click **"Connectors"** in the chat box → connect to Google Drive, **Supabase (run SQL queries)**, custom MCP (Add new MCP server to connect enterprise databases), as well as Notion / Microsoft 365 / Dropbox and more (refer to the interface), then use natural language to have AI query directly |

![Connectors popup, Data Sources section: Supabase + Add new MCP server](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35571/35818dd0.png)

## 4. Select a Mode (Optional)

The mode selector in the input box: **Standard** (default, balances speed and quality) / **Ultra** (more powerful and in-depth, for complex analysis). The exact tier descriptions are as shown in the interface.  
![AI Sheets tier selector: Standard (default) / Ultra](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51190/63e540a8.png)

## 5. Send and Wait for Generation

After you click send, AI starts working (find data → build table → compute formulas → create charts). When complete, the spreadsheet appears in the editing area on the right, where you can continue editing; the chat area also provides a **Key Insights summary with cell references** (indicating data ranges and sources), and charts are automatically placed to the right of the table.
![Generation complete: NVIDIA financial statement table + trend chart + Key Insights in the chat area](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35571/bdc6023a.png)

> For complex tasks, we recommend breaking them into steps: first have AI complete "find data + clean," confirm the results, then have it "analyze in depth"—this avoids a single misstep affecting the final result.

## 6. Continue Refining

After generation, you can manually edit, modify with AI, create charts, and export—see [Editing and Exporting](https://page.gensparksite.com/manual/buddy-guides/v1/en/sheets-edit-and-export.md) for details.

## FAQ

### I don't have any data—can AI find it for me?
Yes. This is the core of AI Sheets—describe the data you want, and it automatically pulls from sources like financial reports, stock prices, academic sources, and web pages to fill in the table, with key data also cross-verified across multiple sources.

### Can I connect to my company's database?
Yes. Connect to Supabase (run SQL) or custom MCP (enterprise databases) via **Connectors**, then use natural language to have AI query and analyze.

### My task is very complex and AI can't get it right in one go—what should I do?
Break it into multiple steps: confirm the results at each step before having AI continue; when the conversation gets too long, start a new AI Sheets project (to avoid performance degradation from an overly long context).

### Next Steps
- Editing/formulas/charts/exporting → [Editing and Exporting](https://page.gensparksite.com/manual/buddy-guides/v1/en/sheets-edit-and-export.md)
- Learn about the overall capabilities → [Product Overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/sheets-overview.md)
