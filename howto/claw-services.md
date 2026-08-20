# Genspark Claw — Connecting External Services

> For Buddy Agent internal use.
> type: howto | feature: genspark-claw | keywords: Services, services, Gmail, Outlook, GitHub, Notion, Slack, Salesforce, Remote Desktop, connect, authorize, login
> User loop: Services tab → click a service → log in via Remote Desktop → close the window → Claw auto-detects success → acts on your behalf

## Why use Services

- **Lets Claw truly "act on your behalf"**: connect your email once, and Claw can read/write emails and manage your calendar directly — no need to open the app yourself
- **Covers your whole work stack**: email, calendar, code hosting, CRM, and collaboration tools all connect in one place
- **Keeps sessions alive**: your login sessions are saved on your cloud computer, so Claw can keep using them long-term

## Prerequisites

- Entry: Claw workspace → **Services** tab
- Cloud Computer enabled (Services is a cloud computer feature)

## Supported services

The Services tab organizes services by **action-based grouping** (not by service type). The actual group names and typical services:

| Group (action-based UI heading) | Typical services |
|------|------|
| **Let Claw Handle Your Workspace** | Google (Gmail, Calendar, Contacts), Microsoft 365 (Outlook, Teams, OneDrive, SharePoint…) |
| **Run Your Social Media** | Twitter/X, Instagram, Facebook, LinkedIn |
| **Take Your Notes** | Notion |
| **Manage Your Code** | GitHub |
| **Watch Your Channels** | Slack, Salesforce, etc. |
| **More Services** (expand to view) | Zoom, Figma, Crunchbase, HubSpot, Stripe, SimilarWeb, Box, Jira |

(Follow what's shown in the UI; the service list and grouping change as the product evolves, so **expand "More Services" before concluding a service doesn't exist**.)
![Services tab: action-based grouped service list + Open Remote Desktop](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35661/5d8d4070.png)

> **Interaction varies**: some services have a toggle next to them (e.g., Google, Slack, Notion, Salesforce — one-click enable), while others show a "→" (e.g., Instagram, Facebook, LinkedIn, Figma, Stripe, Jira — click in for a redirect/manual setup). Just follow the on-screen prompts.

## Steps

### 1. Open the Services tab

Click **Services** in the right-hand control panel. At the top there's a note plus the Remote Desktop entry (with a masked cloud computer password + an **Open Remote Desktop** button).

### 2. Click the service you want to connect

Click the service (toggle-type services flip on directly; "→"-type services open up — just follow the prompts). Services that require logging into a third-party account will open a **Remote Desktop** window — this is the **browser on your cloud computer**, already navigated to that service's login page. Your cloud computer password is **automatically copied to the clipboard**.

> **Buddy guidance (read-only)**: when demoing, stop at the point where the Remote Desktop popup appears — **do not actually log into the third-party account on the user's behalf**.

### 3. Log in inside Remote Desktop

- Enter your cloud computer password to unlock Remote Desktop
- Log into the service as you normally would (enter your username and password, complete authorization as prompted)
- Your login session is saved on your cloud computer

### 4. Close the window — Claw auto-detects

Close the Remote Desktop window. Claw automatically detects whether the login succeeded, after which it can act on the service for you (read/write emails, manage calendar events, review PRs, etc.) — without you needing to open the app again.

**Session expiry**: some platforms log out inactive sessions. Once expired, just repeat the steps above to reconnect.

> **Credit note**: the setup process for connecting a service consumes credits; afterward, when Claw uses the service to get things done (e.g., reading emails, generating content), credits are consumed based on the actual workload.

## FAQ

**Q: I connected Google, but Calendar isn't working?**
The initial Google authorization may not have included the Calendar permission. Go to the Services tab, **disconnect Google**, then reconnect — and during re-authorization, **check all requested permissions** (including Calendar).

**Q: Can Claw get my password?**
Your login inside Remote Desktop happens in your private cloud browser session, which is saved on your own isolated cloud computer and is not shared between users.

**Q: Should I connect a lot of services?**
Connect as needed (principle of least privilege): only connect the services your task actually requires. A Claw used mainly for scheduling and research doesn't need access to financial accounts. See the security section in [claw-tips-and-credits](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-tips-and-credits.md) for details.

## Next steps

- [Set up scheduled tasks (let Claw use these services automatically) →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-schedules.md)
- [Use Claw inside messaging apps →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-channels.md)
- [Manage your cloud computer →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-manage.md)
