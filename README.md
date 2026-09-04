# DefectIQ — Operations Quality Analytics

> An operations analytics tool built during my internship to analyze large booking and escalation datasets and improve visibility into operational quality.

## 🚀 Live Demo

The application can be accessed through GitHub Pages.

---

## 📌 Why I Built This

During my internship, the operations team needed to analyze booking and escalation data to understand operational quality and escalation performance.

Initially, Excel was used for analysis. However, booking datasets could become very large, causing Excel to become slow or crash during processing.

There was also a need to quickly answer questions such as:

- Who handled the most escalations?
- How many escalations did each person handle?
- How long did each escalation take to resolve?
- Which branches, suppliers, hotels, or issues were contributing to operational problems?

To address this, I developed **DefectIQ**, a browser-based operations quality analytics tool.

---

## 💡 Product Solution

DefectIQ converts large booking and escalation datasets into an interactive analytical dashboard.

The workflow is:

**Upload Data → Analyze → Identify Problems → Investigate → Export Reports**

The tool automates calculations and provides faster access to operational insights compared with manually analyzing large Excel files.

---

## ✨ Key Features

### 📊 Operations Dashboard

Provides an overview of booking and escalation performance, including:

- Booking volume
- Escalation volume
- Defect ratios
- Trends over time
- Branch-level performance
- Issue-level analysis

### 👤 Escalation Performance

Helps analyze:

- Number of escalations handled by each employee
- Escalation distribution
- Resolution time
- Open and unresolved cases
- Cases exceeding the 2-day threshold

### ⏱ Resolution Threshold

The operational resolution threshold used in the analysis is:

**2 days**

DefectIQ helps identify escalations that exceed this threshold so that potential delays can be investigated.

### 🔎 Deep Analysis

Allows operational data to be analyzed across multiple dimensions such as:

- Branch
- Issue
- Supplier
- Hotel
- Employee
- Time period

### 📋 Escalation Log

Provides searchable and filterable access to escalation records.

### 📥 Export Reports

Analysis can be exported for further reporting and operational use.

---

## 🏗 How It Solves the Excel Problem

The original analysis process relied heavily on Excel.

With sufficiently large booking datasets, this became difficult because:

- Files could become very large
- Excel could become slow
- Processing could become unreliable
- Repeated analysis required manual work

DefectIQ was designed to process the uploaded data directly in the browser and provide automated calculations and visual analysis.

The application uses **streaming CSV parsing** so that large CSV files can be processed more efficiently.

---

## 🛠 Technology

- HTML
- CSS
- JavaScript
- PapaParse
- Chart.js
- SheetJS
- Browser-based data processing

---

## 📈 Product Thinking

The product was designed around a simple operational question:

> **How can managers quickly understand where operational quality problems are occurring and who is handling them?**

Instead of manually working through large spreadsheets, managers can upload the relevant data and use the application to explore:

**Volume → Defects → Escalations → Resolution Time → Root Areas**

---

## 🔐 Demo Data

This public portfolio version is intended for demonstration.

It should be used with synthetic/demo data rather than confidential operational booking or employee information.

---

## 🚀 Project Status

**Status:** Working prototype / internship project / portfolio demonstration

The application demonstrates the workflow and analytical capabilities developed to address the operational problem encountered during my internship.

---
