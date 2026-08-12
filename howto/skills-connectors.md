# Skills — Connecting Connectors

> For Buddy Agent internal use.
> type: howto | feature: skills | keywords: Connectors, connection, OAuth, Google, Slack, Salesforce, external services
> User loop: Skills home → click Connectors → browse available services → authorize connection → run a Skill that needs the service → Skill automatically reads data from the connected service

## Why Connect Connectors

- **Give Skills access to your real data**: Once Gmail is connected, a Skill can read your emails; once Google Sheets is connected, a Skill can analyze your spreadsheets
- **Connect once, share across all Skills**: Connect Gmail one time, and every Skill that needs email can use it
- **Secure authorization**: Authorize via the standard OAuth protocol — a Skill can only access the scope you allow, and you can revoke it at any time

## Prerequisites

- Login required
- Entry point: the **"Connectors"** button at the top of the `/skills` page (shows the number of connected services)

## Steps

### 1. Open the Connectors panel

Click the **"Connectors"** button at the top of the Skills home page. The Connectors installation panel pops up.

At the top of the panel there's a **"Search connectors..."** search box, which lets you quickly find a service by name.

![Top of the Connectors panel: flat card grid with search box](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34215/2675e1d5.png)

### 2. Browse available services

The panel is divided into three sections:

**Main grid (no category headers, flat card list)**:

| Service | Description |
|------|------|
| Google Suite | Aggregated entry point for Google services |
| Gmail, Calendar, Drive, Google Contacts | Individual Google services |
| Notion | Notes and knowledge base |
| Microsoft 365 | Aggregated entry point for Microsoft services |
| Outlook Email, Outlook Calendar, Microsoft Teams, OneDrive, SharePoint | Individual Microsoft services |
| Slack | Team communication |
| Salesforce, Pipedrive, Affinity CRM | CRM services |
| GitHub | Code hosting |
| Box | File storage |
| Mailchimp | Email marketing |
| X (Twitter) | Social data |
| Jira, Confluence | Project management |
| LinkedIn Lite (Beta) | Social data (requires manually entering a 3-legged OAuth token) |

![Google suite and individual service cards](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34215/0513db31.png)

![Microsoft/CRM laid out flat, no category headers](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34215/5b8679a0.png)

**Data Sources section**: Supabase Database, Dropbox

**MCP Connectors section**: Reddit, Deep Wiki, Chart Server, Hacker News, Asana, plus the **"Add new MCP server"** and **"Create E2B Sandbox with MCP"** entry points

**MCP Connectors from community section**: community-contributed MCP services (in GitHub repo form), with support for category filtering

![Grouping structure: Data Sources / MCP Connectors](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34215/ad72f666.png)

### 3. Connect a service

Click the button next to the service you want to connect (the main grid shows **"Install"**, and the Data Sources section shows **"Connect"**).

**Most services use OAuth authorization**:
1. The browser redirects to the service's login/authorization page (such as the Google account selection page)

![OAuth authorization redirect](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34215/a1c37a68.png)

2. Select an account and authorize Genspark to access it

![OAuth authorization page (Google)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34215/57eb97b5.png)

3. After authorization succeeds, you're automatically returned to the Skills page
4. The service status changes to **"Connected"**

**A few services require entering credentials manually**:
- LinkedIn Lite (Beta): follow the on-page instructions to obtain access credentials from the LinkedIn developer platform, then paste them into the input field (a higher setup bar, suited to users with a technical background)

![LinkedIn Lite custom MCP credential form](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34215/4b668854.png)

- Others: a credential input field pops up — enter your API Key or Access Token, then click Connect

### 4. Use the connected service

Once connected, whenever you run any Skill that needs the service, the Skill automatically reads data from the connected service.

For example: after connecting Gmail, run the "Email Summary" Skill → the Skill automatically reads your inbox → it generates a summary report.

### 5. Disconnect (optional)

In the Connectors panel, each connected service has an **"Uninstall"** or **"Disconnect"** button next to it. After disconnecting, the Skill can no longer access that service's data.

## Notes

- Some Skills declare `required-connectors` in their SKILL.md; before running, they will block and prompt you to connect the corresponding service first
- Authorization stays valid long-term, and the system maintains the connection automatically. You only need to re-authorize if you actively disconnect, or if the authorization expires after a long period of inactivity
- Team admins can control which Connectors are visible to members via ACL (member-level visibility control, not per-Skill restrictions)

---

## Screenshot checklist

| # | Screenshot ID | Capture location | Content that must be visible in the screenshot | Purpose |
|---|---------|---------|-------------------|------|
| 1 | `connectors-panel` | Connectors installation panel | Main grid cards, Data Sources/MCP Connectors sections, search box | Show the full panel |
| 2 | `connectors-oauth` | Google OAuth authorization page | Account selection, permission description | Show the OAuth authorization flow |
| 3 | `connectors-connected` | Connected state | "Connected" label, Uninstall button | Show the successful connection state |
| 4 | `connectors-count` | Top of the Skills home page | "Connectors N" button | Show the entry point and connected count |
