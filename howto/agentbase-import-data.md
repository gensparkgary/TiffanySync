# Dashboards & CRM — Import Data

> For Buddy Agent internal use.
> type: howto | feature: agentbase | keywords: import, data import, file upload, connector, HubSpot, Salesforce, Dropbox, Box, Microsoft 365, Snowflake, email, database, connector
> User loop: In a workspace → have AI pull data from files/email/apps/databases → data lands in tables, ready to query and build views on

## Why use it

- **No manual entry**: Spreadsheet files on hand, info in your inbox, contacts in HubSpot/Salesforce, records in your own database — AI can pull them all in directly, no more copying things row by row.
- **Multiple sources in one place**: Consolidate data scattered across different apps and files into one system for unified management and viewing.
- **AI aligns the structure for you**: Imported data is automatically organized into the right tables, so you don't have to worry about how fields map.

## Prerequisites

- You need to be signed in and already have a workspace (if not, [create a system](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-create-a-system.md) first)
- Entry point: chat directly in your workspace and tell the AI where you want to import from
- Imports are driven by chat and consume credits based on usage for that turn

## Steps

Imports all happen through **chat** — you tell the AI where the data is, and it pulls it in and organizes it into tables. The instructions below are grouped by source type.

### 1. Upload files

The most direct approach: hand your existing spreadsheets or documents to the AI. Common spreadsheet and document files are supported (Excel, CSV, PDF, Word), and you can also upload an entire folder; other file types like archives (e.g. zip) can be uploaded directly too — the AI unpacks and processes their contents itself.

![File source menu: Browse Local Files / Choose from AI Drive](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36683/32e6f32c.png)

The getting-started cards on the home page also have a "Start from files" entry that guides you through uploading a file and building a system from it.

### 2. Import from email and Microsoft 365 / Google

You can have the AI pull data from accounts you've authorized, for example:

- Info in your **email** (Gmail / Outlook)
- **Microsoft 365**: SharePoint, OneDrive, Teams, plus Outlook calendar and contacts

Just say in the chat what you want to import and from which account, and the AI will fetch it using your authorization. The first time you use a given account, it'll walk you through authorizing it once.

### 3. Connect apps (HubSpot, Salesforce, Dropbox, Box, etc (connected through the chat conversation via OAuth; the UI has no static app list).)

You can bring in data from business apps. Common ones include **HubSpot** and **Salesforce**; cloud storage services **Dropbox** and **Box** can also be attached as data sources — both to keep an inventory of their files and to import data files from them into tables. The exact list of supported apps is whatever the UI shows.

- **HubSpot**: Generate an **access token** in HubSpot, then **paste** it in following the prompts in the chat to connect.
- **Salesforce** and other personal connectors: Follow the UI prompts to connect your account.

![Connect HubSpot: AI guides you to generate and paste a Private App Access Token (PAT)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36683/d00585e5.png)

### 4. Connect your own database

If your data lives in your own database, you can connect to it directly too. Common databases are supported (PostgreSQL, MySQL, Snowflake, etc.); the exact list is whatever the UI shows. Just describe in the chat the database you want to connect and provide the connection info when prompted.

### 5. Where imported data lands

Imported data is organized by the AI into **tables** in your system, just like tables you build by hand — you can query it, build views on it, and set up automatic updates.

- For moderate amounts of data, the AI **pulls the whole set in**, and you can freely add, edit, and delete.
- When a dataset is **very large**, the AI won't cram all of it in. Instead, it builds an **aggregated view** (pulling in only the summary results you need) to keep the system from slowing down. The AI will let you know when this happens.

Once the import is done, you can [build views and dashboards](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-views-and-dashboards.md), or [set up scheduled syncs](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-automate-workflows.md) to keep the data up to date.

## FAQ

**I'm not sure my data is "in the right format" — can I just upload it?**
Yes. Just hand the file to the AI or have it connect to your app, and it'll organize the data into the right tables for you — no need to adjust the format first.

**Does connecting HubSpot require one-click admin authorization?**
No. The current approach uses a **pasted access token** — you generate an access token in HubSpot and paste it in following the prompts in the chat. It doesn't rely on one-click authorization.

**Will the data keep updating automatically after import?**
By default it's a one-time import. To have it sync automatically on a schedule and stay up to date, set up a workflow — see [Automate Workflows](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-automate-workflows.md).

**My dataset is huge — will it all get pulled in and slow the system down?**
No. For large datasets, the AI switches to an aggregated view, pulling only the summary you need rather than moving everything over.

**Which apps and databases are supported exactly?**
Whatever the UI shows — common business apps (HubSpot, Salesforce, etc.), cloud storage (Dropbox, Box), and databases (PostgreSQL, MySQL, Snowflake, etc.) are all in scope, and the UI lists the current options.

**Can a program I wrote push data into my workspace?**
Yes. As the workspace owner, you can create **API credentials** inside the workspace and use them to write data into this workspace's tables from your own program or script; credentials only work on workspaces you own and can be revoked at any time.

## Next steps

- Turn imported data into boards, calendars, and dashboards → [Views and Dashboards](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-views-and-dashboards.md)
- Have data sync automatically on a schedule and stay current → [Automate Workflows](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-automate-workflows.md)
- Share it with teammates → [Share and Collaborate](https://page.gensparksite.com/manual/buddy-guides/v1/en/agentbase-share-and-collaborate.md)
