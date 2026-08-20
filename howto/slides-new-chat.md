# AI Slides — Memory Management and New Chat

> For Buddy Agent internal use.
> type: howto | feature: ai-slides | keywords: Memory, New Chat, context, clearing, saving credits, switching Tier
> User loop: Continuous editing → Memory indicator turns yellow/red → Understand the meaning → New Chat clears context → Tier can be switched → Continue editing

## Prerequisites

- You've had multiple rounds of conversation in an AI Slides project
- The Memory indicator is visible in the editor

## Memory Indicator

The editing interface displays the Agent's **Memory usage indicator**, which uses a **cost badge** to tell you roughly how many credits each request currently costs:

| Badge users see | Color | Meaning |
|-------------|------|------|
| **Cheap** | Green | The context is still fresh; each request consumes the least |
| **Pricier** | Yellow | The context is about to fill up; each request starts consuming more credits |
| **Expensive** | Red | The context is near its limit; each request is expensive — New Chat recommended |

When the badge turns yellow or red, the indicator **automatically pops up** a reminder bubble that stays for a moment before retracting.

## Why You Need New Chat

Continuing to chat after Memory is full causes two problems:

1. **Wasted Credits** — Each time the Agent processes a request, it sends the entire conversation context to the model. The longer the context, the more credits consumed. After New Chat clears the context, the same editing request consumes fewer credits.
2. **Quality Decline** — When the context gets too long, the Agent will "forget" earlier conversation details, causing editing results to drift from your expectations. After New Chat, the Agent restores its precise response capability.
3. **Unlock Tier Switching** — The Tier (Ultra/Standard) is locked during a conversation and can't be switched mid-way. After New Chat, the Tier selector is re-unlocked, so you can switch to a different tier.

**In short: New Chat = save money + more accurate + switchable tier**.

## When You Need New Chat

- The Memory indicator shows **yellow or red**
- The Agent starts to "forget" previous editing requests
- You want to start a brand-new editing direction from scratch
- You want to save credits (long conversations consume more credits than short ones)
- You want to switch Tier (Ultra ↔ Standard)

## Steps

### 1. Watch the Memory Status

Keep an eye on the Memory indicator in the editing interface. When it shows yellow/red, the context is about to fill up.

### 2. Click New Chat

Find and click the **"+ New chat"** link **inside the Memory indicator's hover bubble**. A confirmation dialog appears explaining that New Chat will clear the current conversation context.

![Memory indicator hover bubble with New chat button](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36129/25ad084a.png)

![New Chat confirmation dialog](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36129/d4d343b0.png)

### 3. Confirm and Continue

After confirming, you enter a brand-new conversation state.

### 4. (Optional) Switch Tier

After New Chat, the Tier selector is re-unlocked. If needed, you can switch between Ultra or Standard before sending the first message. Once a message is sent, the Tier locks again.

![Tier unlocked + Slides retained after New Chat](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/36129/155e90d8.png)

## What Happens After New Chat

### What Gets Cleared (user-perceived)

| Content | Description |
|------|------|
| Conversation history | All previous messages are cleared; the Agent doesn't remember what you said before |
| Design decisions from the conversation | Context like "the color scheme we discussed earlier" or "the structure you suggested last round" is all lost |
| Tier lock | Released — you can re-select Ultra or Standard |

### What Gets Retained (reassuring)

| Content | Description |
|------|------|
| Generated Slides | All pages, content, and layout are fully retained; not a single page is lost |
| Project files | Files like `.slides` and `.skills` are all retained |
| Save Point version history | All historical versions are retained; you can still roll back |
| Project settings | Aspect ratio, mode (Pro/Creative), and Guide Mode settings are retained |
| Skill configuration | Installed Skills are retained |

### Impact on the Agent

- The Agent loses all conversation memory, but can still **read the files in the project** (including the generated Slides)
- The Agent will re-understand the project state by reading existing files, but won't know your previous editing intent and preferences
- **Recommendation**: For the first message after New Chat, briefly tell the Agent what you want to do next (e.g., "continue refining the data chart on page 3") to help it get up to speed quickly

![Continue editing an existing Deck after New Chat](https://gensparkpublicblob.blob.core.windows.net/user-upload-image/v1/pr_upload/34002/3588e8b6.png)

## Notes

- New Chat only clears the conversation context; it **won't delete generated Slides**
- After New Chat, the Agent can still see the current Slides content; it just doesn't remember the previous conversation
- When the Tier upgrades from Standard to Ultra, the Memory indicator will also automatically pop up a reminder

## FAQ

**Will New Chat delete the Slides I've made?**
No. New Chat only clears the conversation history; all generated pages, version history, and project files are fully retained.

**Do I have to New Chat immediately when the badge turns red?**
Not mandatory, but recommended soon. The redder the badge, the more credits each request consumes, and the more likely the editing results drift from expectations. The best time to clear is right after finishing the current round of editing.

**After New Chat, will the Agent still remember my previous design preferences?**
It won't remember preferences from the conversation (like "the color scheme we discussed earlier"). It can re-read the existing Slides content, but won't know your previous intent. We recommend briefly explaining what you want to do next in your first message.

**Why can't I switch Tier mid-conversation?**
The Tier is locked within a conversation to ensure the entire conversation uses the same tier. To switch tiers, first do a New Chat and switch before sending the first message.

## Next Steps

- To manage multiple sets of Slides within the same project → see "AI Slides — Multi-file Management"
- To import existing PPTX/PDF and continue editing → see "AI Slides — Importing Existing Files"
