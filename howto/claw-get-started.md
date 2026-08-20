# Genspark Claw — Activation and First Use

> For Buddy Agent internal use.
> type: howto | feature: genspark-claw | keywords: activation, Start Now, Cloud Computer, cloud computer, Desktop App, download, Local Computer, workspace, first use, Open Genspark Claw
> User loop: open /claw → choose cloud computer or desktop app → activate/install → enter workspace → first conversation

## Why Read This First

- **Each path has trade-offs**: the cloud computer is online 24/7 but requires a subscription, while the desktop app is free but only runs while your computer is on—pick wrong and you'll either pay for a subscription needlessly or miss the background output you were waiting for.
- **The first-time setup order shapes the experience**: connect message channels first, then services, then scheduled tasks, so Claw can start working for you as fast as possible.

## Prerequisites

- Entry: `https://www.genspark.ai/claw` (you can also open it from the "Genspark Claw" tile in the Agents grid)
- Requires a logged-in Genspark account
- The Cloud Computer path requires a Cloud Computer subscription; the Desktop App path only needs an account + credits

## Path A: Activate Cloud Computer

**Best for**: users who need 24/7 operation, scheduled tasks, cross-platform messaging, and the full feature set.

### 1. Open Claw

Go to [genspark.ai/claw](https://www.genspark.ai/claw). Users who haven't activated will see the Claw landing page, with feature cards and a **Start Now** button.
![Claw marketing landing page (Your First AI Employee) with the Start Now button, alongside Download Desktop App · Free](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35850/ae92e1af.png)

### 2. Choose a Plan and Check Out

Click **Start Now** to open the **"Activate Genspark Claw"** pricing modal (an in-page modal, no redirect to a separate page). You can switch between **Monthly / Annually** (annual saves more), and choose from three cloud computer tiers:

| Plan | Specs (Cloud Computer) | Positioning |
|------|------|------|
| **Lite** | 2 vCPU / 4 GB / 64 GB | Entry level, good for getting started solo |
| **Standard** (**MOST POPULAR**) | 2 vCPU / 8 GB / 64 GB | Balanced performance and cost, good for everyday tasks |
| **Powerful** | 4 vCPU / 16 GB / 128 GB | High performance, good for heavy automation and intensive computation |

Each tier comes with a one-time batch of Welcome Credits on first subscription (more for higher tiers). **The exact prices, discounts, and gifted credit amounts are whatever the in-app modal shows.**

![Activate Genspark Claw pricing modal: Lite / Standard (MOST POPULAR) / Powerful tiers + Monthly/Annually toggle (prices redacted)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35850/4747d076.png)

> **Read-only note (Buddy guidance)**: activation triggers a real charge. Guide the user to confirm their plan themselves before checking out—do not purchase on the user's behalf.

### 3. Enter the Workspace

After a successful checkout, a confirmation page appears. Click **Open Genspark Claw**. The system creates your dedicated cloud computer (showing live progress, usually a few minutes), and automatically enters the Claw workspace when done.

### 4. Get to Know the Workspace

Once inside, the **chat panel is on the left** and the **control panel is on the right**, with 8 tabs:

| Tab | Purpose |
|------|------|
| **Home** | Overview + everyday configuration (Computer Information, 4 quick cards, Advanced) |
| **Tutorial** | How to Use guide |
| **Channels** | Connect messaging apps |
| **Services** | Connect external services |
| **Schedules** | Scheduled tasks |
| **Terminal** | In-browser command line |
| **Files** | File management |
| **Settings** | Cloud computer management (including Plan Management) |
![Claw workspace: chat on the left + 8-tab control panel on the right](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35661/998a9d68.png)

Under **Home → Computer Information** (click to expand), you can view/configure: Claw Email, Domain, AI Model + Image Model (each has **Switch model**; switching the conversation model does not clear history), Remote Desktop Password, and read-only VM Information / System status panels. See [claw-manage](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-manage.md) for details.

### 5. Your First Conversation

Use natural language in the left chat panel to give Claw a task, for example:
> "Search for the most important AI industry news from the past week and summarize it into 5 bullet points."

Claw will call its built-in Skills (search, scraping, etc.) to complete it.

> **Credit note**: every conversation message and tool call consumes credits (shared across the whole account).

### 6. Recommended First-Time Setup Order

1. **Connect message channels** ([claw-channels](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-channels.md)) → chat with Claw directly in Slack/WhatsApp and others
2. **Connect external services** ([claw-services](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-services.md)) → let Claw send/receive email and manage your calendar
3. **Set up scheduled tasks** ([claw-schedules](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-schedules.md)) → let Claw handle repetitive work automatically

## Path B: Install the Desktop App

**Best for**: users who want to try it out, use it occasionally, or don't want to pay for a subscription.

> ⚠️ The steps below are based on the code and Help Center, and **have not been verified live via a headless browser** (the local desktop app can't be automated).

1. **Download**: on [genspark.ai/claw](https://www.genspark.ai/claw), click **Download Desktop App** (marked **Free**), then choose **Download for Mac** (Apple Silicon, .dmg) or **Download for Windows** (.zip). Install and open it.
   ![Download Desktop App (free, Mac / Windows platforms)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/35850/c364ae17.png)
2. **Sign in**: log in with your Genspark account.
3. **Choose Local Computer**: select **Local Computer** in the left panel.
4. **Set a workspace folder** (strongly recommended): click the **folder icon** in the input bar and choose a dedicated working directory. Claw will try to keep its file operations within this directory, reducing the risk of touching other files by mistake.
   - **Note**: this is a soft guide, not a hard boundary—Claw may still access files outside the directory when a task requires it. Back up important files first.
5. **Start chatting**: just type in a task. The desktop app shares memory and Skills with the cloud computer.

## How to Choose Between Cloud Computer and Desktop App

| Need | Recommendation |
|------|------|
| Need 24/7 background operation, scheduled tasks, full features | Cloud Computer |
| Occasional use / don't want a subscription / want to try first | Desktop App |
| Want both | Enable both on the same account; memory is shared |

## FAQ

**Q: Do I pay twice to activate (subscription + credits)?**
The Cloud Computer is a fixed monthly fee (for your dedicated machine), and credits are the separately metered "fuel" the AI burns while working, shared across the whole account. An idle cloud computer doesn't consume credits. The desktop app needs no subscription—just credits.

**Q: How long does it take to create the cloud computer?**
Usually a few minutes. The interface shows live progress and automatically enters the workspace when done.

**Q: Is the desktop app safe?**
Local mode can access your file system, a broader scope than cloud access. Set a workspace folder in the input bar first to narrow the scope, and back up files before file-related tasks. See the security section in [claw-tips-and-credits](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-tips-and-credits.md).

## Next Steps

- [Connect message channels →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-channels.md)
- [Connect external services →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-services.md)
- [Set up scheduled tasks →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-schedules.md)
- [What Claw is / choosing →](https://page.gensparksite.com/manual/buddy-guides/v1/en/claw-overview.md)
