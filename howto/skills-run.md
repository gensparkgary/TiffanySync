# Skills — Running a Skill and Viewing Results

> For Buddy Agent internal use.
> type: howto | feature: skills | keywords: run, Run, SkillBar, execute, Sandbox, deliverable files, results, slash
> User loop: Home SkillBar → select Skill → enter prompt → execute → view steps → get deliverable files → preview/download

## Why understand the run details

- **Not a black box**: While a Skill runs you can see what each step is doing (searching, writing code, reading files), helping you judge the quality of the results
- **Deliverable files**: Many Skills generate files (reports, data tables, charts), and you need to know where to find and download them
- **Permission confirmation**: Some operations require you to confirm permissions (such as accessing external services), and you need to know how to respond

## Prerequisites

- At least one installed Skill
- If the Skill needs Connectors (such as reading Gmail), connect the corresponding service first

## Steps

### 1. Select a Skill

In the SkillBar area on the Skills home page, there are two ways to select:

**Option A: Click to select**
Click **"Select a skill first"** (or the displayed Skill name) to open a dropdown list, then choose from your installed Skills.

![SkillBar dropdown showing the list of installed Skills](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34212/7b922394.png)

**Option B: Slash command**
Type `/` in the input box to open the Skill search panel, then type a keyword to search and select.

![Slash command opening the Skill search panel](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34212/a9ea0ff3.png)

After selecting, the SkillBar shows the name of the chosen Skill. You can select multiple Skills at once (shown as "N in use").

![Multiple Skills selected showing "2 skills in use"](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34212/edd7bfad.png)

### 2. Enter a Prompt

Describe your specific request in the input box. You can attach files (click the attachment icon or drag and drop).

Example: "Analyze the sales data in the attachment and generate a weekly report with trend charts."

![Input box, attachment button, and send button](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34212/93732441.png)

### 3. Execute

Click send. The Skill runs in the SuperAgent Sandbox, and the page switches to the execution view.

### 4. Watch the execution process

During execution you can see:

| UI element | Description |
|---------|------|
| Execution steps | Each operation (search, read file, write code, etc.) is shown as a collapsible card |
| Thinking | The Agent's reasoning process (expandable) |
| Streaming output | Real-time text replies |
| Permission request | If special permissions are needed (accessing external services, etc.), a confirmation dialog pops up |

![Execution step cards and streaming output](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34212/127ee77f.png)

![Plain text result output (no deliverable files)](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34212/e0df8e7f.png)

### 5. View deliverable files

After the Skill finishes running, deliverable files appear in the **Output files** drawer behind the folder icon in the top-right corner:
- Click the folder icon in the top-right corner to open the files drawer
- Click a file to **preview** it (supports text, code, images, PDF, etc.)
- Click the download icon to **download** it locally
- Files can also be found in the Task List

![Output files deliverables drawer](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34212/1d2b990c.png)

**Tidying deliverables (rename/delete)**: The task owner can **rename** or **delete** delivered files from the file row's menu in the files pane — handy when long-running tasks pile up similarly named artifacts. Some multi-file outputs (such as slide/document renders) can't be renamed or deleted.

### 6. Task List (history)

All Skill run records are saved in the Task List (click the hamburger menu icon in the top-left corner to open it from the left drawer). You can:
- View past run records
- Search past conversations (Search Chats)
- Review deliverable files again
- Download historical files

![Task List history drawer](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34212/71851f70.png)

## Notes

- Running a Skill consumes credits; complex tasks consume more
- Deliverable files are permanently stored in the cloud, so you can come back to download them anytime
- If execution is interrupted or fails, you can run it again

---

## Screenshot checklist

| # | Screenshot ID | Capture location | Content that must be visible in the screenshot | Purpose |
|---|---------|---------|-------------------|------|
| 1 | `run-skillbar-select` | SkillBar dropdown selection | List of installed Skills, selected state | Show how to select a Skill |
| 2 | `run-slash-popover` | Panel that appears after typing `/` | Skill search list | Show the Slash command selection method |
| 3 | `run-executing` | Skill running | Execution step cards, Thinking area, streaming output | Show the execution process |
| 4 | `run-deliverables` | Output files drawer | File list, preview/download buttons, folder icon entry point in top-right corner | Show how to get result files |
| 5 | `run-file-menu` | Output files file row menu | Rename/Delete actions | Show deliverable tidying |
| 6 | `run-task-list` | Task List drawer | List of historical run records, Search Chats | Show how to find history |
