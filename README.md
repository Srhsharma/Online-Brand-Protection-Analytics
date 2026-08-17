# 📊 Brand Protection & IP Risk Analysis Dashboard
![Python](https://img.shields.io/badge/Python-Data%20Cleaning-blue)
![Power BI](https://img.shields.io/badge/PowerBI-Dashboard-yellow)

> An end-to-end data analysis solution focused on preprocessing, transforming, and analyzing marketplace data to uncover platform, geographical, and IP risk insights.

---

## 📌 Overview

This project presents an interactive Power BI dashboard developed to evaluate brand protection performance and identify patterns in IP violations and enforcement activity. The solution integrates platform data, geographical distribution, seller behavior, and infringement characteristics to generate actionable insights.

The dataset was designed to simulate real-world conditions, containing intentional inconsistencies and irregularities. It was cleaned, standardized, and transformed using Python to ensure accuracy before being used for analysis and reporting.

The dashboard enables stakeholders to:

- Monitor listing activity across platforms  
- Identify high-risk countries and regions  
- Analyze IP violation patterns  
- Evaluate enforcement effectiveness  
- Understand revenue exposure from infringements  

---
## ⚠️ Key Insights

- China and India are the leading contributors to total listings volume  
- Platform distribution is highly fragmented, indicating decentralized risk  
- Design-related infringements drive the highest revenue exposure  
- APAC dominates both listings volume and overall risk exposure

---

## ⚠️ Business Problem

Online marketplaces face significant challenges due to:

- Counterfeit products  
- Trademark misuse  
- Design and copyright violations  

Raw data is often inconsistent and unstructured, making it difficult to derive insights.

This project addresses that challenge by cleaning, structuring, and visualizing the data into a centralized analytical dashboard.

---

## 🔄 Data Preparation & Transformation

### 🔹 Data Cleaning (Python – VS Code / Jupyter)

- Standardized price and currency formats across multiple sources  
- Converted unstructured textual values (e.g., 1.2K, 10+, RFQ) into numerical format for analysis  
- Handled missing values and ensured data completeness  
- Removed duplicate records to maintain data integrity  
- Standardized categorical fields (IP Type, Infringement Type, Status) for consistency  
- Parsed and formatted date fields for time-based analysis  
- Ensured consistency across multiple fields to improve analytical accuracy

### 🔹 Data Adjustment (Excel)

- Refined data distribution to reduce uniformity and improve analytical realism  
- Applied final validations and adjustments to ensure data readiness for reporting  

### 🔹 Data Modeling (Power BI)

- Developed DAX measures for key metrics including listings, revenue exposure, and compliance  
- Designed KPIs to evaluate performance, risk, and contribution across dimensions  
- Built a structured multi-page dashboard for platform, geographical, and IP analysis

---

## 📊 Dashboard Structure

### 1. Overview

#### Key Metrics
- Total Listings  
- Total Transactions  
- Revenue Exposure  
- Avg Price  
- Monthly Trends  

#### Business Value
- Provides overall performance snapshot  
- Tracks trends over time  

---

### 2. IP Analysis

#### Key Metrics
- Top IP Type Violated  
- Most Common Infringement Type  
- Revenue Impact by IP Type  

#### Business Value
- Identifies vulnerable IP categories  
- Highlights infringement patterns  

---

### 3. Platform Analysis

#### Key Metrics
- Listings by Platform  
- Top Platform Contribution  
- Platform Distribution  

#### Business Value
- Identifies dominant platforms  
- Detects fragmented marketplace behavior  

---

### 4. Geographical Analysis

#### Key Metrics
- Listings by Country  
- High-Risk Countries  
- Revenue by Region  

#### Business Value
- Highlights geographical risk concentration  
- Supports regional decision-making  

---


## 🧠 Data Modeling & Analytics

### 📐 Key Measures (DAX)

- Total Listings  
- Compliance Rate (%)  
- Revenue Exposure  
- Avg Revenue per Listing  
- Top 3 Contribution (Platform / Country)  
- High Risk Entity (Country / Platform based on listings)

---

## 🛠️ Technology Stack

| Technology | Purpose |
|------------|--------|
| Python (Pandas) | Data Cleaning |
| VS Code / Jupyter | Processing |
| Excel | Data Adjustment |
| Power BI | Dashboard |
| DAX | Calculations |

---

## 📷 Dashboard Preview
### Overview
<img width="1272" height="713" alt="image" src="https://github.com/user-attachments/assets/329d980c-d777-4210-8f31-a4b4f72e2b0c" />

### IP Analysis
<img width="1269" height="715" alt="image" src="https://github.com/user-attachments/assets/b022b066-b044-4bc2-9375-541ddc389408" />

### Platform Analysis
<img width="1267" height="715" alt="image" src="https://github.com/user-attachments/assets/575048e5-747e-4a63-bede-eb13a983d669" />

### Geographical Analysis
<img width="1271" height="713" alt="image" src="https://github.com/user-attachments/assets/05d9abdb-7805-4ec5-ac8e-941db3dd52ef" />

---

## 💼 Business Impact

- Improves visibility into platform-level and regional risk patterns  
- Enables faster identification of high-risk countries and IP categories  
- Supports data-driven prioritization of enforcement actions  

---

## 🚀 How to Use

1. Download the `.pbix` file  
2. Open in Power BI Desktop  
3. Use slicers (Year, Platform, Country, IP Type) to explore insights 
---

## 👤 Author

Sourabh Sharma  
Data Analyst | Power BI | SQL | Python  

---

## ⭐ If you found this useful

Give it a ⭐ on GitHub!
