# Employee Attrition Analysis: Salifort Motors Case Study

## 📌 Project Overview
This project is the final Capstone for the **Google Advanced Data Analytics Professional Certificate**. 
The goal was to help the HR department of a fictional company, Salifort Motors, reduce employee turnover by identifying key factors that lead to resignations and building a predictive machine learning model.

## 📊 Key Business Insights
My analysis revealed that employee attrition is driven by two main extremes:
*   **Burnout (The Silent Killer):** Employees assigned to **6 or 7 projects** or working more than **240 hours/month** are at a critical risk of leaving.
*   **Satisfaction Gap:** Low satisfaction scores (~0.4 and below) are the strongest statistical predictors of churn.
*   **The 3-5 Year Crisis:** Employees are most likely to leave between their 3rd and 5th year. However, those who stay past **6 years** show significantly higher loyalty.

## 🛠 Tech Stack & Methodology
*   **Language:** Python
*   **Libraries:** Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, Statsmodels
*   **Models Evaluated:** 
    *   **Logistic Regression** (Baseline: 80% accuracy, 19% recall)
    *   **Random Forest Classifier** (Champion: 98% accuracy, 91% recall)
*   **Optimization:** Hyperparameter tuning via `GridSearchCV` (optimized for F1-score).
*   **Framework:** Followed the **PACE** (Plan, Analyze, Construct, Execute) workflow.

## 🚀 Strategic Recommendations
1.  **Cap Project Load:** Limit assignments to a maximum of 5 projects per person.
2.  **Monitor Overtime:** Flag and review workloads for employees exceeding 240 hours/month.
3.  **Retention Programs:** Implement specialized career growth programs for the "3-5 year" tenure group.
4.  **Pulse Surveys:** Conduct quarterly engagement checks to catch drops in satisfaction early.

## 📁 Repository Structure
*   `Employee_Attrition_Analysis.ipynb`: Full technical analysis and modeling.
*   `Salifort_Motors_Executive_Summary.pdf`: A one-page business report for stakeholders.
---
*Developed as part of the Google Advanced Data Analytics Professional Certificate.*
