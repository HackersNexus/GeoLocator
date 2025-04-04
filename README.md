# Live GPS Tracker to Telegram (Android App)

This Android app sends live GPS location updates to a Telegram user whenever the device moves from one place to another. It uses a Telegram bot to deliver these updates directly to your Telegram chat.

---

## Features

- Live GPS tracking
- Sends location only on movement
- Works in background
- Sends data to Telegram via bot
- Simple setup via bot token and chat ID

---

## Requirements

- Android device with GPS
- Telegram account
- Telegram bot token
- Your Telegram chat ID
- Internet connection (Wi-Fi or Mobile Data)

---

## How to Set Up

### 1. Create a Telegram Bot

1. Open Telegram and search for `@BotFather`.
2. Start a chat and send `/start`.
3. Type `/newbot` to create a new bot.
4. Give your bot a **name** (any name you like).
5. Then, set a **username** for the bot (must end in `bot`, e.g., `MyTrackerBot`).
6. BotFather will respond with your **bot token** (e.g., `123456789:ABCDefghIJKlmnoPQRstuVWxyZ`).

> Save this token for use inside the app.

---

### 2. Get Your Telegram Chat ID

1. In Telegram, search for `@WhatChatIDBot`.
2. Start a conversation with it.
3. It will display your **Telegram User ID** (a number like `123456789`).

---

### 3. Set It Up in the App

1. Launch the app on your Android device.
2. You will see two textboxes:
   - **Bot Token**: Paste the token from BotFather here.
   - **Telegram User ID**: Paste the Chat ID from @WhatChatIDBot here.
3. Click the **Save** button.

The location tracking service will now start. When the device moves, the app will send a new GPS location update to your Telegram chat using the bot.

---

## Permissions Needed

- Location Access (GPS)
- Internet Access
- Foreground service (for continuous tracking on newer Android versions)

---

## Notes

- Disable battery optimization for this app to ensure it runs continuously in the background.
- The app does **not** store your location; it only sends it to your Telegram chat securely via your own bot.

---

## Disclaimer

This app is intended for **personal and educational** use only. Do not use it to track others without consent.

---

## License

MIT License

---

## Developer

Built by Hackers Nexus 
Feel free to contribute or report issues.
