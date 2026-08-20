# ⚡ Cyberpunk Analytics Dashboard with AI Action Agent

A futuristic **AI-powered Business Intelligence Dashboard** that combines real-time analytics, conversational AI, and automated business workflows.

This project transforms traditional dashboards into an intelligent command center where users can ask questions, update business data, trigger actions, and automate communication using natural language.

Powered by:

- 🤖 n8n AI Agent
- 🧠 Groq Large Language Model
- 📊 Google Sheets
- 📧 Gmail Automation
- 📈 Real-Time Data Visualization

---

# 🚀 Overview

The Cyberpunk Analytics Dashboard is an AI-driven analytics platform that allows users to interact with business data conversationally.

Instead of manually managing spreadsheets and reports, users can simply tell the AI Assistant what they need.

Example:

```
Increase Kashif Khan budget by 5000 rupees
```

The AI Agent will:

1. Understand the request
2. Find the correct customer record
3. Update Google Sheets
4. Send notification emails if required
5. Confirm completion

---

# 🏗️ Architecture

```
                     User Request
                           |
                           v
                  AI Assistant Interface
                           |
                           v
                     n8n AI Agent
                           |
        +------------------+------------------+
        |                  |                  |
        v                  v                  v

   Groq Chat Model   Google Sheets        Gmail API

        |                  |                  |

        v                  v                  v

  AI Reasoning       Data Updates      Email Notifications

                           |
                           v

             Real-Time Analytics Dashboard
```

---

# 🧩 Technology Stack

| Layer | Technology |
|---|---|
| Workflow Automation | n8n |
| AI Model | Groq Chat Model |
| AI Framework | n8n AI Agent |
| Data Source | Google Sheets |
| Email Automation | Gmail API |
| Frontend Dashboard | Custom Web Dashboard |
| Analytics | Business Intelligence Charts |

---

# 🤖 AI Agent Capabilities

The AI Assistant is capable of understanding business commands and executing real-world actions.

## 1. Data Management

Users can update business records using natural language.

Example:

```
Add 5000 rupees budget for Ahsan Durrani
```

Workflow:

```
User Command
      |
      v
AI Intent Understanding
      |
      v
Find Customer Record
      |
      v
Update Google Sheet
      |
      v
Return Confirmation
```

---

## 2. Automated Email Communication

Example:

```
Send email to Junaid Murad informing him that his budget has increased
```

The AI Agent automatically:

- Finds customer information
- Creates email content
- Sends email through Gmail
- Returns execution status

---

## 3. Business Data Querying

Users can ask:

```
Who generated the highest revenue?
```

```
Show all delivered projects
```

```
Which client has the highest budget?
```

The AI retrieves and analyzes business data automatically.

---

# 📊 Dashboard Features

## Executive Overview

The dashboard provides real-time business metrics:

- Total Clients
- Total Headshots
- Total Revenue
- Average Client Value
- Project Status

---

## Revenue Analytics

Visual insights:

- Revenue by Client
- Monthly Performance Trends
- Customer Contribution
- Earnings Analysis

---

## Project Tracking

Monitor:

- Delivered Projects
- Active Projects
- Pending Work
- Completion Status

---

## Client Records

Includes:

- Customer Name
- Project Details
- Budget Information
- Email Records
- Status Tracking

---

# 🔄 Workflow Execution

## Step 1 — User Sends Command

Example:

```
Increase Kashif Khan budget by 5000
```

---

## Step 2 — AI Processing

Groq LLM analyzes:

- User intention
- Required action
- Target data

---

## Step 3 — Tool Selection

The n8n AI Agent selects required tools:

Available tools:

```
Google Sheets
Gmail
Data Retrieval
```

---

## Step 4 — Action Execution

Example:

Before:

```
Client:
Kashif Khan

Budget:
3999
```

After:

```
Client:
Kashif Khan

Budget:
8999
```

---

## Step 5 — Response

The AI Assistant confirms:

```
Budget updated successfully.
Notification email sent.
```

---

# 🧠 AI Agent Flow

```
                 User Message

                       |

                       v

                 AI Agent

                       |

              Understand Request

                       |

                       v

              Select Required Tool

                       |

          +------------+------------+

          |                         |

          v                         v

   Google Sheets               Gmail

          |                         |

          v                         v

   Update Records        Send Notification

          |

          v

      Final Response
```

---

# ✨ Key Features

## Conversational Analytics

No need to manually open dashboards.

Ask:

```
Show highest revenue client
```

```
Update customer budget
```

```
Send customer notification
```

---

## Action Taking AI

Unlike traditional dashboards:

Traditional BI:

```
View Data
    |
Human Decision
    |
Manual Action
```

AI Powered BI:

```
Ask AI
    |
AI Understands
    |
AI Executes
    |
Business Outcome
```

---

## Real-Time Intelligence

Provides:

- Live business insights
- Automated updates
- Faster decision making
- Reduced manual operations

---

# 📌 Business Use Cases

## Sales Management

- Customer budget updates
- Revenue tracking
- Sales analysis

---

## Project Management

- Project status monitoring
- Delivery tracking
- Client management

---

## Customer Communication

Automated:

- Email notifications
- Customer updates
- Business communication

---

## Executive Intelligence

Management can ask:

```
What is our top revenue client?
```

```
How many projects are completed?
```

```
Show business performance.
```

---

# 🔐 Security Recommendations

Production deployment should include:

- Secure n8n credentials
- OAuth authentication
- Google API permission control
- Workflow access restrictions
- Execution monitoring
- Audit logging

---

# 🚀 Future Enhancements

Planned improvements:

- Voice-enabled AI assistant
- Database integration
- Predictive analytics
- AI-generated reports
- Slack / Microsoft Teams integration
- Multi-agent collaboration
- Role-based AI assistants

---

# 🌟 The Future of Business Intelligence

Traditional Analytics:

```
Collect Data
      |
Create Reports
      |
Human Decision
      |
Manual Action
```

AI Analytics:

```
Collect Data
      |
AI Understands
      |
AI Decides
      |
AI Executes
      |
Business Growth
```

The future of analytics is not only understanding data — it is taking intelligent actions automatically.

---

# 📸 Project Stack

Built using:

**n8n + Groq AI + Google Sheets + Gmail + AI Agent + Business Intelligence Dashboard**

---

## Tags

```
#AI
#Automation
#n8n
#Groq
#BusinessIntelligence
#DataVisualization
#GoogleSheets
#AI-Agent
#WorkflowAutomation
```
