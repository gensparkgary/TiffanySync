# Genspark Code — Deploy & Export

> For Buddy Agent internal use.
> type: howto | feature: ai-developer | keywords: deploy, deploy, go live, publish, publish, export, export, download, download, GitHub, share, Cloudflare, Hosted Deploy
> User loop: Happy with the app → one-click publish / download code / connect GitHub → walk away with a shareable result

## Why this step matters

A finished app should actually get used — deploying lets others reach it via a URL, exporting gives you the full code so you can self-host or keep building, and connecting GitHub brings the app into your own version control. This step turns "previewable" into "deliverable."

## 1. Deploy/publish to the web

Workspaces from web-type starting points (Simple Website or Web App, Full-Stack Websites or App) ship with a one-click publish entry — the unified **Publish** tab. It's a single publishing hub with three persistent channels — **Genspark Hosting** (one-click hosted deploy, no API key needed from you), **Quick Share** (free public link), and **Your own Cloudflare** (deploy to your own account with your Cloudflare API token) — plus domains, access control and analytics under the same tab's Site management area.

Pick any channel and follow the prompts to get a working URL.
![Workspace unified Publish tab](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/51135/f49c5c27.png)

The publish action itself doesn't cost extra; the earlier conversation turns that generated/built the app consume credits based on usage.

> The Full-Stack starting point's card description notes it's optimized for Cloudflare Pages deployment; Native App Development (Flutter) follows a preview + export-code model.

## 2. Download/export code

When you want the full code to keep or keep building on, go to the workspace **File Explorer** tab and click **Download files** to export the entire project (zip). Downloading doesn't consume credits.
![Download files entry point in File Explorer](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35762/c22764c9.png)

## 3. Connect GitHub

The GitHub integration lives at the **starting point when you create a project**, not as a workspace tab after publishing. To have the AI work on your GitHub repo (read the repo, change code, open PRs, collaborate as a team), choose the **Existing GitHub Project** starting point when creating a project and connect your GitHub — see [Connect existing code](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-developer-existing-code.md) for details.
![Existing GitHub Project starting point under the Existing code category](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35762/34ea3b2f.png)

> The **Git** tab in the workspace is Genspark's internal version control (SB-Git, a commit history where each round of AI edits auto-records a commit) — it's not your GitHub repo. Connecting GitHub doesn't consume credits.

## FAQ

**Where does it deploy? Do I need my own server?**
No. In the Publish tab, **Genspark Hosting** (one-click hosted deploy, no API key needed) and **Quick Share** (free public link) both give you a working URL without needing your own server or credentials. Only **Your own Cloudflare** (deploying to / binding your own Cloudflare account) requires a Cloudflare API token.

**Can every app be published in one click?**
Workspaces from web-type starting points (Simple Website or Web App, Full-Stack Websites or App) come with the unified Publish tab's one-click publish entry; mobile apps (Native App Development) follow a preview/export model.

**Does publishing cost anything?**
The publish action itself doesn't cost extra; the earlier process of generating and modifying code consumes credits based on usage.

**Can I download the code?**
Yes. In the workspace File Explorer tab, click Download files to export the entire project (zip). Downloading doesn't consume credits.

**How do I connect my own GitHub?**
Connect your GitHub when creating a project via the "Existing GitHub Project" starting point (see [Connect existing code](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-developer-existing-code.md)). The Git tab in the workspace is internal version control, not your GitHub.

## Next steps

- [Connect existing code](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-developer-existing-code.md) — the reverse: have the AI work on an existing GitHub repo/server
- Still tweaking the app? See [Preview & edit](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-developer-preview-and-edit.md)
- Want the big picture? See [Product overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/ai-developer-overview.md)
