# AMI ClientConnect Dashboard

A production-grade **WhatsApp-based financial operations dashboard** designed to monitor AI chatbot conversations, enable real-time human takeover, and manage follow-ups for a SEBI-registered mutual fund distributor.

This system integrates with the **WhatsApp Cloud API** to ensure reliable message handling, multi-client routing, and secure audit-ready conversation logging — preventing missed high-intent investment opportunities.

---

## Features

- Real-time monitoring of WhatsApp chatbot conversations
- Human takeover (bot ON/OFF) controls per client
- Multi-client message routing and segregation
- Follow-up tracking for high-priority conversations
- Secure storage of messages and files for audit and compliance
- GPT-4 powered chatbot responses with fallback to human agents

---

## Tech Stack

- **Backend:** Python (Flask)
- **Database:** MongoDB
- **Messaging:** WhatsApp Cloud API
- **Frontend:** JavaScript
- **Automation:** Make.com
- **AI:** OpenAI GPT-4

---

## System Workflow

1. Incoming WhatsApp messages are received via WhatsApp Cloud API webhooks.
2. Flask backend processes and routes messages based on client and conversation state.
3. Messages and metadata are stored in MongoDB for reliability and auditing.
4. GPT-4 generates automated responses when chatbot mode is enabled.
5. Human agents can monitor conversations and take over in real time using the dashboard.

---

## Installation & Setup

### Prerequisites

- Python 3.9+
- MongoDB (local or Atlas)
- WhatsApp Cloud API credentials
- OpenAI API key

### Clone the Repository

```bash
git clone https://github.com/Akshara-Amirtharaj/AMI-Client-Connect-Dashboard.git
cd AMI-Client-Connect-Dashboard
