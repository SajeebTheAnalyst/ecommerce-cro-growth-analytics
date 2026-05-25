# E-Commerce Growth Analytics & Conversion Rate Optimization (CRO) Case Study

## 📌 Project Overview
This repository contains an end-to-end data analytics and growth optimization project focused on identifying revenue leakage, analyzing user friction points, and optimizing conversion rates for an e-commerce platform. 

By extracting behavioral trends from raw user session data, I diagnosed why high-traffic categories were underperforming and developed a prioritized 60-day strategic roadmap designed to maximize business ROI using professional frameworks like the **Pareto Principle (80/20)** and **ICE Scoring**.

---

## 🛠️ Tech Stack & Core Competencies
- **Data Engineering & EDA:** Python (`pandas`, `numpy`, `matplotlib`, `seaborn`), SQL
- **Frameworks:** Conversion Funnel Analysis, Pareto (80/20) Framework, ICE Task Prioritization Matrix
- **Domain Focus:** Growth Hacking, Conversion Rate Optimization (CRO), Digital Product Analytics

---

## 📊 Core Insights & Analytical Breakdown

### 1. The "Vital Few" (Pareto Analysis)
* **The Finding:** Applied the 80/20 rule to platform revenue streams and discovered that the vast majority of overall revenue is driven by a small, core group of categories (primarily Books & Electronics).
* **Business Impact:** This allows executive management to shield core revenue and stop over-allocating marketing budgets to low-margin or low-converting products.

### 2. Identifying Revenue Leakage & Bounce Rates
* **The Finding:** Isolated a massive systemic drop-off in the **Baby Category**, which suffered from an alarming **77.41% bounce rate**. 
* **Business Impact:** Even though marketing spent money to acquire this traffic, 77% of users left the site immediately without clicking anything. Fixing this localized layout/copy gap is significantly cheaper than buying new ads.

### 3. Funnel Analysis & User Friction
* **The Finding:** Mapped the complete user journey from *Landing Page ➔ Product Detail View ➔ Cart ➔ Checkout*. 
* **Business Impact:** Pinpointed exactly where users dropped out of the pipeline, identifying structural check-out bugs and instances of behavioral friction (like repetitive clicking/user confusion).

---

## 🚀 The Solution: 60-Day Strategic Roadmap
Rather than attempting to rebuild the entire platform simultaneously, I utilized the **ICE Framework (Impact, Confidence, Ease)** to prioritize rapid, high-yield implementations:

* **Priority #1: CTA Copy & Microcopy Optimization**
  * **Score:** 8.0/10 (High Impact, High Confidence, High Ease)
  * **Action:** Redesigned action buttons and product headlines to utilize psychological triggers and urgency.
* **Testing Protocol:** Formulated clear statistical A/B testing parameters to ensure every design iteration is structurally proven to lift the platform's average **0.52% conversion rate** before a full deployment.

---

## 📂 Project Directory Structure
```text
├── data/
│   └── dashboard_data.csv                 # Cleaned dataset used for final modeling
├── notebooks/
│   ├── Sajeeb_Data_Cleaning.ipynb         # Data parsing, missing value handling, and pipeline setups
│   └── Sajeeb_Data_Analysis.ipynb         # Funnel analysis, Pareto charts, and calculations
├── documentation/
│   ├── Growth_Copy_Deck.pdf               # Psychological copywriting strategy and button rewrites
│   └── Rokomari Growth Roadmap.pdf       # Final 7-slide executive business presentation
└── README.md                              # Project documentation
