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

### Step 6: Import Workflow

Import the `workflow.json` file into n8n.

---

## 📸 Screenshots

### Workflow Architecture

(Add workflow screenshot)

### WhatsApp Conversation

(Add WhatsApp screenshot)

### Google Sheet Database

(Add Sheet screenshot)

### Payment Flow

(Add payment screenshot)

---

## 🔮 Future Improvements

- Multi-doctor support
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
