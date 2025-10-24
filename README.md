# Mr Tan Auto Message Bomber Tool

> **Warning:** This tool can repeatedly type and send the same message. It can easily be abused for spamming or other unauthorized actions. This project is intended **only** for educational, testing, and authorized-use scenarios. Do not run it against other people's systems or services without explicit permission.

---

## Brief Description

**Mr Tan Auto Message Bomber Tool** is a Windows-based Python script that:

- Generates a unique device key from the system username and MAC address.
- Checks remote server status and block list (via raw GitHub URLs).
- Sends the device key to an admin via a Telegram bot.
- Takes a user message and a sending limit, then simulates keyboard input to type the message and press `Enter` repeatedly.

> Note: The tool uses `pyautogui` (keyboard emulation) so it types to the **active window** where the cursor is focused.

---

## Features

* Unique device key (username + MAC).
* Server on/off and block-list checks.
* Telegram bot integration to send keys to Devoloper.
* Keyboard emulation with message typing and `Enter`.
* Designed for Windows only.

---

## Usage


1. Enter your name when prompted.
2. Tool checks remote server and block list.
3. Device key will be sent to admin Telegram ID.
4. Enter the message at `Write Your Msg:` and the `Sending Limit:`.
5. After countdown it will type the message into the active window repeatedly.

---

## Converting to .exe (recommended method)

This tool **can** be converted to an `.exe` that runs on Windows without Python installed. See the conversion section below for detailed steps.

---

## Security & Best Practices

* **Never** hardcode secret tokens (Telegram bot token) or admin IDs in plain text for distributed `.exe`. Use environment variables or external config encrypted at runtime.
* Test thoroughly in an isolated environment.
* Be aware some antivirus engines may flag auto-typing and remote-communication tools as suspicious — sign your binary if needed for distribution.

---

## Legal & Ethical Notice

You must have explicit permission to run this on any machine or target. Unauthorized or malicious use is illegal. The author (Mr Tan) is not responsible for misuse.

---

## Credits

**Created by:** Mr Tan  
**GitHub:** https://github.com/mrtan-official  
