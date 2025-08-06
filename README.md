# 📊 Credit Risk Analysis & Profitability Dashboard
# By: Laymoni Morrison

This project analyzes credit risk and loan profitability using peer-to-peer lending data. Through a combination of data cleaning, feature engineering, machine learning modeling, and interactive dashboard development, the goal was to uncover insights that help evaluate lending strategies and default risk.

---

## 🧠 Project Overview

I used historical LendingClub data to:

- Clean and preprocess borrower information in Python
- Predict loan defaults using multiple machine learning models (Logistic Regression, Random Forest, XGBoost)
- Engineer financial metrics like interest income and estimated profit
- Visualize the risk landscape in Power BI for business-oriented insights

The final dashboard allows users to interact with borrower filters and KPIs, and explore trends across grade, geography, and loan characteristics.

---

## 🧪 Methods

Modeling and data processing were conducted in Google Colab using Python. The key steps included:

- Removing columns with >40% missing values
- Encoding categorical variables and imputing missing values
- Creating custom financial metrics such as `interest_income` and `estimated_profit`
- Training and evaluating classification models to predict default
- Exporting final results to CSV for Power BI visualization

---

## 📁 Files in this Repository

| File/Folder                        | Description |
|-----------------------------------|-------------|
| `notebooks/`                      | Contains the Google Colab notebooks used for data cleaning, feature engineering, and modeling |
| `report/`                         | Final report in PDF format documenting the entire process and insights |
| `dashboard/`                      | Contains a static PDF export of the interactive Power BI dashboard |

---

## 📌 Key Insights Answered in This Project

1. **Are we making money overall and which types of loans are helping or hurting?**  
2. **Which borrower segments are driving the highest risk or returns?**  
3. **Which credit grades are getting the most capital and are they worth the risk?**  
4. **How does housing status influence loan profitability?**  
5. **Which purposes dominate loan demand and do they drive gains or losses?**  
6. **Which borrower segments are receiving the most capital—are they also the most risky?**  
7. **Which model performs best at predicting loan defaults?**  
8. **How does borrower grade impact profitability?**  
9. **Are we lending too much to high-risk borrowers and missing out on safer, more profitable ones?**  
10. **Are we focusing too heavily on high-volume but low-profit states?**  

These questions are explored in both the dashboard and the written report.

---

## 📊 Dashboard Walkthrough Video

Want to see the dashboard in action? Watch the full interactive walkthrough below:

[![Watch the video](https://img.youtube.com/vi/IvKc_jsBXBg/hqdefault.jpg)](https://youtu.be/IvKc_jsBXBg) 
---

## 🧾 Credit

Project created using Python (Google Colab), Power BI, and GitHub.  
📂 Dataset source: [LendingClub Loan Data on Kaggle](https://www.kaggle.com/datasets/wordsforthewise/lending-club)

---

