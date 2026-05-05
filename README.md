# A/B Testing Analysis: Landing Page Conversion Optimization

## 📊 Executive Summary

The new landing page achieved a **conversion rate of 11.88%**, compared to **12.04%** for the existing page.

- Absolute change: **-0.16 percentage points**
- P-value: **0.1897** (not statistically significant)
- Effect size: **negligible**

**Conclusion:** The new landing page does not improve performance and should not be rolled out.

---

## 🎯 Objective

To determine whether a newly designed landing page leads to a statistically and practically significant improvement in user conversion rate.

---

## 🧠 Business Context

A/B testing is a critical decision-making tool in product and growth teams. Even small changes in conversion rates can significantly impact revenue and user engagement at scale.

This analysis aims to ensure that any product change is both **statistically valid** and **business-relevant** before deployment.

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

During data inspection, inconsistencies were identified:

- Users in the control group exposed to the new page  
- Users in the treatment group exposed to the old page  

These records were removed to preserve the integrity of the experiment.

---

## 📈 Conversion Rate Analysis

| Group       | Conversion Rate |
|------------|----------------|
| Control    | **12.04%** |
| Treatment  | **11.88%** |

**Absolute difference:** -0.16 percentage points

The treatment group shows a slightly lower conversion rate compared to the control group.

---

## 📊 Visualization

### Conversion Rate Comparison

![Conversion Rate](https://github.com/KrishnaTiwari1cr/ab-testing-project-/blob/main/Coversion_Rate.png?raw=true)

---

## 🧪 Statistical Analysis

- Method: Two-proportion Z-test  
- P-value: **0.1897**

**Interpretation:**  
The observed difference is not statistically significant at the 5% significance level.

---

## 📉 Effect Size (Practical Significance)

- Cohen’s h: **-0.0049**

**Interpretation:**  
The difference between groups is negligible and does not represent a meaningful practical impact.

---

## ⚡ Statistical Power

- Power: **0.2588**

**Interpretation:**  
The test has low statistical power, indicating limited ability to detect small differences.

---

## 💰 Business Impact

A decrease of **0.16 percentage points** in conversion rate can result in substantial performance loss at scale.

Rolling out the new page could negatively impact key business metrics.

---

## 🧾 Final Recommendation

**Do not implement the new landing page.**

### Rationale:
- Lower observed conversion rate  
- No statistical significance  
- Negligible effect size  
- High uncertainty in results  

The observed variation is likely due to random chance rather than a genuine improvement.

---

## 🧠 Key Insights

- Statistical significance alone is insufficient; practical impact must be considered  
- Effect size is essential for interpreting real-world relevance  
- Data validation is critical for maintaining experimental integrity  
- Not all experiments lead to actionable changes  

---

## 🛠 Tools and Technologies

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Statsmodels  

---


---

## 🧠 Skills Demonstrated

- A/B Testing and Experimental Design  
- Hypothesis Testing  
- Statistical Significance and Power Analysis  
- Data Cleaning and Validation  
- Business Decision-Making  

---

## 📣 Relevance

A/B testing is a core competency for data analysts and product analysts.  
This project demonstrates the ability to translate statistical results into clear, business-oriented decisions.

---

## ⭐ Acknowledgment

If you found this project useful, feel free to star the repository or connect with me on LinkedIn.
