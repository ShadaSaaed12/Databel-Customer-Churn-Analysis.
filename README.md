# Databel Telecom – Customer Churn Analysis (Power BI)

This repository contains a Data Visualization project focused on **customer churn analysis** for **Databel Telecom**.  
The goal is to transform raw telecom data into **clear, actionable insights** using interactive **Power BI dashboards**, and to help decision-makers understand **who is leaving, why they leave, and what can be done to retain them**.  [oai_citation:0‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)

---

## 📌 Project Context

This project was developed as part of the **Data Visualization** course  
at the **Faculty of Computer and Data Science, Alexandria University (2025–2026)**.  [oai_citation:1‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

- **Topic:** Customer Churn Analysis for Databel Telecom  
- **Scope:** Exploratory analysis + interactive dashboards + business interpretation  
- **Tool:** Microsoft Power BI

---

## 🎯 Objectives

The main objectives of the analysis are to:  [oai_citation:2‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

- Understand the **profile** of Databel’s customers (age, gender, geography, spending).  
- Measure and visualize **churn rate** across different customer segments.  
- Analyze how **contracts, payment methods, and customer service** affect churn.  [oai_citation:3‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  
- Explore **usage patterns** (local minutes, international minutes, data) and plan subscriptions.  [oai_citation:4‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  
- Identify the **main reasons and categories of churn**, especially competitor-driven churn.  [oai_citation:5‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  
- Provide **actionable recommendations** to reduce churn and improve retention.  [oai_citation:6‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

---

## 📊 Dashboards Overview

The Power BI report is organized into four main dashboards, each answering specific business questions.

### 1️⃣ Overview Dashboard – Customer Profile & Churn Snapshot

Focuses on the **high-level profile** of Databel’s customers:

- Total number of customers (~6,687).  [oai_citation:7‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  
- Average age (~47 years) and average monthly charges (~$53).  [oai_citation:8‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  
- Balanced gender distribution (male vs female), indicating that **gender is not a major churn driver**.  [oai_citation:9‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  
- Customers & churn rate by age:  
  - Younger customers (20–40) show **lower churn rates**.  
  - **Senior customers (65+) have the highest churn rate**, making them a high-risk segment.  [oai_citation:10‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  
- Customers by state: a map shows the **geographical distribution** of the customer base.  [oai_citation:11‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

This dashboard builds the **foundation** for deeper analysis in the next pages.  [oai_citation:12‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

---

### 2️⃣ Customer Service & Contracts Dashboard

Analyzes how **operational and contractual factors** drive churn:  [oai_citation:13‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

Key visuals:

- **Customers by Payment Method (Donut):**  
  - Direct Debit is the dominant method (~55%), while Paper Check and Credit Card are much less used.  [oai_citation:14‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

- **Customers by Group & Contract Type:**  
  - Most customers are **not in a group plan**.  
  - Group customers are **more likely** to be on one-year or two-year contracts.  [oai_citation:15‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

- **Churn Rate by Contract Period and Gender:**  
  - **Monthly contracts** have very high churn (around 47–53%).  
  - **Yearly contracts** have extremely low churn (~6%).  
  - Gender differences are small and not significant.  [oai_citation:16‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

- **Customers by Contract Type:**  
  - Month-to-Month is the most common contract type (3411 users),  
  - One-Year and Two-Year contracts have far fewer customers.  [oai_citation:17‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

- **Churn Rate by Customer Service Calls:**  
  - Churn increases sharply with the number of customer service calls.  
  - 4+ calls → churn above 97–100%, indicating severe dissatisfaction.  [oai_citation:18‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

**Main takeaway:**  
- **Contract length** and **customer service experience** are strong predictors of churn.  
- Monthly contracts and frequent service calls significantly increase the risk of customer loss.  [oai_citation:19‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

---

### 3️⃣ Usage & Plans Dashboard

Explores **usage behavior** and **plan adoption**:  [oai_citation:20‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

Key metrics (KPI cards):  [oai_citation:21‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

- 130 average international minutes.  
- 323 average local minutes.  
- 7 GB average monthly data usage.  
- ~$31 average monthly charges.

Key visuals and insights:

- **Customers by International Plan (Pie):**  
  - About **90%** of customers do **not** have an international plan.  
  - Only 10% subscribe to it.  [oai_citation:22‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

- **Customers by Unlimited Data Plan (Pie):**  
  - 67% of customers **do not** have unlimited data.  
  - Only 33% subscribe to unlimited data.  [oai_citation:23‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

- **Interactive Slicers (Contract Type, Gender, State, Demographics):**  
  - Allow dynamic filtering of churn patterns by segment.  
  - Confirm that **gender is not a major churn driver**,  
  - Show that **seniors** and **Month-to-Month customers** consistently exhibit higher churn.  [oai_citation:24‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

- **Customers by Intl Plan and Intl Active (Stacked Bar):**  
  - Many customers **without** an international plan still use international minutes.  
  - This reveals **revenue opportunities** and potential for **targeted upselling**.  [oai_citation:25‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

---

### 4️⃣ Churn Reasons & Competitive Analysis Dashboard

This is the **core dashboard** answering *why* customers leave.  [oai_citation:26‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

Highlights:  

- **Overall churn rate:**  
  - 1,796 churned customers.  
  - Churn rate = **26.86%**, considered high by telecom standards (above 20%).  [oai_citation:27‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

- **Churn by Unlimited Data Plan:**  
  - Unlimited Data: 32.11% churn.  
  - No Unlimited: 16.10% churn.  [oai_citation:28‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  
  - Suggests dissatisfaction with the value or price of the unlimited plan.  [oai_citation:29‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

- **Churned Customers by Churn Reason:**  
  - Main reasons:  
    - Competitor made a better offer.  
    - Competitor had better devices.  
    - Attitude of support team.  
    - Dissatisfaction with service.  [oai_citation:30‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

- **Churn Categories (Treemap):**  
  - Competitor: 45.51%  
  - Attitude: 16.22%  
  - Dissatisfaction: 16.17%  
  - Price: 11.13%  
  - Other: 10.80%  [oai_citation:31‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

- **Churn Rate by Demographics:**  
  - Seniors: 38.46% (highest).  
  - Others: 24.54%  
  - Under 30: 23.00%  [oai_citation:32‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

- **Monthly Charges & Churn by Customer Group:**  
  - Larger groups show **lower churn (5–9%)**.  
  - Solo customers have the highest churn (~32.85%).  [oai_citation:33‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

- **Churn Rate by State (Map):**  
  - Some regions show **high churn density**, especially where competitor presence is strong.  [oai_citation:34‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

---

## 🔍 Key Insights (Summary)

Across all dashboards, the analysis shows that:  [oai_citation:35‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

- **Competitor pressure** is the primary driver of churn (better offers, devices, data plans, and overall value).  [oai_citation:36‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  
- **Monthly contracts** and **frequent customer service calls** strongly increase churn risk.  [oai_citation:37‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  
- **Senior customers** are a high-risk segment: higher churn, more dissatisfaction, more sensitivity to offers.  [oai_citation:38‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  
- **Group/family plans** significantly reduce churn and improve stability.  [oai_citation:39‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  
- Many customers use **international or data services without suitable plans**, indicating both **revenue opportunities** and a risk of perceived overcharging.  [oai_citation:40‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

---

## ✅ Recommendations (from the Analysis)

Based on the findings, the report suggests Databel should:  [oai_citation:41‡Report of Data Visualization  Assignment01 (AutoRecovered).pdf](sediment://file_0000000023cc71f495c2881f288eb9cc)  

1. **Improve competitiveness** through better pricing, device offers, and data plans.  
2. **Enhance customer service**, especially for seniors and customers with repeated complaints.  
3. **Promote long-term and group contracts** to stabilize retention.  
4. **Target high-risk users** (e.g., seniors, monthly contracts, frequent callers) with personalized offers.  
5. **Optimize plan structures** to better match actual usage patterns.

---

## 🛠️ Tech Stack

- **Tool:** Microsoft Power BI  
- **Data Source:** Customer churn dataset for Databel Telecom  
- **Techniques:**  
  - KPI cards, bar/column charts, line charts, maps, tree maps, stacked bars  
  - Slicers for interactive segmentation  
  - Churn rate calculations and comparative analysis
