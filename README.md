# Intelligent Email Routing System

![Make.com](https://img.shields.io/badge/Make.com-Automation-6D00CC?style=for-the-badge)
![OpenAI](https://img.shields.io/badge/OpenAI-GPT--4.1_Mini-10A37F?style=for-the-badge)
![Gmail](https://img.shields.io/badge/Gmail-API-EA4335?style=for-the-badge)
![Slack](https://img.shields.io/badge/Slack-API-4A154B?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-blue?style=for-the-badge)

An AI-powered email routing system that automatically classifies, prioritises, and routes incoming emails to the appropriate department while generating intelligent customer acknowledgement responses.

## Tech Stack

- Make.com
- Gmail API
- OpenAI GPT-4.1 Mini
- Slack API

---

## The Challenge

Businesses often receive sales enquiries, support requests, HR questions, and finance-related emails through a shared inbox. Manually reviewing, prioritising, and forwarding every email is repetitive, slows response times, and increases the risk of requests reaching the wrong team.

---

## The Solution

This workflow monitors a Gmail inbox for new emails, extracts the relevant information, and uses GPT-4.1 Mini to classify each message into the appropriate department. It assigns a priority level, generates a concise summary, routes the email to the correct Slack channel, and automatically drafts acknowledgement emails for Customer Support enquiries.

---

## Key Capabilities

- 📧 Monitors a Gmail inbox for new emails.
- 🤖 Classifies emails using GPT-4.1 Mini.
- 🚦 Assigns High, Medium, or Low priority.
- 📝 Generates concise AI summaries.
- 💬 Routes emails to department-specific Slack channels.
- ✉️ Drafts professional acknowledgement emails for Customer Support.
- ⏱️ Delays automated responses to create a more natural customer experience.
- 🛡️ Uses structured JSON outputs for reliable downstream automation.

---

## Workflow

![Workflow](assets/emailrouting.jpg)

*Complete Make.com workflow demonstrating AI-powered email classification, intelligent routing, Slack notifications, and automated customer acknowledgements.*

---

## Business Impact

- Eliminates manual email triage and routing.
- Ensures enquiries reach the correct team within seconds.
- Improves response times through intelligent prioritisation.
- Provides immediate acknowledgement for customer support requests.
- Scales efficiently without increasing administrative workload.

---

## Example Flow

| Incoming Email | AI Processing | Outcome |
|----------------|--------------|---------|
| Customer sends a billing enquiry | GPT classifies it as **Finance**, assigns **High** priority, and generates a concise summary | The Finance team receives an instant Slack notification with the email summary and priority level. |

---

## Make Blueprint

The exported Make.com scenario blueprint is included in this repository and can be imported after configuring the required API connections and credentials.

**Blueprint Location**

```text
make/Intelligent Email Routing System.blueprint.json
```

---

## Setup

### Requirements

- Make.com account
- Gmail account
- OpenAI API key
- Slack workspace

### Import the Blueprint

1. Download the blueprint from the `make` folder.
2. Import it into Make.com.
3. Connect your Gmail, OpenAI, and Slack accounts.
4. Update the monitored Gmail inbox and Slack channels.
5. Enable the scenario.

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
