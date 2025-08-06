<img width="2206" height="1281" alt="image" src="https://github.com/user-attachments/assets/ca1f835d-11ee-4101-a821-925679aaf5ea" />

# 🧾 Actual Spending Behavior Dashboard

## 📌 Table of Contents
1. [Overview](#overview)
2. [Dataset Description](#dataset-description)
3. [Dashboard Structure](#dashboard-structure)
4. [Key Insights & Recommendations](#key-insights--recommendations)
5. [Tools Used](#tools-used)
6. [Files Included](#files-included)

---

## Overview

This project presents an **interactive Tableau dashboard** analyzing 5 years (2020–2024) of **personal finance behavior**. It aims to uncover saving potential, identify overspending habits, and provide realistic recommendations for financial improvement.

---

## Dataset Description

**Personal Finance Dataset**

- **Type**: Synthetic (realistic simulation)
- **Size**: 1,500 rows × 5 columns
- **Quality**: No missing or duplicate values

**Features:**
- `Date`: Transaction date  
- `Transaction Description`: Transaction label  
- `Category`: Income or expense category  
- `Amount`: Amount of money spent or earned  
- `Type`: Expense or Income

**Objective**:
- Monitor actual income and expenses
- Detect habitual spending
- Support users in achieving better budgeting and savings habits

---

## Dashboard Structure

The dashboard contains 4 key sections:

1. **KPI Summary Cards**  
   - Total Income, Total Expenses, Net Saving  
   - Trend indicators per year  

2. **Monthly Spending Trend**  
   - Visual timeline of monthly expenses  
   - Highlights spikes and consistency  

3. **Spending Distribution**  
   - Pie chart of spending categories  
   - Identifies dominant expenses (e.g., Shopping, Entertainment)  

4. **Saving Opportunity Analysis**  
   - Estimates potential savings  
   - Essential vs. Non-essential expenses breakdown  

---

## Key Insights & Recommendations

### 📍 Insights

- **Overspending Detected**: Net loss of ~$195,000 despite $883,000 income  
- **Only ~18% months showed positive saving**  
- **Spending behavior is highly habitual (>99% repeated categories)**  
- **Non-essential expenses dominate (up to 60% of monthly spending)**

### 💡 Recommendations

- Reduce spending in **Shopping & Travel** → Cap monthly limit (e.g., 20% reduction = +$700/month saved)
- Use budgeting tools (e.g., Excel, PocketGuard) to track categories
- Introduce **“No-Spend Weeks”** to break habitual patterns
- Allocate at least **15–20%** of income to automated savings
- Build a **3–6 month emergency fund** using savings from reduced non-essentials

These are **personalized, data-driven recommendations** derived directly from behavior visualized in the dashboard.

---

## Tools Used

- **Tableau** (Data visualization)
- **Calculated Fields** (to create KPIs, classify expenses, analyze trends)

---

## Files Included

- `report_spending_behavior_dashboard.twbx` — Tableau workbook  
- `Personal_Finance.xlsx` — Transaction dataset  
- `Dashboard_Actual_Spending_Behavior.pdf` — Dashboard snapshot

---

> 📝 *Created by Nguyen Phuong Nhi as part of a data visualization and storytelling project.*

*Built with Tableau. Created by [Nguyen Phuong Nhi].*
