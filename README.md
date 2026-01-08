# 📊 Customer Churn Analysis & Prediction

## 📌 Project Overview

This project aims to identify why customers are leaving (churning) and build a predictive model to flag "at-risk" customers before they quit. By combining **SQL data engineering**, **Random Forest Machine Learning**, and **Power BI visualizations**, this end-to-end solution provides actionable insights to increase customer retention and business revenue.

## 🚀 The Workflow

### 1. Data Cleaning (SQL)

Raw data is often messy. I used **SQL Server** to transform and clean the dataset.

* **Handling Nulls:** Used `ISNULL()` to fill missing values in critical columns like `Online_Security`, `Contract`, and `Internet_Type`.
* **Feature Engineering:** Created views to separate "Active/Churned" customers from "Newly Joined" customers to ensure the ML model learns from historical behavior.
* **Script:** See `SQLQuery3.sql` for the full transformation logic.

### 2. Machine Learning (Python)

Using a **Random Forest Classifier**, I built a "Crystal Ball" to predict churn.

* **Preprocessing:** Encoded categorical variables and handled class imbalances.
* **Performance:** Achieved an **84% Accuracy Score**.
* **Top Drivers:** The model identified **Contract Type**, **Tenure**, and **Monthly Charges** as the biggest predictors of churn.

### 3. Business Visualization (Power BI)

I created an interactive dashboard to make the data "speak" to stakeholders.

* **KPIs:** Tracked Total Churn Rate, Revenue Loss, and Customer Demographics.
* **Insights:** Visualized the correlation between high monthly charges and customer exit rates.

---

## 📂 Project Structure

* `SQLQuery3.sql`: Database scripts for data cleaning and preparation.
* `ChurnML.ipynb`: Jupyter Notebook containing the Random Forest model and evaluation.
* `Executive_report.docx`: A non-technical summary designed for investors/management.
* `Prediction_Data.xlsx`: The cleaned dataset used for training.
* `Churn Analysis.pbix`: The Power BI dashboard file.

## 📈 Key Findings

* **Contracts Matter:** Customers on Month-to-Month contracts are **6x more likely** to churn than those on 2-year plans.
* **Security Services:** Offering "Online Security" bundles reduces churn probability by nearly 25%.
* **Newbie Risk:** Most churn occurs within the first 6 months of a customer joining.

---

## 🛠️ How to Run

1. **Database:** Execute the SQL script in your SQL environment to clean the raw data.
2. **Model:** Open `ChurnML.ipynb` in Jupyter or VS Code. Ensure you have `scikit-learn`, `pandas`, and `seaborn` installed.
3. **Report:** Check the `Executive_report.docx` for a breakdown of business recommendations.

## 🤝 Contact

**[Farzan Ahmad]** *Data Analyst & Machine Learning Enthusiast* [https://www.linkedin.com/in/farzan-ahmad-bb9572240/] | [farzanahmed3615@gmail.com]
<img width="1292" height="727" alt="Dashboard" src="https://github.com/user-attachments/assets/ceedf8f9-0ae3-49ff-bd2c-b2fa9f80f163" />
<img width="698" height="564" alt="Python" src="https://github.com/user-attachments/assets/bd4cc885-ccbf-4f1f-a597-ba4083b70f5a" />


