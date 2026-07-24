# Intelligent Email Routing System

![Make.com](https://img.shields.io/badge/Make.com-Automation-6D00CC?style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4.1_Mini-10A37F?style=for-the-badge)
![Gmail](https://img.shields.io/badge/Gmail-API-EA4335?style=for-the-badge)
![Slack](https://img.shields.io/badge/Slack-API-4A154B?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

AI-powered email routing system that classifies, prioritizes, routes incoming emails to the appropriate department, and automates customer acknowledgements

## Tech Stack

- Make.com
- Gmail API
- OpenAI GPT-4.1 Mini
- Slack API

---

## The Challenge

Businesses often receive sales inquiries, support requests, HR questions, and finance-related emails through a shared inbox. This project automates the entire email triage process by using AI to classify, prioritize, and route incoming emails while generating professional acknowledgement responses for customer support inquiries.
---

## Features

- 📧 Monitors a Gmail inbox for new emails.
- 🤖 Uses GPT-4.1 Mini to classify incoming emails.
- 🚦 Assigns High, Medium, or Low priority.
- 📝 Generates concise AI summaries.
- 💬 Routes emails to the appropriate Slack channel.
- ✉️ Drafts acknowledgement emails for Customer Support.
- ⏱️ Delays automated responses for a more natural customer experience.
- 🛡️ Uses structured JSON outputs for reliable automation.
---

## Workflow

![Workflow](assets/emailrouting.jpg)

*Complete Make.com workflow for AI-powered email classification, routing, Slack notifications, and automated customer acknowledgements.*

## Demo

| Incoming Email | AI Processing | Outcome |
|----------------|--------------|--------|
| Customer sends a billing enquiry | GPT classifies it as Finance, assigns High priority and generates a summary | Finance team receives a Slack notification instantly |
---

## Make Blueprint

The Make.com scenario blueprint is included for reference and can be imported after configuring the required connections.

**Blueprint Location:**

---

## Setup

To run this workflow, you'll need:

- A Make.com account
- A Gmail account
- An OpenAI API key
- A Slack workspace

### Import the Blueprint

1. Download the blueprint from the `make` folder.
2. Import it into Make.com.
3. Connect your Gmail, OpenAI, and Slack accounts.
4. Update the monitored Gmail inbox and Slack channels.
5. Enable the scenario and start receiving automated email routing.
```text
make/Intelligent Email Routing System.blueprint.json
```

---

## Repository Structure

```text
intelligent-email-routing-system/
├── assets/
│   ├── emailrouting.jpg
│   └── README.md
├── make/
│   ├── Intelligent Email Routing System.blueprint.json
│   └── README.md
├── LICENSE
└── README.md
```
> **Note:** API keys, OAuth connections, and other sensitive credentials are **not** included in the exported blueprint and must be configured after importing the scenario.
