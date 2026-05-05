# 🚀 A/B Testing Analysis: Landing Page Conversion Optimization

## 📊 Key Result (TL;DR)

The new landing page achieved a **conversion rate of 11.88%**, compared to **12.04%** for the existing page.

- 📉 Absolute change: **-0.16 percentage points**
- 🧪 P-value: **0.1897** (not statistically significant)
- 📉 Effect size: **negligible**

👉 **Final Decision: Do NOT roll out the new landing page**

---

## 🎯 Problem Statement

Can a new landing page improve user conversion rates?

This project evaluates:
- Statistical significance (Is the result real?)
- Practical significance (Does it actually matter?)

---

## 🧠 Business Context

A/B testing is widely used in product and growth teams to validate changes before rollout.

Even small changes in conversion rate can:
- Impact revenue  
- Affect user engagement  
- Influence product decisions  

👉 Goal: **Make a data-driven decision under uncertainty**

---

## 📊 Dataset Overview

| Column         | Description |
|----------------|------------|
| user_id        | Unique user identifier |
| group          | control / treatment |
| landing_page   | old_page / new_page |
| converted      | 1 = converted, 0 = not converted |

---

## 🧹 Data Validation

Real-world issue detected:

- Control users seeing new page  
- Treatment users seeing old page  

✅ These mismatches were removed to ensure experiment validity.

---

## 📈 Conversion Rate Analysis

| Group       | Conversion Rate |
|------------|----------------|
| Control    | **12.04%** |
| Treatment  | **11.88%** |

📌 **Absolute Lift: -0.16%**

👉 The new page performs slightly worse than the old page.

---

## 📊 Visualization

### Conversion Rate Comparison

![Conversion Rate](https://github.com/KrishnaTiwari1cr/ab-testing-project-/blob/main/Coversion_Rate.png?raw=true)

---

## 🧪 Statistical Testing

- Test: Two-proportion Z-test  
- **P-value: 0.1897**

📌 Interpretation:  
No statistically significant difference (**p > 0.05**)

---

## 📉 Effect Size (Practical Impact)

- **Cohen’s h: -0.0049**

📌 Interpretation:  
Negligible → no meaningful business impact

---

## ⚡ Statistical Power

- **Power: 0.2588**

📌 Interpretation:  
Low power → experiment may not detect small effects reliably

---

## 💰 Business Impact

Even a **0.16% drop in conversion rate** can result in significant losses at scale.

👉 Rolling out the new page could negatively impact overall performance.

---

## 🧾 Final Recommendation

### ❌ Do NOT roll out the new landing page

### Reason:
- Lower conversion rate (**11.88% vs 12.04%**)  
- No statistical significance  
- Negligible effect size  
- Weak and unreliable difference  

📌 The observed difference is likely due to random variation.

---

## 🧠 Key Learnings

- Statistical significance ≠ business impact  
- Effect size matters more than p-value alone  
- Data validation is critical in experiments  
- Not all experiments lead to rollout decisions  

---

## 🛠 Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Statsmodels  

---

## 📁 Project Structure
