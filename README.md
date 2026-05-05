# 🚀 A/B Testing Analysis: Landing Page Conversion Optimization

## 🎯 Problem Statement
Can a new landing page improve user conversion rates compared to the existing one?

This project evaluates both **statistical significance** and **practical business impact** to support a real-world product decision.

---

## 🧠 Business Context
A/B testing is widely used by product and growth teams to validate changes before rollout.

👉 Key Question:
**Should the company roll out the new landing page?**

---

## 📊 Dataset Overview

| Column         | Description |
|----------------|------------|
| user_id        | Unique user identifier |
| group          | control / treatment |
| landing_page   | old_page / new_page |
| converted      | 1 = converted, 0 = not converted |

---

## 🧹 Data Validation (Critical Step)

- Removed mismatched users where:
  - Control group saw new page  
  - Treatment group saw old page  

✅ Ensured valid A/B test setup

---

## 📈 Conversion Rate Analysis (KEY METRIC)

| Group       | Conversion Rate |
|------------|----------------|
| Control    | **12.04%** |
| Treatment  | **11.88%** |

📌 **Absolute Difference (Lift): -0.16 percentage points**

👉 The new landing page performs slightly worse than the old page.

---

## 🧪 Statistical Testing

- Test: Two-proportion Z-test  
- **P-value: 0.1897**

📌 Interpretation:  
Since **p > 0.05**, the result is **not statistically significant**

---

## 📉 Effect Size (Practical Impact)

- **Cohen’s h: -0.0049**

📌 Interpretation:  
Negligible difference → no meaningful business impact

---

## ⚡ Statistical Power

- **Power: 0.2588**

📌 Interpretation:  
Low power → experiment may not detect small effects reliably

---

## 📊 Visualization Insight

- 95% confidence intervals **overlap significantly**
- Indicates **high uncertainty in difference**

---

## 🧾 Final Decision

### ❌ Do NOT roll out the new landing page

### Reasoning:
- Conversion rate is lower (**11.88% vs 12.04%**)  
- No statistical significance  
- Negligible effect size  
- Weak and unreliable difference  

📌 The observed change is likely due to random variation.

---

## 💡 Key Takeaways

- Statistical significance ≠ business impact  
- Conversion rate difference must be meaningful, not just measurable  
- Data quality issues can affect experiment validity  
- Not every experiment leads to a rollout decision  

---

## 🛠 Tech Stack

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Statsmodels  

---

## 📁 Project Structure
ab-testing-project/
│── notebook.ipynb
│── ab_data.csv
│── README.md



## 📣 Why This Project Matters

A/B testing is one of the most common real-world tasks for data analysts.

This project demonstrates:
- End-to-end experiment analysis  
- Statistical reasoning  
- Business decision-making  

---

## ⭐ If you found this useful
Feel free to star ⭐ the repo or connect with me on LinkedIn
