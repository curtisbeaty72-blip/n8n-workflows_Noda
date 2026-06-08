# AI-Powered Audit Document Tracking System
**Week 10 Capstone | Moringa School Workflow Automation**
Submitted by: Leilah Kokoyo and Dennis Paul | June 2026

---

## Project Overview
An AI-powered n8n workflow that automatically identifies overdue audit documents, classifies risk levels, drafts tone-appropriate client emails, routes them through a human approval gate, and logs every outcome — all triggered daily at 08:00 with no manual intervention.

---

## Repository Contents

| File | Description |
|------|-------------|
| `Audit Tracker_Dennis Paul Audit Firm.json` | Main workflow JSON |
| `Audit Workflow Error Handler (1).json` | Error handler workflow JSON |
| `Week10_AI_Audit_Tracker_Leilah_Kokoyo_Den...` | Full project documentation (Word) |
| `AUDIT TRACKER_ PPT.pptx` | Presentation slide deck |
| `LEILAH KOKOYO AND DENNIS PAUL GOOGLE...` | Google Sheets execution evidence |

---

## Tools and Integrations
- **n8n Cloud** — workflow orchestration
- **Google Sheets** — data source and output store
- **Gmail** — approval requests and client emails
- **Mistral AI via OpenRouter** — AI Classifier and Email Drafter agents
- **GitHub** — version control and submission

---

## How to Run
1. Import both JSON files into n8n
2. Configure credentials for Google Sheets, Gmail, and OpenRouter
3. Set the Error Handler as the Error Workflow in main workflow Settings
4. Activate both workflows
5. The workflow fires automatically every day at 08:00

---

## Documentation
Full setup instructions, architecture, node configurations, and troubleshooting are in the Word document above.
