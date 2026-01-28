# n8n Workflow Templates

This repository contains a curated collection of **reusable n8n workflow templates** researched and organized for **real-world company automation use cases**.  
These workflows focus on improving efficiency across **recruitment, sales, email management, document processing, and internal operations**.

Each template is provided as a JSON file that can be directly imported into n8n and customized as per business requirements.

---

## 📌 Key Objectives of This Repository

- Reduce manual work through automation  
- Demonstrate practical AI and workflow use cases  
- Provide ready-to-use templates for rapid adoption  
- Serve as a centralized automation library for the company  

---

## 📂 Workflow Templates Included

---

### 1. Gmail Campaign Sender – Bulk Send & Follow-up  
**File:** `gmail_campaign_sender.json`

**Description:**  
Automates multi-step email campaigns using Gmail and Google Sheets. The workflow sends follow-up emails only if recipients do not reply, helping teams avoid manual follow-ups.

**Business Value:**  
- Sales outreach automation  
- Recruitment communication  
- Saves time on repetitive email follow-ups  

---

### 2. AI Task Manager for Google Sheets  
**File:** `ai_task_manager_sheets.json`

**Description:**  
Allows users to create project tasks using natural language through a chat interface. Tasks are automatically structured and stored in Google Sheets with proper status tracking.

**Business Value:**  
- Simplifies task creation  
- Reduces dependency on manual sheet updates  
- Improves project and task tracking  

---

### 3. AI Resume Screening & Evaluation  
**File:** `ai_resume_screening.json`

**Description:**  
Automates the resume screening process using AI by analyzing candidate details and generating structured evaluations stored in Google Sheets.

**Business Value:**  
- Faster candidate shortlisting  
- Reduces manual resume review  
- Improves HR efficiency  

> Note: Full execution may require paid AI or Google Cloud credentials.

---

### 4. AI Lead Qualification in Google Sheets  
**File:** `ai_lead_qualification.json`

**Description:**  
Uses AI to analyze and qualify leads stored in Google Sheets, helping sales teams prioritize high-quality prospects.

**Business Value:**  
- Better sales focus  
- Faster lead response time  
- Improved conversion efficiency  

---

### 5. AI Gmail Auto Labeling  
**File:** `ai_gmail_auto_label.json`

**Description:**  
Automatically classifies incoming Gmail messages using AI and applies appropriate labels such as Inquiry, Partnership, or Support.

**Business Value:**  
- Organized inbox management  
- Faster email triaging  
- Useful for sales, HR, and support teams  

---

### 6. AI Applicant Screening & HR Notification  
**File:** `ai_applicant_screening.json`

**Description:**  
Screens job applicants using AI, notifies HR about qualified candidates, and stores applicant data in Google Sheets.

**Business Value:**  
- Automated recruitment pipeline  
- Centralized applicant data  
- Faster HR decision-making  

---

### 7. CV Resume PDF Parsing with Vision AI  
**File:** `ai_cv_pdf_parser.json`

**Description:**  
Processes candidate resume PDFs by converting them into images and analyzing them using multimodal vision AI models.

**Business Value:**  
- Advanced resume analysis  
- Handles PDF-based resumes  
- Useful for large-scale recruitment  

> Note: Requires AI vision model support and sufficient API quota.

---

### 8. GitHub API Documentation Chatbot (RAG-Based)  
**File:** `ai_github_docs_chatbot.json`

**Description:**  
A Retrieval-Augmented Generation (RAG) chatbot that allows users to query GitHub API documentation and receive accurate, context-aware responses.

**Business Value:**  
- Internal developer support  
- Faster onboarding for engineers  
- Reduces dependency on manual documentation search  

---

## ⚙️ How to Use These Templates

1. Open n8n  
2. Click **Import Workflow**  
3. Upload the required `.json` file  
4. Configure credentials (Google, Gmail, AI APIs, etc.)  
5. Customize nodes based on company requirements  

---

## ⚠️ Notes & Limitations

- Some workflows require **paid AI APIs or cloud services** for full functionality  
- Templates are meant to be **extended and customized**, not used as-is in production  
- Rate limits may apply when using AI models  

---

## 🏢 Intended Use

These templates are suitable for:
- Recruitment automation  
- Sales & lead management  
- Email handling & communication  
- AI-driven document processing  
- Internal operations and productivity  

---

## 👤 Maintained By Johil 

Automation & AI Workflow Research  
(Internship Task – n8n Workflow Templates)

---


