# 📊 Brand Protection & IP Risk Analysis Dashboard

> An end-to-end Power BI solution designed to analyze platform activity, geographical risk, and intellectual property violations across global marketplaces.

---

## 📌 Overview

This project presents an interactive Power BI dashboard developed to evaluate brand protection performance and identify patterns in IP violations and enforcement activity. The solution integrates platform data, geographical distribution, seller behavior, and infringement characteristics to generate actionable insights.

The dataset was AI-generated and intentionally unstructured, simulating real-world inconsistencies. It was cleaned and transformed using Python before being used for reporting.

The dashboard enables stakeholders to:

- Monitor listing activity across platforms  
- Identify high-risk countries and regions  
- Analyze IP violation patterns  
- Evaluate enforcement effectiveness  
- Understand revenue exposure from infringements  

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

- Standardized price and currency formats  
- Converted textual values (e.g., 1.2K, 10+, RFQ) into numeric  
- Handled missing values  
- Removed duplicate records (URLs)  
- Cleaned categorical inconsistencies (IP Type, Infringement Type)  
- Parsed and formatted date fields  

### 🔹 Data Adjustment (Excel)

- Improved distribution realism (data was initially too uniform)  
- Prepared dataset for better analytical output  

### 🔹 Data Modeling (Power BI)

- Created DAX measures  
- Designed KPIs for performance and risk  
- Built multi-page dashboard  

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

### 2. Platform Analysis

#### Key Metrics
- Listings by Platform  
- Top Platform Contribution  
- Platform Distribution  

#### Business Value
- Identifies dominant platforms  
- Detects fragmented marketplace behavior  

---

### 3. Geographical Analysis

#### Key Metrics
- Listings by Country  
- High-Risk Countries  
- Revenue by Region  

#### Business Value
- Highlights geographical risk concentration  
- Supports regional decision-making  

---

### 4. IP Analysis

#### Key Metrics
- Top IP Type Violated  
- Most Common Infringement Type  
- Revenue Impact by IP Type  

#### Business Value
- Identifies vulnerable IP categories  
- Highlights infringement patterns  

---

## 🧠 Data Modeling & Analytics

Key measures created using DAX:

- Total Listings  
- Compliance Rate (%)  
- Revenue Exposure  
- Top Contribution Metrics  
- Avg Revenue per Listing  

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

_Add screenshots here_

---

## 📈 Key Insights

- Listings are highly fragmented across platforms  
- No single platform dominates significantly  
- Certain countries contribute more to overall risk  
- Trademark violations drive higher revenue exposure  
- Counterfeit is the most frequent infringement type  

---

## 💼 Business Impact

- Improves visibility into platform and regional risks  
- Enables faster identification of high-risk areas  
- Supports data-driven enforcement decisions  

---

## 🚀 How to Use

1. Download the `.pbix` file  
2. Open in Power BI Desktop  
3. Use filters to explore insights  

---

## 👤 Author

Sourabh Sharma  
Data Analyst | Power BI | SQL | Python  

---

## ⭐ If you found this useful

Give it a ⭐ on GitHub!
