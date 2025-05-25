# 🤖 VoiceBox — Smart, Scalable, Seamless

> Automate your entire appointment booking workflow — just by talking.

---

## 🎯 What is This?

An AI-powered **voice agent** that automates appointment booking using natural conversation. Integrated with:

- 🧠 **Vapi.ai** – Voice agent framework  
- ⚙️ **n8n** – Workflow automation  
- 📅 **Cal.com** – Scheduling backend  
- 🧾 **Airtable** – Availability database  
- 📆 **Google Calendar** – Real-time sync  
- 📞 **Twilio** – SMS/Voice confirmations  
- 🗣️ **ElevenLabs** – Human-like voice output  
- 🔁 **Postman** – A2A (agent-to-agent) escalation

---

## 💡 Why We Built It

Manual appointment scheduling wastes time, leads to errors, and doesn’t scale. Our agent:

✅ Books appointments via natural voice  
✅ Checks availability in real-time  
✅ Sends instant confirmations/reminders  
✅ Handles conflicts with smart logic  
✅ Connects agents when needed  

---

## 🛠️ Tech Stack

| Tool        | Role                         |
|-------------|------------------------------|
| Vapi.ai     | Conversational AI (voice)    |
| n8n         | Logic & automation backend   |
| Cal.com     | Appointment booking platform |
| Airtable    | Stores slot availability     |
| Google Calendar | Syncs booked events     |
| Twilio      | Sends voice/SMS confirmations|
| ElevenLabs  | Natural TTS voice responses  |
| Postman     | A2A testing + API calls      |

---

## 🧪 How It Works

1. User talks to AI Agent via phone/web  
2. Vapi captures intent → n8n processes logic  
3. Availability is fetched from Airtable  
4. Slot is booked via Cal.com and synced with GCal  
5. Confirmation sent via Twilio (SMS/call)  
6. ElevenLabs returns realistic voice responses  
7. For edge cases, fallback to another agent using Postman A2A call

---

## 🌍 Where It Can Be Used

- 🏥 Healthcare Clinics  
- 💼 Consultants / Coaches  
- 🏫 Educational Institutions  
- 💇 Salons & Personal Services  
- 🛠️ On-demand Home Repairs  
- 📞 Customer Support Automation  

---

## 🚀 Getting Started

1. **Clone this repo**
2. Set up `.env` file with API keys:
   - Vapi.ai, Twilio, Airtable, Cal.com, GCal, ElevenLabs
3. Import n8n workflow (provided in `/flows`)
4. Test agent locally or deploy via webhook
5. Try it with Postman or actual voice call

---

## 🔁 Agent-to-Agent Demo (A2A)

1. Initiate call from Agent A  
2. Conflict or escalation triggers Agent B  
3. Agent B receives data + context via Postman  
4. Booking continues seamlessly

---

## 📹 Demo

[🎥 Watch the demo](https://link-to-your-video.com)  
(Voice interaction → Slot booking → Calendar entry → Confirmation SMS)

---

## 📌 What's Next?

- Add rescheduling & cancellation flow  
- Dashboard UI for admins  
- Personalized agent memory for repeat users  
- Multilingual support  
- Live voice-based feedback loop

---

## 💬 Final Note

> **The future of scheduling is voice-first, intelligent, and fully automated — let’s lead it.**

---

## 🧠 Built with ❤️ during Holboxathon
