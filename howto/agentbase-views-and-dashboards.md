# Dashboards & CRM — Views & Dashboards

> For Buddy Agent internal use.
> type: howto | feature: agentbase | keywords: views, board, Kanban, Gallery, Calendar, Form, Table, dashboard, interactive views, queries, charts, Filter, Sort, Group, Search, toolbar, export, Export, CSV, Excel
> User loop: In your workspace → have AI turn your data into the right view/board/dashboard → view, interact, and query data however you need

## Why use it

- **One dataset, many perspectives**: The same customer table can work as a spreadsheet, a sales board, a calendar, or a gallery—switch the way you look at it based on what you're doing right now, without re-entering any data.
- **Ask your data questions without writing a single query**: Want to know "how many deals closed this month" or "which items have stock below 10"? Just ask AI and it pulls the answer and shows it to you.
- **Interactive dashboards at a glance**: AI can build dashboards with charts and clickable filters that put your key numbers right in front of you.

## Prerequisites

- You need to be signed in and already have a workspace with data (first [create a system](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-create-a-system.md) or [import data](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-import-data.md))
- Views and dashboards are generated through conversation and consume credits based on that turn's usage; viewing and interacting with them afterward is free

## Steps

### 1. Five built-in views

Every table in your system can be presented in the 5 ways below. **There are two ways to switch views**: click a view button in the toolbar above the table (**Table / Kanban / Gallery / Calendar / Form**, switches instantly with one click), or tell AI in chat which one you want and let it recommend.

| View | What it looks like | Good for |
|------|---------|------|
| **Table** | Classic spreadsheet, one row per record | Seeing all fields, bulk browsing and editing |
| **Kanban** | Card board split into columns by status | Tracking processes (sales stages, hiring stages, task status) |
| **Gallery** | A wall of large image cards | Content with images (products, assets, candidate photos) |
| **Calendar** | Records placed on a calendar by date | Anything with a time attribute (content schedules, interview schedules, order dates) |
| **Form** | A single entry form | Letting others or yourself quickly add a new record |

Not sure which to use → start with **Table** for the full picture, switch to **Kanban** to track a process, switch to **Calendar** when you have dates.

Here's what the five views actually look like:

![Table view: classic spreadsheet, one row per record](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36683/d25fd99a.png)

![Kanban view: card board split into columns by status](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36683/99b34056.png)

![Gallery view: a wall of large image cards](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36683/a72b6a46.png)

![Calendar view: records placed on a calendar by date](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36683/0887d887.png)

![Form view: a single entry form for quickly adding records](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36683/44c189a9.png)

#### The built-in Filter / Sort / Group / Search toolbar

In **Table** view, there's also a row of tools above the table—**Filter** / **Sort** / **Group** / **Search**—that lets you organize and locate data directly, with no conversation and no credits: show only matching records, sort by a column, group by a field like status, or search for a keyword.

#### One-click table export (Export)

As the workspace owner, you can also **download a table's data directly**: open the **Export** menu in the table toolbar and pick **CSV / JSON / XLSX**. The export follows the current state of your view — the filters, sorts, and visible columns you've set — so what you see is what you get. Exporting doesn't call AI and is **free**.

### 2. Switch or create views

The fastest way is to click a view button in the toolbar to switch. When you need a more complex view, ask AI for help—e.g. "turn the deals table into a board split by stage" or "add a calendar view to the content table"—and it'll configure the details like the grouping field and date field for you.

### 3. Ask your data questions without writing a query

To understand what's in your data, just ask AI in plain language—it pulls the answer and gives you the result, with no need to know any query syntax.

For example:
- "How many deals closed this month?"
- "List the products with stock below 10"
- "By owner, count how many in-progress projects each person has"

![Ask your data in plain language (e.g. "how many leads in each status"), and AI pulls the answer](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36683/907a5975.png)

### 4. Interactive views and dashboards (Apps)

Beyond the basic views, AI can build **interactive views**—pages with charts and clickable filters that pull key information from multiple tables into a single dashboard. For example, a sales dashboard with this month's revenue, deal counts per stage, a monthly trend chart, and clickable controls to switch the time range.

![Interactive dashboard "Leads Overview": KPI cards + status bar chart + trend line chart, with LIVE real-time data](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36683/b05dfa91.png)

Finished dashboards and views are filed under the **Dashboards** section on the left, ready to open anytime. Viewing and interacting with them doesn't re-invoke AI, so it's **free**.

A finished dashboard can also be **shared read-only on its own** — including via a link that can be viewed without signing in. See [Share & Collaborate](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-share-and-collaborate.md).

## FAQ

**What's the difference between a view and a dashboard?**
A view is a way of looking at one table (table/board/calendar…); a dashboard pulls key information and charts from multiple tables into a single page, usually with interactivity. AI builds both for you.

**Will switching views change my original data?**
No. A view is just a different way of presenting the data—switching or deleting a view never affects the underlying data itself.

**Do I spend credits every time I query data?**
Having AI look something up on the fly (one conversation turn) is billed based on that turn's usage; but opening a view or dashboard you've already built and interacting with it is free.

**Can I download the data in a table?**
Yes. The workspace owner can download the current table as CSV / JSON / XLSX from the **Export** menu in the table toolbar. The export follows the current filters, sorts, and visible columns, and costs no credits.

**Can I make a dashboard auto-refresh with the latest data?**
When you open a dashboard, it shows the current data; to have the underlying data update automatically on a schedule, set up a workflow—see [Automate Workflows](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-automate-workflows.md).

## Next steps

- Keep data and reports updating automatically on a schedule → [Automate Workflows](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-automate-workflows.md)
- Share your workspace with colleagues to view together → [Share & Collaborate](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-share-and-collaborate.md)
- Don't have data yet? Start by [importing data](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-import-data.md)
