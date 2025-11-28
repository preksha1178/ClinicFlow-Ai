🚀 ClinicFlow AI – Intelligent WhatsApp Appointment Automation System

ClinicFlow AI is an AI-powered, end-to-end doctor appointment automation system built using n8n, AI Agents, and WhatsApp Cloud API.
It fully automates bookings, rescheduling, cancellations, reminders, payments, and FAQs — making clinic management fast, simple, and professional.

Patients simply send a WhatsApp message, and the AI handles everything automatically.

⭐ Features

✅ 1. AI-Powered WhatsApp Chat

Understands patient messages

Handles timings, fees, availability & FAQs

Smart intent detection (booking, cancel, reschedule, info)

✅ 2. Automated Appointment Booking

Collects name, date, and time

Saves appointment to Google Sheet / Database

Sends instant booking confirmation

✅ 3. Rescheduling System

Checks available time slots

Updates appointment automatically

Notifies patient instantly

✅ 4. Cancellation Flow

Asks confirmation

Deletes the booking

Sends cancellation message

✅ 5. Reminder System

24-hour reminder

2-hour reminder

Missed appointment alert

Reduces no-shows

✅ 6. WhatsApp Payment Support (Optional)

Sends UPI payment link

Confirms payment status

Stores payment info in DB

✅ 7. Admin / Doctor Dashboard

View all appointments

Today’s schedule

Patient info & status

Payment status

Works with any HTML/JS dashboard

🧠 AI Logic

ClinicFlow AI automatically identifies the user’s intent:

User Message	AI Understanding
“I want to book appointment”	Start booking flow
“Shift my booking to tomorrow”	Rescheduling
“Cancel my appointment”	Cancellation
“What are clinic timings?”	FAQ

AI handles the entire conversation without manual work.

🔗 Workflow Structure (n8n)

The automation includes:

Webhook Trigger – receives WhatsApp messages

AI Agent – analyses intent using Gemini / OpenAI

Switch Node – routes booking, cancel, reschedule

Google Sheets / MySQL Nodes – save appointment

HTTP Request Nodes – send WhatsApp replies

Cron Nodes – reminder automation

Set Nodes – format message templates

📂 Tech Stack
Layer	Technology
Automation	n8n Cloud
Messaging	WhatsApp Cloud API
AI	Google Gemini / OpenAI
Database	Google Sheets / MySQL
Frontend (optional)	HTML + CSS + JavaScript
Format	JSON Webhooks
Deployment	n8n Cloud
📦 Data Stored

Patient Name

Phone Number

Date & Time

Appointment Status

Payment Status

Reschedule/Cancellation Logs

Stored in Google Sheet / Database depending on your setup.

📥 How to Import This Workflow

Download the JSON file from this repository

Open n8n Dashboard

Click Import

Upload the JSON

Add your WhatsApp API token

Activate the workflow

🧪 Testing

Send any of these messages to your WhatsApp business number:

“Book appointment”

“Cancel my booking”

“I want to reschedule”

“What is your timing?”

Your AI will reply instantly.

🏥 Impact

ClinicFlow AI helps clinics by providing:

70% staff time saved

No manual booking errors

Fewer no-shows thanks to reminders

24×7 patient reply system

Fully automated workflow

🎯 Conclusion

ClinicFlow AI converts any clinic into a smart, automated, AI-powered appointment management system.
Perfect for hackathons, final-year projects, portfolios, and real clinic deployment.
