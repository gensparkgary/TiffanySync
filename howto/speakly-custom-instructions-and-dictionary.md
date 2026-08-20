# Speakly — Custom Instructions & Personal Dictionary

> For Buddy Agent internal use.
> type: howto | feature: speakly | keywords: Custom Instructions, Custom Instructions, Shortcuts, Templates, Translate to English, Dictionary, Dictionary, Proper Nouns, Auto-added
> User loop: Enable/create instructions on the Shortcuts page + add words in Dictionary → hold your custom key and speak, get text processed to your instructions, proper nouns never misspelled again

## Why use Custom Instructions and the Dictionary

- **Recurring needs in one press**: Always want to "speak Chinese, get English," or "rewrite in professional tone"? Bind the processing rule to a key—hold it, speak, and you get the finished result, no need to explain it verbally every time.
- **Teach proper nouns once**: Add product names, people's names, and industry jargon to the dictionary, and they'll be spelled correctly in every dictation—no need to fix them one by one afterward.
- **Set your own rules**: If the built-in templates aren't enough, write rules in your own words and create your own custom instructions.

## Prerequisites

- Speakly installed and signed in (see [Get Started](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-get-started.md))
- Dictating with a custom instruction uses your **word quota** (same as regular dictation), no credits deducted; the dictionary itself is free
- Entry points: main window sidebar **Shortcuts** and **Dictionary**

## Steps

### 1. Open the Shortcuts page to view built-in templates

Go to **Shortcuts** from the main window sidebar. The page has two sections: at the top, **Default Shortcuts** manages the keys for the three core modes—dictation / Agent Mode / Hands-free. Scroll down and **below** the core mode section is **Recommended Shortcuts**, the built-in instruction template section—by default only **3** templates are shown, click **See more** to expand all of them. Built-in templates include: **Translate to English**, **Terminal Helper**, **Professional Rewrite**, **Chaos Mode**, and **Buzzword Mode** (as displayed in the UI). Templates are **all off by default**.

### 2. Enable a template and assign a shortcut

Turn on the template you want and assign it a shortcut. Shortcuts are preset to **Option+1..9 on Mac / Right Ctrl+1..9 on Windows**, and can be changed.

### 3. Speak with a custom instruction

In any app, **hold the instruction's shortcut** and speak—when you release, the text inserted is processed according to the instruction. For example, with Translate to English enabled, speak Chinese and English gets inserted.

You can also combine it with **selection rewriting**: select a block of text first, then hold the instruction key and speak your request—the AI processes the selected content per the instruction.

### 4. Create your own instruction

Beyond the templates, you can create your own: click **+ Add** and fill in **Name**, **AI Prompt** (spell out in your own words how you want the AI to process the text—e.g. "translate to Japanese in a formal tone," or "organize what I say into a Notion-style bullet list"), and **Shortcut** (the bound key, **required**—you can't save without one). There's also an optional **Description** field that serves as a short summary in the list. Once saved, hold the key and speak to trigger it.

### 5. Maintain your personal dictionary

Go to **Dictionary** from the main window sidebar and add proper nouns: click add and **type the word**—the add form has just a single word input field. The **All / Auto-added / Manually-added** at the top of the list are three **filter tabs**—when you correct a word in a transcript, Speakly offers to save the corrected spelling to the dictionary (visible under Auto-added), and next time you say that word it outputs the version you saved. If an auto-added entry isn't right, just delete it from the Dictionary page.

Added words **take effect automatically in every dictation**—no need to enable them manually. The dictionary is stored locally and synced to the cloud, so it follows you across devices. Quick entry: the **Add Words to Dictionary** option in the system tray/menu bar icon menu lets you add words directly.

## FAQ

**Enabled a template but the key does nothing?**
Confirm two things: the template toggle is on, and a shortcut is bound (templates are all off and have no key by default). Also check whether the shortcut conflicts with the system or another app—try a different key.

**What's the difference between custom instructions and speaking styles?**
Speaking styles (Keep my wording / Deep AI polish) are the global output style for regular dictation; custom instructions are dedicated processing rules bound to a separate key (translate, professional rewrite, etc.)—whichever key you press, that rule set produces the text.

**Any way to speak Chinese and get English besides an instruction?**
Yes. You can set the Translation Language (target language) in Settings for use with translation-type instructions; the Translate to English template is the most direct way. See [Settings & Account](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-settings-and-account.md).

**Do I have to add dictionary words one by one manually?**
Not entirely. When you correct a word in a transcript, Speakly offers to save the correction to the dictionary (Auto-added tab). You just need to fill in the proper nouns it hasn't picked up and manage the auto-collected results.

**How many words can the dictionary hold?**
Plenty for everyday use; the exact capacity is as shown in the UI.

**Does accuracy improve over time?**
Yes. The more words you add to the dictionary, the better Speakly handles your accent, pace, and common vocabulary; the underlying model is also updated periodically.

**Want to temporarily disable an instruction for one task?**
Go to the Shortcuts page and turn off that instruction's toggle, or just use the plain dictation key (basic transcription without any instruction applied).

## Next steps

- Dictation basics and how to use each mode → [Dictation & Voice Modes](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-dictation-and-modes.md)
- Shortcut conflicts, language, and other settings → [Settings & Account](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-settings-and-account.md)
- Full product picture and billing rules → [Product Overview](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-overview.md)
