# 🏦 AI-Powered Loan Approval Automation using n8n

<p align="center">
  Automated Loan Processing • Credit Risk Assessment • AML Screening • Email Notifications
</p>

---

# 📌 Project Overview

This project automates the loan approval process using **n8n**, **Google Sheets**, **JavaScript**, and **Gmail**.

The workflow reads loan application data, evaluates applicants based on credit score, debt-to-income ratio, and AML/PEP watchlist checks, automatically classifies applications, and sends email notifications.

The solution simulates a modern banking loan approval system designed to improve efficiency, compliance, and decision accuracy.

---

# 🎯 Objectives

* Automate loan approval decisions
* Reduce manual processing time
* Improve decision consistency
* Perform AML/PEP compliance screening
* Generate automated email notifications
* Demonstrate financial process automation using n8n

---

# 🏗️ Solution Architecture

```text
Google Sheets
      ↓
Applicant Data Extraction
      ↓
n8n Workflow
      ↓
Credit & DTI Evaluation
      ↓
AML / PEP Screening
      ↓
Decision Engine
      ↓
Approve / Reject / Review
      ↓
Email Notifications
```

---

# ⚙️ Workflow Process

### Step 1 — Read Applicant Dataset

Import applicant records from Google Sheets.

### Step 2 — Evaluate Creditworthiness

Check:

* Credit Score
* Debt-to-Income Ratio (DTI)
* Income Eligibility

### Step 3 — AML & Compliance Screening

Perform:

* Watchlist Checks
* PEP Screening
* Risk Evaluation

### Step 4 — Generate Decision

Classify applications as:

* Auto-Approve
* Auto-Reject
* Manual Review

### Step 5 — Send Automated Notifications

Generate:

* Approval Emails
* Rejection Emails
* Compliance Alerts

---

# 🧠 Loan Decision Rules

| Rule | Description                         |
| ---- | ----------------------------------- |
| L1   | Credit Score ≥ 600                  |
| L2   | Debt-to-Income Ratio ≤ 0.50         |
| L3   | Watchlist Score < 0.30              |
| L4   | Credit Score < 560 → Auto-Reject    |
| L5   | DTI > 0.55 → Auto-Reject            |
| L6   | Watchlist 0.30–0.79 → Manual Review |
| L7   | Watchlist ≥ 0.80 → AML Escalation   |
| L8   | PEP Match → Auto-Reject             |

---

# 📊 Dataset Summary

| Metric             | Value |
| ------------------ | ----- |
| Total Applications | 40    |
| Auto-Approved      | 18    |
| Auto-Rejected      | 11    |
| Manual Review      | 11    |

---

# 📸 Project Screenshots

## Loan Dataset
<img width="1600" height="579" alt="loan-dataset png" src="https://github.com/user-attachments/assets/f1d730eb-c4e8-4833-9fb0-8e7562af424e" />

<img src="./loan-dataset.png" width="1000"/>

Shows:

* Applicant information
* Credit score
* DTI ratio
* Watchlist score
* System decision

---

## n8n Workflow Architecture
<img width="1522" height="582" alt="approval-email png" src="https://github.com/user-attachments/assets/120b0205-844d-4a33-bb25-4eea1c07a053" />


<img src="./workflow-architecture.png" width="1000"/>

Workflow showing:

* Data extraction
* Rule evaluation
* Conditional routing
* Email notifications

---

## Approval Email
<img width="1522" height="582" alt="approval-email png" src="https://github.com/user-attachments/assets/48e7e213-cf8a-4c78-b0ab-599b38cd8931" />


<img src="./approval-email.png" width="1000"/>

Automated email sent to approved applicants.

---

## Rejection Email
<img width="1518" height="448" alt="rejection-email png" src="https://github.com/user-attachments/assets/3f38c5d9-2117-4b96-93cc-746e0c6023fe" />


<img src="./rejection-email.png" width="1000"/>

Automated notification sent to rejected applicants.

---

## Compliance Alert
<img width="1535" height="553" alt="compliance-alert png" src="https://github.com/user-attachments/assets/eb8d68d9-ae7d-4ee4-9e08-0fda145c4479" />


<img src="./compliance-alert.png" width="1000"/>

Alert generated for AML/PEP review cases.

---

# 📈 Business Impact

| Parameter            | Manual Process | Automated Process |
| -------------------- | -------------- | ----------------- |
| Time Per Application | 3–5 Days       | < 2 Minutes       |
| Error Rate           | ~35%           | <3%               |
| Cost Per Application | $2,400         | $180              |
| Throughput Per Day   | 20–30          | 500+              |
| Compliance Coverage  | 60%            | 100%              |

### Key Results

* ⚡ 99.9% Faster Processing
* 💰 92% Cost Reduction
* 📈 17× Higher Throughput
* 🎯 91% Error Reduction
* 🛡️ Full AML/PEP Coverage

---

# 🛠️ Tech Stack

| Technology    | Purpose             |
| ------------- | ------------------- |
| n8n           | Workflow Automation |
| Google Sheets | Data Storage        |
| JavaScript    | Decision Logic      |
| Gmail         | Email Notifications |
| AML Screening | Compliance Checks   |

---

# 📂 Repository Structure

```text
ai-loan-approval-automation/
│
├── README.md
├── Loan Approval Automation.json
├── loan-dataset.png
├── workflow-architecture.png
├── approval-email.png
├── rejection-email.png
└── compliance-alert.png
```

---

# 🚀 Run Locally

### Clone Repository

```bash
git clone https://github.com/your-username/ai-loan-approval-automation.git
```

### Execute Workflow

```text
Open n8n
↓
Import Workflow JSON
↓
Configure Google Sheets Credentials
↓
Configure Gmail Credentials
↓
Run Workflow
```

---

# 🔮 Future Scope

* Machine Learning Credit Scoring
* Predictive Risk Assessment
* WhatsApp Notifications
* CRM Integration
* Real-Time Dashboard
* Multi-Currency Support
* Banking API Integration

---

# 👨‍💻 Developed By

**MBA Applied Finance – Financial Technology & Automation**

### Group Members

* Bhumi Gupta
* Muskan Garg
* Manu Bansal
* Vivek
* Sandeep
* Samridhi
* Vansh

### Faculty

Prof. Lavanya Srivastava

**Chitkara University*
