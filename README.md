# ai-healthcall-plus
# 🧠 AI HealthCall+

AI HealthCall+ is an AI-powered phone call assistant designed to book diagnostic test appointments over voice using GPT-4o and Twilio. It stores the booking details in a database and sends SMS confirmations and reminders.

---

## 🔧 Features
- Real-time AI voice conversation with users (via Twilio)
- Books test appointments through conversation
- Saves booking details to SQLite database
- Sends confirmation SMS using Fast2SMS
- Sends automated reminders 1 hour before appointment

---

## ⚙️ Tech Stack
- **Language**: Python
- **Backend**: FastAPI
- **AI Model**: OpenAI GPT-4o
- **Voice Call**: Twilio
- **SMS API**: Fast2SMS
- **Scheduler**: APScheduler
- **Database**: SQLite (local)

---

## 🚀 How to Run

### 1. Clone the Repo

```bash
git clone https://github.com/Bhumikapatil2006/ai-healthcall-plus.git
cd ai-healthcall-plus
