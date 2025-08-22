# Telegram Bot to Google Sheets Automation

🚀 This project demonstrates how to connect a **Telegram Bot** with **Google Sheets** using [Make.com](https://www.make.com/) for seamless automation.

---

## 📌 Project Idea
Whenever you send a message (for example: a YouTube link or a quick note) to your Telegram Bot, it will automatically be saved as a new row in Google Sheets along with a timestamp.

---

## ⚡ Features
- Save important links from Telegram instantly.
- Keep notes and messages organized in Google Sheets.
- Improve productivity by automating repetitive tasks.

---

## 🔧 Tools Used
- **Telegram Bot** (created via BotFather 🤖)
- **Make.com** (Scenario: Watch Updates → Add Row ⚙️)
- **Google Sheets** 📊

---

## 📂 Files
- `README.md` → Project documentation.
- `Telegram Bot.json` → Example of Make.com scenario structure.
---

## 🚀 How it Works
1. Create a Telegram Bot via [BotFather](https://t.me/botfather) and get the API Token.
2. In [Make.com](https://www.make.com/):
   - Add **Telegram Bot** module → *Watch Updates*.
   - Add **Google Sheets** module → *Add Row*.
   - Map the Telegram message → to **Link column**.
   - Add **Now()** function → to **Date column**.
3. Run the scenario → send any message to your bot → data will appear in Google Sheets automatically.

💡 Even small automations like this can make a big difference in daily workflow efficiency!
