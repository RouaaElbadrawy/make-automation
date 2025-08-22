# Telegram Bot → Google Sheets Automation

🚀 This project shows how to connect a **Telegram Bot API** with **Google Sheets** using [Make.com](https://www.make.com/) for seamless automation.

---

## 📌 Project Idea
Every time I send a **message** (not only links — any quick note or text) to my Telegram Bot, it automatically gets saved in Google Sheets along with the timestamp ⏳.

---

## ⚡ Benefits
- Never lose important notes in chats again 💬  
- Keep everything organized in Google Sheets 📊  
- Save time & boost productivity ⏱️  
---

## 🔧 Tools Used
- **Telegram Bot** (via BotFather 🤖)  
- **Make.com** (Scenario: Watch Updates → Add Row ⚙️)  
- **Google Sheets** 📑  

---

## 📂 Files
- `README.md` → Documentation for the project.  
- `Telegram Bot.json` → Example scenario file structure.  

---

## 🚀 How it Works
1. Create a Telegram Bot via [BotFather](https://t.me/botfather) and get the **API Token**.  
2. In [Make.com](https://www.make.com/):  
   - Add **Telegram Bot** module → *Watch Updates*.  
   - Add **Google Sheets** module → *Add Row*.  
   - Map the message text → to **Message column**.  
   - Add **Now()** → to **Date column**.  
3. Run the scenario → Send any message to the bot → A new row will appear in Google Sheets automatically.  


---

💡 Even small automations like this can make a big difference in everyday workflows!
