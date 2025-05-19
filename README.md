# 💼 Revenue Loss & Unclaimed Shifts Analysis – Clipboard Health

This project analyzes operational and financial inefficiencies within Clipboard Health by identifying the drivers of unclaimed shifts and estimating revenue loss. The goal is to uncover actionable insights that can help reduce shift abandonment and improve shift fulfillment rates.

---

## 📁 Objective

* Identify patterns in unclaimed shifts across day, time slot, and posting behavior
* Quantify estimated revenue loss due to unclaimed shifts
* Recommend pay rate and scheduling adjustments to optimize revenue recovery

---

## 📊 Key Findings

### 1. 📉 Weekend Shift Gaps & Revenue Loss

* **Weekend shifts (Fri PM, Sat AM/PM, Sun AM/PM)** are the most unclaimed.
* **Estimated lost revenue** (Sep 2024 – Jan 2025): **\$697,745.40**
* Top revenue loss slots:

  * Saturday PM: \$68,485.38
  * Friday PM: \$53,999.55
  * Sunday PM: \$47,096.57

### 2. 💰 Pay Rate Disparity: Claimed vs Unclaimed

* Claimed shifts consistently have **higher average pay rates** than unclaimed.
* Example:

  * Wednesday AM: Claimed = \$29.60 vs Unclaimed = \$25.68 (↓ 15.26%)
  * Tuesday PM: Claimed = \$28.37 vs Unclaimed = \$23.97 (↓ 18.32%)
* **Low weekend pay rates** may be deterring workers despite higher demand.

### 3. ⏰ Lead Time Matters

* Shifts posted **< 6 hours before start** had only **3.0% claim rate**.
* Shifts posted 1–2 days in advance had **>10% claim rate**.
* **Short lead times** reduce claim likelihood and require stronger incentives.

### 4. 🕒 Pay Rates vs Lead Time

* Pay rates **do not significantly increase** for last-minute shifts:

  * <6 hours: \$25.14 | 6–12 hrs: \$24.14 | >1 week: \$23.98
* **Minimal incentives** offered for urgent shifts — missed opportunity to attract workers.

### 5. 🚨 No-Shows

* 17 of 31 no-shows were for **AM shifts**.
* Suggests fatigue, scheduling conflict, or inadequate reminders.

---

## 💡 Recommendations

* **Increase weekend pay rates** to match weekday standards and attract workers.
* **Add financial bonuses** for shifts posted <12 hours before start.
* **Implement AM shift reminders/confirmations** to reduce no-shows.
* **Consider lowering margins** slightly on hard-to-fill shifts to improve coverage and net revenue.

---

## 📎 Tools & Techniques Used

* Python (Pandas, NumPy, Matplotlib, Seaborn)
* Excel (initial summaries, formatting)
* Time-based grouping and aggregation
* Custom revenue calculation logic using claimed shift averages
* Visualization of slot/day trends and lead time analysis

---

## 🧠 Project Type

Exploratory business analysis project (Clipboard Health Case Study)

> *"This project combined business intuition with quantitative rigor to uncover shift behavior patterns and offer financially viable improvements."*
