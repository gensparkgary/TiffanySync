# Skills — Connectors Concept

> For Buddy Agent internal use.
> type: concept | feature: skills | keywords: Connectors, External Services, OAuth, MCP, Google, Microsoft, CRM, Collaboration

## Why You Need Connectors

- **Expand Skill capabilities**: Without Connectors, a Skill can only work with files you upload and information found through web searches. With Connectors, a Skill can directly read your emails, calendar, and CRM data.
- **Zero manual exports**: No need to export emails from Gmail and re-upload them — the Skill reads them directly.
- **Secure isolation**: Each Connector is authorized via OAuth, so the Skill can only access the scope you allow.

## What Is a Connector

A Connector is an **authorized channel** between Genspark and an external service. Once connected, every Skill can access that service's data through this channel.

```
Your Gmail account ←→ Connector (OAuth) ←→ Genspark ←→ Any Skill that needs email data
```

## Supported Services

The Connectors panel is divided into three sections (no purpose-based section titles — displayed as a flat grid of cards):

### Main Grid (23 Connectors)

| Service | Description |
|------|------|
| **Google Suite** | Aggregated entry point for Google services (Gmail, Calendar, Drive, Contacts) |
| Gmail, Calendar, Drive, Google Contacts | Individual Google service connections |
| **Microsoft 365** | Aggregated entry point for Microsoft services |
| Outlook Email, Outlook Calendar, Microsoft Teams, OneDrive, SharePoint | Individual Microsoft service connections |
| Notion | Notes and knowledge base |
| Slack | Team communication |
| Salesforce, Pipedrive, Affinity CRM | CRM services |
| GitHub | Code hosting |
| Box | File storage |
| Mailchimp | Email marketing |
| X (Twitter) | Social data |
| Jira, Confluence | Project management |
| LinkedIn Lite (Beta) | Social data (requires manually entering a 3-legged OAuth token) |

### Data Sources Section

Supabase Database, Dropbox

### MCP Connectors Section

Reddit, Deep Wiki, Chart Server, Hacker News, Asana

Supports **"Add new MCP server"** and **"Create E2B Sandbox with MCP"**.

There is also an **MCP Connectors from community** subsection, which showcases community-contributed MCP services (presented as GitHub repos) with category filtering support.

## Connection Methods

Most Connectors use the standard **OAuth** protocol — click Install → get redirected to the service's authorization page → authorize → return. No need to manually copy an API key.

A few services require manually entering credentials. For example, LinkedIn Lite (Beta) requires you to obtain a 3-legged OAuth token from the LinkedIn Dev Console and paste it (a fairly high setup barrier).

Authorization is long-lasting once granted, and the system automatically maintains the connection. You only need to re-authorize if you actively disconnect, or if the authorization expires after a long period of inactivity.

## Team Management

Team Plan admins can control which Connectors are visible to members via **Connector ACL**. The management entry is on a dedicated page at `/payment/team_connectors` (not within the Team Skills management page). This is member-level visibility control, not a per-Skill restriction.

---

## Screenshot List

| # | Screenshot ID | Capture Location | Content That Must Be Visible | Purpose |
|---|---------|---------|-------------------|------|
| 1 | `concept-connectors-panel` | Full view of the Connectors install panel | Main grid cards, Data Sources/MCP Connectors sections, search box | Show all available Connectors |
| 2 | `concept-connectors-flow` | Diagram | Connector connection flow (user → OAuth → service → Skill) | Explain how Connectors work |
