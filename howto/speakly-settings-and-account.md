# Speakly — Settings & Account

> For Buddy Agent internal use.
> type: howto | feature: speakly | keywords: Settings, Settings, Shortcuts, Language, Microphone, Quota, Usage, Upgrade, Tray, Feedback, Updates
> User loop: Open Settings → tune shortcuts/language/microphone etc. → understand usage & quota, and upgrade when needed

## Why walk through the settings

- **Use it your way**: trigger key, speaking style, interface language, microphone — all configurable. Get them right and dictation just flows.
- **Know where your quota stands**: how much of your free quota is left, when it resets, and how to upgrade — all at a glance, so you're never caught short at a critical moment.
- **A clear path when something's off**: unhappy with a transcription? Give feedback right inside the app, with context attached, so improvements land faster.

## Prerequisites

- Speakly installed and signed in (see [Get Started](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-get-started.md))
- Entry points: open the **Settings** dialog from the main window; or **Open Settings** from the tray/menu bar icon menu; on Mac you can also use the app menu Preferences (⌘,)

## Steps

### 1. Open Settings

Settings is a dialog split into a few tabs — **Account / General / Meeting / Permissions / About** (**Permissions shows only on Mac**; there's no such page on Windows).

### 2. General: all the core settings

The General tab includes (as shown in the UI):

- **Shortcuts**: change the dictation trigger key and other keys; conflict checking runs automatically as you set them, and conflicting keys won't be accepted
- **Speaking style**: "Keep my wording" / "Deep AI polish" (default)
- **Interface language**: the display language of the app
- **Translation Language**: the target language for translation (used with translation-type instructions)
- **Language variant**: regional variants for English, Chinese, etc.
- **Microphone**: select the input device and test it
- **Interaction sounds**: toggle for cue sounds
- **Mute while dictating** (on by default): automatically mutes system playback during dictation to avoid interfering with recognition
- **Launch at Startup** (on by default): start automatically on boot
- **FloatBar toggle**: show/hide the floating bar
- **Close-window behavior**: on Mac you can set closing the window to hide the Dock icon; on Windows you can set closing to minimize to the tray

### 3. Meeting: connect a calendar

The Meeting tab has just one group of settings: **Connect Calendar** — connect **Google Calendar** and **Outlook Calendar** individually (disconnect anytime once connected), keeping AI Meeting Notes in sync with your schedule. Once connected, an "**Upcoming**" schedule section appears at the top of the **Meeting Notes** page, listing future meetings from your calendar. For deeper web-side calendar features like Meeting Bot auto-joining, see [Meeting Bot & Calendar](https://page.gensparksite.com/manual/buddy-guides/v1/en/meeting-notes-bot-and-calendar.md).

### 4. Tray / menu bar icon

The system tray (menu bar on Mac) icon menu offers common actions: **Show/Hide** (show/hide the main window), **Open Settings**, **Add Words to Dictionary**, **Meeting Notes** (after signing in), select microphone, view Time Saved / Word Count stats, check for updates, and **Quit**.

### 5. Check usage and quota

Free users can see a **usage card** in the main window sidebar (showing words used/total, or days left in the trial); paid members have unlimited words and no usage card. The free quota is **4,000 words/week, reset every Monday**.

Once your quota runs out, the FloatBar will prompt **"Usage quota exceeded. Please upgrade your plan or wait for quota reset."** during dictation — wait for the Monday reset, or upgrade your membership to remove the limit.

### 6. Upgrade your membership

The upgrade entry point opens the **Genspark membership page in your browser** to complete the purchase; paid members get unlimited words for dictation, and Meeting Notes recording transcription is credit-free within 24 hours per day.

### 7. Feedback and updates

- **Feedback**: in the recent transcription list on the **Home** page, hovering over any record reveals a **feedback flag icon** — click it to submit feedback on that transcription. Feedback attaches that transcription and its audio, and is used solely to improve recognition quality; it **is not used to train general-purpose models**.
- **Updates**: check for updates from the tray menu to stay on the latest version

## FAQ

**Why won't any of my shortcuts save?**
Conflict checking runs when you set a shortcut, and keys that clash with the system or common apps are rejected — just pick a different combination.

**Where do I see how much free quota is left?**
Free users see the usage card in the main window sidebar (words used/total); the quota resets every Monday. Paid members have unlimited words, so it isn't shown.

**After upgrading, is anything still charged in credits?**
Dictation-type features (dictation / Hands-free / custom instructions / rewrite selection) are entirely unlimited; Meeting Notes recording transcription is credit-free within 24 hours per day (excess is charged at normal credit rates), and Agent Mode tasks are billed under the Super Agent credit rules.

**How do I fully quit the app?**
Click Quit in the tray/menu bar icon menu. Simply closing the window won't quit it — on Mac it hides by default, and on Windows it minimizes to the tray by default (you can change this behavior in General).

## Next steps

- Dictation and the various voice modes → [Dictation & Voice Modes](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-dictation-and-modes.md)
- Custom instructions and dictionary → [Custom Instructions & Dictionary](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-custom-instructions-and-dictionary.md)
- Full details on dual-track billing → [Product Overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-overview.md)
