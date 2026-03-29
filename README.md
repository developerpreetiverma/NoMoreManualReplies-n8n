# WhatsApp Lead Automation (n8n)

An automated workflow built using n8n to handle WhatsApp leads, reduce manual replies, and streamline follow-ups.

## Problem

Managing repeated WhatsApp queries and follow-ups manually was time-consuming.

## 💡 Solution

This workflow automates:
- Sending initial response to incoming messages
- Collecting user details
- Checking for email in response
- Sending welcome video (if email present)
- Saving incomplete leads in Excel with "Need Follow-up" flag

## ⚙️ Workflow Logic

1. User sends WhatsApp message
2. Auto-reply asks for details
3. System checks for email:
   - ✅ If email exists → send welcome video
   - ❌ If not → store in Excel with follow-up flag

## 🛠 Tech Stack

- n8n (workflow automation)
- WhatsApp API (via webhook)
- Google Sheets / Excel
- HTTP nodes

## 📂 How to Use

1. Import `workflow/whatsapp-lead-automation.json` into n8n
2. Configure credentials:
   - WhatsApp API
   - Google Sheets / Excel
3. Activate workflow

## 📸 Screenshots

(Add your workflow screenshot here)

## 👨‍💻 Author

Preeti Verma
