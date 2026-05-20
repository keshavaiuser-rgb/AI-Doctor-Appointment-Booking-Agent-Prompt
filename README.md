An AI-powered Doctor Appointment Booking System built using n8n workflow automation, WhatsApp API, OpenAI/OpenRouter, Google Calendar, Google Sheets, Razorpay, Docker, and ngrok.

This project automates the complete patient appointment process through conversational AI. Patients can book, reschedule, or cancel appointments through WhatsApp while the system handles availability checking, token generation, payment processing, reminders, and database updates automatically.

---

## 🚀 Features

- 📲 WhatsApp-based appointment booking
- 🤖 AI conversational assistant using OpenAI/OpenRouter
- 📅 Real-time Google Calendar availability checking
- 🔄 Appointment booking, cancellation, and rescheduling
- 🎫 Automatic date-wise token generation
- 💳 Razorpay payment link generation
- ✅ Payment verification through webhook
- 📊 Google Sheets integration for patient records
- 🧠 Context memory for natural conversations
- 🚨 Emergency request detection
- 🔔 Automated reminders and follow-up messages
- ❌ Duplicate booking prevention
- 🐳 Local deployment using Docker + ngrok

---

## 🛠️ Tech Stack

- n8n
- OpenAI / OpenRouter
- WhatsApp API
- Google Calendar API
- Google Sheets API
- Razorpay API
- Docker
- ngrok

---

## 📋 Workflow Overview

1. Patient sends a message on WhatsApp
2. AI understands user intent
3. Required patient details are collected
4. System checks Google Calendar availability
5. Available slot is suggested or booked
6. Appointment details are stored in Google Sheets
7. Token number is generated automatically
8. Razorpay payment link is generated
9. Patient completes payment
10. Payment webhook confirms payment
11. Appointment confirmation is sent automatically
12. Reminder messages are sent before appointment

---

## 📂 Project Structure

```bash
AI-Doctor-Appointment-Agent/
│
├── README.md
├── workflow.json
├── images/
│   ├── workflow.png
│   ├── whatsapp-chat.png
│   ├── google-sheet.png
│   └── payment-flow.png
│
├── docs/
│   └── setup-guide.md
```

---

## ⚙️ Installation & Setup

### Step 1: Clone Repository

```bash
git clone https://github.com/yourusername/AI-Doctor-Appointment-Agent.git
```

### Step 2: Install Docker

Download and install Docker.

### Step 3: Run n8n locally

```bash
docker run -it --rm \
-p 5678:5678 \
n8nio/n8n
```

### Step 4: Configure ngrok

```bash
ngrok http 5678
```

### Step 5: Configure API credentials

Add:

- WhatsApp API credentials
- OpenRouter/OpenAI API key
- Google Calendar credentials
- Google Sheets credentials
- Razorpay credentials

## 📸 Screenshots

### Workflow Architecture


<img width="1857" height="831" alt="AI Doctor Appointment Booking Agent" src="https://github.com/user-attachments/assets/cd90a48e-2cdb-411b-b44e-bc5cfbfc0510" />

### WhatsApp Conversation

<img width="1270" height="473" alt="Screenshot 2026-05-20 174459" src="https://github.com/user-attachments/assets/fc0f1300-200b-4153-a388-9b4781339da0" />
<img width="1251" height="518" alt="Screenshot 2026-05-20 174443" src="https://github.com/user-attachments/assets/e9482393-bf9c-42f6-b1a7-e73454834961" />


### Google Sheet Database

<img width="1800" height="445" alt="Screenshot 2026-05-20 180224" src="https://github.com/user-attachments/assets/14bd6eac-7826-4b33-b201-8e451afb4a77" />


### Payment Flow

 <img width="1850" height="895" alt="Screenshot 2026-05-20 180325" src="https://github.com/user-attachments/assets/8ecc1d00-0f78-48c4-9a93-c45568f2522b" />

---

## 🔮 Future Improvements

- Voice appointment booking
- Email notifications
- Dashboard for doctors
- Appointment analytics
- AI symptom analysis

---

## 👨‍💻 Author

Keshav Purohit

AI Automation | n8n | Workflow Automation | Conversational AI

---

## ⭐ Support

If you found this project useful, give it a star ⭐
