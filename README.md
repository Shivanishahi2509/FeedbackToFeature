# FeedbackToFeature
AI-powered SaaS feedback analyzer that classifies customer reviews and auto-generates Jira tickets. Built with Airtable, Pipedream, OpenRouter, Power BI and Notion.

## Why I Built This
Enterprise SaaS platforms receive hundreds of feedback entries across platforms like G2, Reddit, and community forums. However:
 Churn signals are buried in unstructured reviews
 Feature requests go unprioritized
 PMs lack a real-time, actionable view of customer voice
Or 
Product Managers constantly ask:  
“What are customers actually struggling with and what should we build next?”
But with hundreds of G2 reviews, emails, Reddit threads, and tickets... important insights get lost.
So I built **FeedbackToFeature** a solo project that helps PMs **go from scattered SaaS feedback to structured, prioritized action**.

**<h3>Refer the uploaded report for my project.</h3>** <br>

## 🔍 What It Does

Collects 100+ real Salesforce reviews from G2  
Uses OpenRouter (LLM API) to classify each one by:
- **Sentiment**
- **Intent** (Churn, Feature Request, Praise)
- **Urgency**
- **Business Impact (1–5)**
Auto-updates Airtable records  
Creates Jira issues for high-risk or urgent feedback  
Visualizes trends in a live Power BI dashboard
Documents UX personas to connect insights to real users
---

## 🛠️ Tech Stack (100% Free Tools)

| Goal               | Tool                      |
|--------------------|---------------------------|
| Store Feedback     | Airtable                  |
| Automate Workflow  | Pipedream                 |
| AI Classification  | OpenRouter API            |
| Visualization      | Power BI                  |
| Issue Tracker      | Jira Cloud                |
| Documentation      | Notion                    |

---

## 📊 Dashboard Highlights

- **Sentiment Pie Chart**  
- **Intent Breakdown Bar Chart**  
- **Table of High Impact Feedback (Score ≥ 4)**  
- **KPI Cards**: Urgency Volume, Churn %, Avg. Impact

---

## 📁 Example Jira Tickets Created

| Ticket Key | Summary |
|------------|---------|
| SCFT-17    | Salesforce Sales Cloud is overpriced and prevents data portability |
| SCFT-18    | Insufficient refund policy, terrible customer service |
| SCFT-22    | UI/UX issues and complicated implementation |

Each of these came directly from G2 feedback and was tagged by the AI classifier.

---

## 👤 UX Personas

1. **Enterprise IT Admin** – SSO issues, UI friction, urgent complaints  
2. **Startup CTO** – Feature walls, pricing confusion, churn risk

Mapped in Notion, connected to real feedback patterns.

---

## 👋 Let’s Connect

If you work in product, CX, or design — I’d love your feedback or thoughts.  
Built this alone, but open to making it better with the community!
By Shivani Shahi (https://www.linkedin.com/in/shivani-shahi-250b6a1b5/)

