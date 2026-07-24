# 🤖 AI-Enabled CRM Automation Platform

> An AI-powered Lead Management & CRM Automation Platform built using **n8n**, **Google Gemini**, **Google Forms**, **Google Sheets**, **JavaScript**, and **Gmail** to automate lead capture, intelligent lead qualification, AI scoring, business objective detection, follow-up recommendations, CRM management, and customer communication.

![n8n](https://img.shields.io/badge/n8n-Automation-orange)
![Google Gemini](https://img.shields.io/badge/Google-Gemini-blue)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-yellow)
![Google Sheets](https://img.shields.io/badge/Google_Sheets-CRM-success)
![MIT License](https://img.shields.io/badge/License-MIT-green)

---

# 📖 Project Overview

Managing incoming business leads manually is repetitive, slow, and often inconsistent. Sales teams spend valuable time qualifying leads, identifying customer objectives, assigning sales representatives, writing follow-up notes, and sending acknowledgment emails.

This project transforms a traditional CRM workflow into an **AI-powered Lead Management Platform**.

Whenever a customer submits a Google Form, the workflow automatically:

- Captures the lead
- Generates a unique Lead ID
- Uses Google Gemini AI to analyze the lead
- Assigns an AI Lead Score
- Determines the customer's Business Objective
- Generates an AI Summary
- Recommends the next sales action
- Assigns the most appropriate salesperson
- Schedules follow-up dates
- Updates the CRM database
- Sends a professional HTML acknowledgment email

The result is a CRM system that not only automates data entry but also enriches every lead with AI-generated business insights.

---

# ✨ Key Features

## 🤖 AI-Powered Features

### 🧠 AI Lead Qualification

Google Gemini analyzes every incoming lead to determine its quality and sales potential.

---

### 📊 AI Lead Scoring

Each lead receives an intelligent score (0–100) based on factors such as:

- Service Requested
- Budget
- Business Type
- Lead Information Quality
- Purchase Intent

Example:

| Lead | AI Score |
|------|----------|
| Enterprise Website Project | 92 |
| Local Business SEO | 78 |
| Basic Inquiry | 41 |

---

### 🎯 Business Objective Detection

Instead of simply storing the requested service, Gemini identifies the customer's real business objective.

Examples:

- Brand Awareness
- Website Modernization
- Lead Generation
- Paid Search Growth
- Customer Acquisition

---

### 📝 AI Lead Summary

Automatically generates concise summaries for sales teams.

Example:

> John from ABC Manufacturing is interested in a new corporate website with a budget above ₹1,00,000 and is seeking modernization of their online presence.

---

### 💡 AI Follow-up Suggestions

Every lead receives personalized follow-up recommendations.

Example:

- Schedule a discovery call.
- Share website portfolio.
- Discuss branding goals.
- Prepare enterprise pricing proposal.

---

## ⚙️ Automation Features

### 📥 Real-Time Lead Capture

- Google Forms Trigger
- Instant workflow execution using n8n

---

### 🆔 Automatic Lead ID Generation

Sequential Lead IDs are generated automatically.

Examples:

- L1101
- L1102
- L1103

---

### 👨‍💼 Intelligent Salesperson Assignment

Automatically assigns leads based on requested services.

| Service | Sales Representative |
|----------|----------------------|
| Branding | Rahul Mehra |
| SEO | Amit Verma |
| Website Development | Sneha Kapoor |
| Google Ads | Priya Singh |
| Meta Ads | Dheeraj Singh |
| Social Media | Jay Verma |

---

### 📅 Automated Follow-up Scheduling

Every new lead automatically receives a follow-up date.

Rule:

> Created Date + 2 Days

---

### 🗂 CRM Database

Automatically stores:

- Lead ID
- Customer Name
- Company
- Email
- Phone Number
- Lead Source
- Requested Service
- Budget
- AI Lead Score
- Business Objective
- AI Summary
- Follow-up Suggestion
- Assigned Salesperson
- Lead Status
- Follow-up Date
- Created Date

---

### 📧 Automated HTML Email

Every customer instantly receives a professionally formatted acknowledgment email including:

- Customer Details
- Requested Service
- Assigned Representative
- Company Branding
- Contact Information

---

# 🔄 Workflow Architecture

```text
Google Form
      │
      ▼
Google Sheets Trigger
      │
      ▼
JavaScript Processing
      │
      ▼
Google Gemini AI
      │
      ├───────────────┐
      │               │
      ▼               ▼
AI Lead Score    Business Objective
      │               │
      ├───────────────┤
      ▼
AI Lead Summary
      │
      ▼
Follow-up Recommendation
      │
      ▼
Assign Salesperson
      │
      ▼
Generate Lead ID
      │
      ▼
CRM Database
      │
      ▼
HTML Email
```

---

# 🛠 Technology Stack

- n8n
- Google Gemini
- Google Forms
- Google Sheets
- Gmail
- JavaScript
- HTML Email Templates
- JSON

---

# 📈 Business Benefits

- Eliminates repetitive manual CRM work
- AI-powered lead qualification
- Intelligent lead prioritization
- Faster response time
- Consistent sales process
- Automated CRM updates
- Personalized follow-up recommendations
- Improved customer experience
- Better lead management
- Reduced human error

---

# 📂 Repository Structure

```text
AI-Enabled-CRM-Automation/

│
├── workflow/
│   └── AI CRM Automation.json
│
├── screenshots/
│   ├── workflow.png
│   ├── google-form.png
│   ├── crm-sheet.png
│   ├── ai-score.png
│   ├── ai-summary.png
│   ├── business-objective.png
│   ├── followup-suggestion.png
│   ├── gemini-node.png
│   └── html-email.png
│
├── README.md
└── LICENSE
```

---

# 📸 Screenshots

## Workflow

![Workflow](screenshots/workflow.png)

## Google Form

![Google Form](screenshots/google-form.png)

## AI Lead Score

![AI Score](screenshots/ai-score.png)

## Business Objective

![Business Objective](screenshots/business-objective.png)

## AI Summary

![AI Summary](screenshots/ai-summary.png)

## CRM Database

![CRM Database](screenshots/crm-sheet.png)

## HTML Email

![Email](screenshots/html-email.png)

---

# 🚀 Future Enhancements

- AI Email Personalization
- WhatsApp Integration
- PostgreSQL Backend
- CRM Web Dashboard
- Power BI Analytics
- REST API
- Role-Based Authentication
- Multi-Agent AI Sales Assistant
- Voice AI Sales Agent

---

# 💼 Skills Demonstrated

- AI Workflow Automation
- n8n Automation
- Google Gemini Integration
- Prompt Engineering
- Business Process Automation
- CRM Design
- JavaScript
- Google Workspace Automation
- API Integration
- AI Lead Qualification
- Workflow Design
- HTML Email Automation
- Low-Code Development
- System Design

---

# 👨‍💻 About

This project demonstrates how Large Language Models can be integrated into business workflows to automate lead management, improve CRM quality, and assist sales teams with intelligent decision-making.

It showcases practical applications of **Generative AI**, **workflow automation**, and **business process optimization** using modern AI tools.

---

# 📄 License

This project is licensed under the **MIT License**.
