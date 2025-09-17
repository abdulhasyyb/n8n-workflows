# n8n-workflows
My n8n workflows
# 🚀 n8n Workflows Collection

This repository contains a set of automation workflows built using [n8n](https://n8n.io).  
Each workflow solves a real-world use case, combining **AI, Gmail, Google Sheets, Drive, Hugging Face, and more**.  

---

## 📂 Workflows Overview

### 1. Email Internship Parser (Email + Attachment → Sheets)
Automatically fetches internship/job emails with PDF attachments, extracts important details using AI, and logs them into Google Sheets.

**Highlights:**
- Monitors Gmail for unread internship/job emails.  
- Downloads and extracts text from PDF attachments.  
- Uses **Google Gemini AI** to structure details (company, role, stipend, location, deadline, etc.).  
- Logs data into a **Google Sheet** for tracking.  

✅ **Result:** Internship/job emails get parsed and tracked in Sheets automatically.  

---

### 2. AI Chat + Image Generator (Chat → Hugging Face → Gmail/Drive)
An AI-powered chat workflow that can both answer questions and generate images.  

**Highlights:**
- Classifies user input into text query or image generation.  
- Handles queries with **Google Gemini AI + Wikipedia**.  
- Generates images via **Hugging Face (FLUX.1-schnell)**.  
- Sends images via **Gmail** and saves them in **Google Drive**.  

✅ **Result:** Smart AI assistant that answers questions and creates AI images on demand.  

---

### 3. Email + Label + Sheets
Automates classification and tracking of emails.  

**Highlights:**
- Listens for new Gmail messages.  
- Extracts key details and classifies them with **Google Gemini AI**.  
- Auto-labels emails inside Gmail.  
- Logs results into **Google Sheets**, including internship type (paid/unpaid).  

✅ **Result:** Emails are neatly organized and tracked with minimal effort.  

---

### 4. Azar Bags AI Agent
AI-powered chatbot workflow designed for **Azar Bags** customer queries.  

**Highlights:**
- Uses **Google Sheets** as a dynamic product database.  
- **Google Gemini AI** generates short, professional replies.  
- **ElevenLabs** adds voice responses.  
- Exposed via **Webhook** to embed as a website widget.  
- Can check stock, confirm bookings, and send confirmation emails.  

✅ **Result:** Acts as a smart assistant for customer queries and order handling.  

---


---

## 🚀 Usage
1. Import workflows into your **n8n instance**.  
2. Configure credentials (Gmail, Google Sheets, Hugging Face, Drive, etc.).  
3. Trigger and customize based on your use case.  

---

## 📜 Roadmap
Planned future workflows:  
- Automated Job Application Tracker  

---
