# Speakly — Get Started

> For Buddy Agent internal use.
> type: howto | feature: speakly | keywords: download, install, sign in, permissions, shortcuts, first dictation, get started, onboarding, Fn, Right Alt
> User loop: Download from speakly.ai → install and sign in with Genspark account → grant permissions, set trigger key → complete your first dictation in any app, with text appearing at the cursor

## Why install Speakly

- **Speak and it's ready to send**: Hold a key and talk, then release — polished written text appears right at your cursor. Long emails and long messages no longer wait on your typing speed.
- **Works everywhere**: It doesn't care which app you're in — chat box, document, code editor. Wherever your cursor is, that's where the text shows up.
- **Free trial on install**: Finish onboarding and you unlock 1 week of unlimited dictation — try it fully before you decide.

## Prerequisites

- Entry point: `https://speakly.ai` (download and intro page); you can also download it from the Speakly card at `genspark.ai/download`
- A Genspark account (for signing in; you can register during sign-in if you don't have one)
- Requires an internet connection

## Steps

### 1. Download the right version

Open `https://speakly.ai` to download: on Mac, pick the installer that matches your chip; Windows has its own installer. Mobile users can search for Speakly in the App Store / Google Play (on mobile you talk by pressing a button inside the app — there's no global shortcut).

### 2. Install and sign in

The first time you open it after installing, sign in with your **Genspark account**: the app opens your browser to complete sign-in, and once you're signed in it returns to Speakly automatically.

### 3. Grant permissions (different on Mac and Windows)

The first-launch onboarding requests permissions in order:

- **Mac**: You need **Accessibility** permission (so polished text can be inserted at the cursor in other apps) and **Microphone** permission; **System Audio** permission is optional (only needed when using Meeting Notes to record sound playing on your system). You can verify permission status under **System Settings → Privacy & Security → Accessibility**.
- **Windows**: Just grant microphone access; recording system audio needs no extra permission.

### 4. Complete the first-launch onboarding

Onboarding walks you through: testing your microphone → setting the dictation trigger key (default **Fn on Mac / Right Alt on Windows**, which you can change to another key; when you press to test, the button turns blue to confirm it triggered) → practicing dictation once each in Notion, Outlook, and Slack → practicing selection rewrite and voice questions → an intro to Agent Mode and multilingual support.

The end of onboarding unlocks your trial: **"Enjoy 1 week of unlimited access!"** — for the next 1 week, dictation has no word limit.

### 5. Your first dictation

Open any app where you can type text and place your cursor in the input box:

1. **Hold** the trigger key (default Fn on Mac / Right Alt on Windows) and start talking
2. **Release** when you're done
3. The AI-polished text appears right at your cursor

A **FloatBar** overlay on screen shows "Click or hold {key} to dictate," and it displays the current status during dictation.

## FAQ

**Why is Accessibility permission required on Mac?**
Speakly has to "type" the polished text into the app you're using, which requires the system's Accessibility permission. Without it, it can record but can't insert text.

**I pressed the key but nothing happened / no text appeared?**
Check in order: ① Is Speakly running in the background; ② Are permissions granted (Mac: check System Settings → Privacy & Security → Accessibility, and confirm microphone permission); ③ Is the trigger key taken by another app or has it been changed — check the currently set key under Settings → General; ④ Restart Speakly and try again. Also confirm your cursor is in a place where you can type.

**I finished recording but the text wasn't inserted at the cursor?**
Usually the focus switched to another window during recording, or Accessibility permission wasn't fully granted — keep the target app in the foreground during recording and don't switch windows midway. If insertion still fails, Speakly automatically shows a popup with the transcribed text so you can copy and paste it manually.

**What do I do if the app is unresponsive?**
Fully quit and reopen Speakly; confirm your network is working (an internet connection is required); if that still doesn't work, uninstall and reinstall the latest version.

**What if the default trigger key conflicts with a shortcut I use often?**
You can change it. Go to the shortcut settings under Settings → General and pick another key; conflicts are checked automatically as you set it. See [Settings and Account](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-settings-and-account.md) for details.

**Can I use it without a Genspark account?**
You need to sign in with a Genspark account to use it, and you can register a new account right from the sign-in page.

**What happens after the one-week trial ends?**
You return to the free tier: 4,000 words of dictation per week, reset every Monday; paid members have no word limit. See the quota notes in [Settings and Account](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-settings-and-account.md) for details.

## Next steps

- Make the most of dictation, Hands-free, Agent Mode, and selection rewrite → [Dictation and Voice Modes](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-dictation-and-modes.md)
- Set up custom instructions and a personal dictionary → [Custom Instructions and Dictionary](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-custom-instructions-and-dictionary.md)
- Record meetings and see live translation captions → [Meeting Notes and Live Translation](https://page.gensparksite.com/manual/buddy-guides/v1/en/speakly-meeting-notes-and-live-translation.md)
