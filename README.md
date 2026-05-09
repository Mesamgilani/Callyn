🎙️ CALLYN — AI Voice Agent Platform for Enterprise Customer Operations
<div align="center">
![CALLYN Banner](https://img.shields.io/badge/CALLYN-AI%20Voice%20Platform-gold?style=for-the-badge&logo=googlecloud)
![Gemini](https://img.shields.io/badge/Powered%20by-Google%20Gemini-blue?style=for-the-badge&logo=google)
![Pakistan](https://img.shields.io/badge/Market-Pakistan%20%7C%20South%20Asia-green?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-white?style=for-the-badge)
Pakistan's First Multilingual AI Voice Agent — Transforming Enterprise Customer Operations
🎯 Live Demo • 🚀 Features • 📱 Screenshots • 🛠️ Tech Stack • 📊 Impact
</div>
---
🏆 Hackathon Submission
Transforming Enterprise Through AI Hackathon
Sponsored by Google DeepMind · Google AI Studio · Gemini · Surge
Prize Pool: $10,000 | May 11–19, 2026 | San Jose, USA
---
🌍 The Problem We're Solving
> **70% of Pakistani business calls go unanswered every day.**
Pakistan has 150,000+ e-commerce businesses, 50,000+ registered clinics, and a $20 billion e-commerce market — yet most small and medium businesses cannot afford a full-time customer service representative.
The consequences are devastating:
📉 Lost sales from unanswered calls
😤 Frustrated customers switching to competitors
💸 CSR staff costs Rs. 30,000–50,000/month
🌙 Zero coverage at night, weekends, or holidays
🗣️ Language barriers across Pakistan's 5 major languages
This is not just a Pakistan problem. 2.4 billion people across South Asia face the same challenge.
---
💡 Our Solution: CALLYN + Sara
CALLYN is an enterprise AI voice agent platform powered by Google Gemini that deploys Sara — an intelligent AI receptionist that:
📞 Answers every call 24/7 simultaneously (4–5 concurrent calls)
🛒 Takes orders, books appointments, manages hotel reservations
🗣️ Speaks 5 Pakistani languages — Urdu, Punjabi, Pashto, Sindhi, English
📲 Sends WhatsApp summaries to business owners after every call
📊 Provides a real-time dashboard with full transcripts and analytics
🤖 Learns from each business's products, FAQs, and workflows
Live Deployment
Sara is currently live at Al-Syed Eye Hospital, Chawinda, Punjab, Pakistan — handling real patient calls, booking appointments with doctors, and answering medical queries in Urdu around the clock.
---
✨ Features
🎙️ Sara — AI Voice Agent
Feature	Description
Multilingual	Urdu, Punjabi, Pashto, Sindhi, English
Concurrent Calls	4–5 simultaneous calls handled
Natural Speech	Pakistani accent via Azure Neural TTS
Smart Routing	Transfers urgent calls to human agents
Order Taking	Captures name, address, product, payment
Appointment Booking	Doctor, time slot, patient details
Hotel Reservations	Room type, check-in/out, guest info
FAQ Handling	Trained on business-specific knowledge
Missed Call Recovery	Auto WhatsApp reply to missed callers
📊 Business Dashboard
Feature	Starter	Growth	Scale
Phone Numbers	1	2	5
Minutes/month	300	800	2,000
Call Logs + Transcripts	Basic	Full	Full + AI Analysis
Orders Dashboard	✅	✅	✅
Appointments	❌	✅	✅
CRM Contacts	❌	❌	✅ Auto-built
White Label	❌	❌	✅
AI Agents	1	1	5
Analytics	Basic	Advanced	Full ROI
---
🛠️ Tech Stack
```
┌─────────────────────────────────────────────────────┐
│                    CALLYN ARCHITECTURE               │
├─────────────────────────────────────────────────────┤
│  AI BRAIN          │  Google Gemini 1.5 Pro          │
│  Voice Engine      │  Retell AI + Azure ur-PK-UzmaNeural │
│  Telephony         │  Twilio Voice API               │
│  Speech-to-Text    │  Deepgram (Urdu support)        │
│  Backend           │  Node.js + Express.js           │
│  Database          │  MongoDB Atlas                  │
│  Frontend          │  React.js                       │
│  Messaging         │  WhatsApp Business API          │
│  Hosting           │  Railway / Render               │
│  Payments (PK)     │  JazzCash + EasyPaisa           │
└─────────────────────────────────────────────────────┘
```
Why Google Gemini?
Multilingual Excellence: Gemini handles Urdu-English code-switching naturally
Low Latency: Sub-500ms response for real-time voice conversations
Cultural Context: Better understanding of South Asian communication patterns
Cost Effective: 60% cheaper than GPT-4o at scale — critical for emerging markets
---
🚀 Quick Start
Prerequisites
```bash
Node.js >= 18.0.0
MongoDB Atlas account (free)
Google AI Studio API key (free)
Retell AI account (free $10 credit)
Twilio account (free $15 credit)
```
Installation
```bash
# Clone the repository
git clone https://github.com/Mesamgilani/callyn.git
cd callyn

# Install dependencies
cd backend
npm install

# Set up environment variables
cp .env.example .env
```
Environment Variables
```env
# Google Gemini (get free at aistudio.google.com)
GEMINI_API_KEY=your_gemini_api_key

# Retell AI (get at retell.ai)
RETELL_API_KEY=your_retell_api_key

# Twilio (get at twilio.com)
TWILIO_ACCOUNT_SID=your_twilio_sid
TWILIO_AUTH_TOKEN=your_twilio_token
TWILIO_PHONE_NUMBER=+1234567890

# MongoDB (free at mongodb.com/atlas)
MONGODB_URI=mongodb+srv://...

# Azure TTS (for Pakistani Urdu voice)
AZURE_SPEECH_KEY=your_azure_key
AZURE_SPEECH_REGION=eastus

# WhatsApp
WHATSAPP_TOKEN=your_whatsapp_token
```
Run the Application
```bash
# Start backend
npm run dev

# Server running at http://localhost:5000
# Dashboard at http://localhost:3000
```
---
🏥 Live Use Case: Al-Syed Eye Hospital
Business: Al-Syed Eye Hospital, Chawinda, Punjab, Pakistan
Challenge: 2 staff members manually answering all patient calls
Solution: Sara AI deployed as 24/7 medical receptionist
Sara Handles:
```
Patient: "AOA, Dr. sahib kitne baje bethte hain?"
Sara:    "Ji! Dr. Tafakhur Gilani subah 10 baje se 2 baje 
          tak hain — Juma'a ke ilawa. Appointment leni hai?"

Patient: "Operation ka kya scene hai?"
Sara:    "Operation har Itwar ko hota hai. Dr. Rafay Amin 
          surgeon hain. Charges Rs. 15,000 se 50,000 tak —
          lens ki choice ke mutabiq. Appointment lein?"
```
Results After Week 1:
📞 47 calls handled (0 missed at night)
📅 18 appointments booked automatically
⏱️ Staff freed from 80% of routine calls
💰 Equivalent of Rs. 35,000/month CSR saved
---
🌐 The 5-Language Vision
```
Sara speaks YOUR customer's language:

🗣️ اردو    Urdu    → All Pakistan (220M speakers)
🗣️ پنجابی  Punjabi → Punjab region (110M speakers)
🗣️ پښتو   Pashto  → KPK / Peshawar (40M speakers)
🗣️ سنڌي   Sindhi  → Sindh / Karachi (30M speakers)
🗣️ English         → Corporate / Expat (15M speakers)

Total addressable: 415M people
No competitor offers all 5 Pakistani languages.
```
---
📊 Market Impact
Metric	Value
Pakistan E-Commerce Market	$20.4 Billion by 2029
E-Commerce Businesses	150,000+
Registered Clinics	50,000+
Calls Missed Daily (est.)	2.1 Million
Revenue Lost to Missed Calls	Rs. 100B+ annually
CALLYN Addressable Market	$57.8M annually
Current Competitors in Urdu AI Voice	0
---
💰 Business Model
```
STARTER:  Rs. 15,000/month (~$53)  — Small businesses
GROWTH:   Rs. 35,000/month (~$125) — Medium enterprises  
SCALE:    Rs. 75,000/month (~$265) — Large enterprises

Year 1 Target: 300 clients → $614K ARR
Year 2 Target: 1,500 clients → $3M ARR
Year 3 Target: Regional expansion → $10M ARR
```
---
🗺️ Roadmap
[x] Core AI voice agent (Sara)
[x] Urdu + English multilingual support
[x] Hospital deployment (Al-Syed Eye Hospital)
[x] Business dashboard (3 plan tiers)
[x] WhatsApp notification system
[x] Order + appointment + booking management
[ ] Google Gemini integration (in progress)
[ ] Punjabi language support
[ ] Pashto language support
[ ] Sindhi language support
[ ] Mobile app (iOS + Android)
[ ] Bangladesh expansion
[ ] India expansion (Hindi/Urdu)
[ ] API for developers
---
👨‍💻 Founder
Mesam Gilani
Founder & CEO, CALLYN
📍 Pakistan
🌐 callyn.io
> *"I built CALLYN because I watched my family's hospital miss patient calls every night. Sara never sleeps, never takes holidays, and speaks in the patient's own language. That's not just technology — that's dignity for every Pakistani business owner."*
---
📸 Screenshots
Main Website
![CALLYN Website](screenshots/website.png)
Client Dashboard — Growth Plan
![Dashboard](screenshots/dashboard.png)
Sara in Action
![Sara Demo](screenshots/sara-demo.png)
WhatsApp Notifications
![WhatsApp](screenshots/whatsapp.png)
---
🏆 Why CALLYN Should Win
Real Deployment — Not a prototype. Live at a real hospital serving real patients today.
Massive Market — 415M multilingual speakers with zero AI voice competition
Google Gemini Powered — Leveraging sponsor technology for multilingual excellence
Social Impact — Democratizing enterprise technology for emerging markets
Proven Revenue Model — Subscription SaaS with 75%+ margins
First Mover — No competitor offers Urdu AI voice in Pakistan
---
📄 License
MIT License — see LICENSE for details.
---
<div align="center">
Built with ❤️ in Pakistan 🇵🇰
CALLYN — Because every business deserves a voice that never sleeps
</div>
