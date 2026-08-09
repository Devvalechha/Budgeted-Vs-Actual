# 📊 Budget vs Actual Variance Report — Shyam Consumer Goods Pvt. Ltd.

A fictional FMCG (Fast-Moving Consumer Goods) company case study built in Excel to analyze Budget vs Actual performance across revenue, volume, price, and gross margin — using core data analyst formulas and a clean interactive dashboard.

---

## 🎯 Project Objective

Most budget reports only tell you "revenue went up or down." This project goes further — it breaks down WHY revenue moved, by separating the impact of:

* 📦 Volume (units sold)
* 💰 Price (per-unit pricing)

...so the business can see whether growth came from selling more, or selling at better prices.

---

## 🛠️ Tools & Formulas Used

* Microsoft Excel
* SUMIF — for aggregating monthly & product-wise data
* EDATE — for auto-generating month sequences
* IFERROR — for clean error handling in % calculations
* Variance formulas: Volume Variance, Price Variance, Revenue Variance, Gross Margin Variance
* Conditional formatting & data visualization (bar charts)

---

## 📁 File Structure (Sheet-by-Sheet)

| Sheet                 | Purpose                                                               |
| --------------------- | --------------------------------------------------------------------- |
| **1. Visual Summary** | Charts + Key Findings — the headline view of the report               |
| **2. Dashboard**      | Monthly Revenue Summary, Product-wise Variance, Gross Profit Analysis |
| **3. Derived Data**   | Calculation engine — where all variance formulas are built            |
| **4. Raw Data**       | Original source data (Budget vs Actual inputs by month & product)     |

---

## 📈 Key Findings

* ✅ Revenue beat budget by +0.51% (₹21.00 Cr actual vs ₹20.89 Cr budgeted)
* 📦 Growth was driven mainly by higher volume (more units sold), not price
* 💸 Average selling price was actually slightly lower than budgeted — a mild discounting effect
* 🏆 Best performer: Green Tea (250g) — highest variance % (+0.64%)
* 📉 Weakest performer: Oats (500g) — lowest variance % (+0.26%)
* ⚠️ Gross Margin dipped from 47.06% (budget) to 46.63% (actual) — costs (COGS) came in higher than planned, quietly eating into profit despite higher revenue

---

## 🐛 Errors Found & Fixed (QA Process)

Part of this project involved auditing my own formulas for accuracy — a few real issues were found and corrected:

### 1. Formula range typo

A SUMIF range accidentally referenced $N$534 instead of $N$53, a copy-paste error that could break calculations if new data was added.

### 2. Sign/logic mismatch

A "Variance" cell was calculated as Budget − Actual instead of Actual − Budget, which incorrectly flagged a positive result (beating budget) as "Unfavourable." Fixed to correctly show it as Favourable.

(Documenting and fixing these was intentional — real-world dashboards need to be audited, not just built.)

---

## 📷 Preview

(Add screenshots of your Visual Summary charts and Dashboard here)

![Visual Summary](<dashboard.png>)

---

## 📌 Note

This is a fictional company and dataset, created purely for portfolio and learning purposes to demonstrate Excel-based financial variance analysis skills.

---

## 🔗 Connect

If you have feedback or suggestions to improve this project, feel free to open an issue or connect with me on LinkedIn.