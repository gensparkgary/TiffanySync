# AI Sheets — Product Overview

> For Buddy Agent internal use.
> type: concept | feature: ai-sheets | keywords: AI Sheets, tables, spreadsheets, data analysis, Excel, XLSX, formulas, charts, finding data
> Entry point: the **AI Sheets** tile under the Office Suite category on the home page, or `/agents?type=sheets_agent_new`

## Why use AI Sheets

The most tedious part of building data tables—financial models, sales analyses, research summaries—is **finding the data + cleaning it + calculating + charting**. AI Sheets turns all of this into a conversation: describe what you want to analyze, and the AI automatically finds the data, cleans it, runs the formulas, builds the charts, and delivers conclusions.

Core value: **generate a table from a single sentence, with the AI automatically going online to find and fill in data, and native Excel compatibility**.

## What it can do

- **Generate a table from one sentence**: describe what you need, and the AI creates a table complete with data and formulas
- **Automatically find data online**: pulls data from authoritative sources and fills it into the table (financial reports, stock prices, academic papers, product info, web pages)
- **Connect your own data**: upload files (Excel/PDF/Word/images), or connect Google Drive and databases via MCP; you can also have the AI reference your past Genspark projects and meeting notes 
- **AI + manual editing**: edit by hand just like Excel, or have the AI make changes using natural language
- **Analysis and insights**: ask questions about your data, generate charts, build visual dashboards
- **Export**: export to XLSX with formatting and formulas fully preserved, compatible with any Excel software

## Generation modes

The mode selector in the input box lets you trade off between speed and depth as needed:

| Mode | Orientation |
|------|-------------|
| **Standard** | Balances speed and quality, the everyday default |
| **Ultra** | More powerful and in-depth, best for complex analysis |

> The exact tiers and their corresponding capabilities are as shown in the interface.

## AI auto-finds data (the key differentiator)

No need to enter data row by row yourself—describe what you want, and the AI pulls it from these sources and fills in the table:

| Source | Data retrieved |
|--------|----------------|
| **Financial data** | SEC company filings (10-K/10-Q), stock prices |
| **Academic data** | Papers, citations, research trends |
| **Product data** | E-commerce product info, prices, reviews |
| **Company data** | Company background, funding, and more |
| **General web** | Public web information, with key data cross-verified across multiple sources |

> For example, "Summarize NVIDIA's FY2021–FY2025 financial reports"—the AI will find the data, build the table, and calculate year-over-year changes on its own.

## Core capabilities at a glance

| Capability | Description |
|------------|-------------|
| Generate | Create a table from one sentence |
| Find data | Pull data online + upload files + connect data sources via MCP + reference your past projects  |
| Edit | Manual (like Excel) + AI (Send to Chat / natural language) |
| Formulas | Full Excel formulas, generated from natural language |
| Charts | 11 chart types |
| Analysis | Q&A (with cell references), insights, HTML visual dashboards |
| Export/Share | Export to XLSX; Share links for collaboration |
| Conversion/Delivery | One-click from the AI message "..." menu to **Create slides (inline)** or **Save to Notion** |

## Credit consumption

Generating tables and having the AI find data or run analysis all **consume credits** (calculated based on AI workload; in our tests a single generation runs around a few hundred credits). **Manual editing does not consume credits (verified)**. The search/scraping/financial-report tools used to find data online are each billed separately. The actual cost is whatever your balance shows before and after the operation.

## Limitations (currently unsupported)

AI Sheets is a web-based spreadsheet, and the following Excel features are currently unsupported:
- **Macros / VBA**: you can't run VBA inside AI Sheets (but the AI can generate VBA code for you to copy into desktop Excel and run there)
- **Native data connections**: ODBC / OLEDB / external links
- **Complex / 3D charts**, custom functions (UDFs), Power Query / Power Pivot

## Quick guide by scenario

| What you want to do | See this |
|---------------------|----------|
| Generate a table / have the AI find data | [Create a table](https://page.gensparksite.com/manual/buddy-guides/v1/en/sheets-create.md) |
| Edit / formulas / charts / export / share | [Edit and export](https://page.gensparksite.com/manual/buddy-guides/v1/en/sheets-edit-and-export.md) |

## FAQ

### What's the difference between AI Sheets and AI Docs?
AI Sheets is for **data tables and analysis** (financial models, sales analysis); AI Docs is for **text documents** (PRDs, reports). Use AI Sheets when you need to crunch numbers, build charts, or find data.

### Can I use it on my phone?
For now, AI Sheets on mobile **only supports viewing results**. For full functionality, we recommend using a computer.

### Is there a limit on data volume?
In theory it supports operations on roughly a million cells (depending on your computer's performance—the AI manipulates the table in the browser, so you need enough memory to avoid lag).

### Can it do statistical analysis (regression, hypothesis testing)?
It supports most data analysis that can be done with Excel formulas, including statistical analysis.
