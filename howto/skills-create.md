# Skills — Creating a Skill

> For Buddy Agent internal use.
> type: howto | feature: skills | keywords: Create, Create, Upload, Upload, New Skill, skill-creator
> User loop: + New Skill → choose a creation method → AI-guided or upload a file → save → see it in My Own Skills → run to verify

## Why Create Your Own Skill

- **Package repetitive work**: For the reports, analyses, and content you generate often, build a Skill once and finish it in one click every time after
- **Consistent output quality**: A Skill locks in the instructions and tool configuration, so quality won't fluctuate based on a different prompt each time
- **Team sharing**: Useful Skills can be published to your team, so everyone uses the same standardized workflow
- **Build up assets**: As you create more Skills, your AI workspace grows ever more powerful

## Prerequisites

- You must be signed in
- Entry point: the **"+ New Skill"** button in the top-right corner of the `/skills` page

![+ New Skill button (top-right corner)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34213/35bd74a8.png)

## Three Ways to Create

![Dropdown with three options: Create for myself / Upload / Create for Team](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34213/d0dc33e9.png)

### Option 1: Create for myself (AI-guided creation)

Ideal for starting from scratch — no technical background required.

#### 1. Click "+ New Skill" → "Create for myself"

The system launches the skill-creator Agent and opens a chat interface.

#### 2. Describe your needs

The Agent will guide you through:
- **Skill name and description**: what your Skill does
- **Trigger word**: a quick command (e.g., `@weekly-report generate`)
- **Inputs and outputs**: what input it needs and what files it produces
- **Tool permissions**: whether it needs tools like search, web scraping, etc.

Just answer the Agent's questions step by step — no need to write code or configuration files.

![skill-creator Agent chat interface](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34213/4069d534.png)

#### 3. Test and save

Once the Agent finishes creating the Skill, you can run a test right away. When you're happy with it, save it and the Skill will appear in the **My Own Skills** tab.

### Option 2: Upload (import a file)

Ideal when you already have a Skill file or a Skill package obtained from elsewhere.

#### 1. Click "+ New Skill" → "Upload"

The **"Import skill package"** dialog appears.

![Import skill package upload dialog](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34213/4d315b81.png)

#### 2. Choose a file

Drag and drop or select a file. Supported formats: `.zip`, `.skill`, `.md` (a `.zip` must contain a skill.md with name + description), up to 200MB.

#### 3. Confirm and save

The dialog shows "We'll unpack it and install it into My Skills" — click **"Save skill"** to confirm. The Skill appears in the **My Own Skills** tab and is ready to use right away.

### Option 3: Create for Team (team creation)

Shown in the dropdown as **"Create for Team"** (with a "Team Plan" badge). Requires a Team Plan. The creation flow is the same as "Create for myself," but the Skill is submitted to your team admin for review, and once approved it appears in the **Team Skills** tab.

Users without a Team Plan who click this option will open the Team Plan upgrade page (`/team_pricing`) in a **new tab**.

![Team Plan upgrade page](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34213/6b1478ac.png)

## After Creating

- The Skill is saved in the **My Own Skills** tab

![My Own Skills tab](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34213/a757614f.png)

- You can select and run it from the SkillBar on the home page
- You can share it with others via the Share feature
- You can edit or delete it in Manage Skills

---

## Screenshot List

| # | Screenshot ID | Capture location | Must be visible in the screenshot | Purpose |
|---|---------|---------|-------------------|------|
| 1 | `create-dropdown` | + New Skill dropdown expanded | The three options "Create for myself" (subtitle: Private to your account) / "Create for Team" (Team Plan badge) / "Upload" | Show the creation entry points |
| 2 | `create-agent-chat` | skill-creator Agent chat | Agent's guiding questions, user's answers, creation progress | Show the AI-guided creation process |
| 3 | `create-upload-modal` | Upload dialog | File selection area, supported format notes | Show the upload interface |
| 4 | `create-my-own-result` | My Own Skills tab | The newly created Skill card appearing in the list | Confirm successful creation |
