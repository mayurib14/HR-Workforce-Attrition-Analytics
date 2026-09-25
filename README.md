# HR-Workforce-Attrition-Analytics- Project
An end-to-end **HR data analytics project** focused on analyzing employee attrition and identifying the key factors associated with employee turnover. This project covers the complete workflow: **data cleaning and preprocessing using Python**, followed by **data analysis, DAX calculations, and interactive dashboard development using Power BI**.

## 📊 Project Overview & Core Findings
Instead of presenting only overall employee statistics, this project provides a detailed view of **attrition patterns, retention factors, and employee risk areas** through an interactive two-page Power BI dashboard with Drill-through analysis.

Key insights discovered:
* **Overall Attrition:** The overall employee attrition rate is **16.12%**, providing a baseline for understanding employee turnover.
* **Overtime Impact:** Employees working overtime show a significantly higher attrition rate of **30.53%**, highlighting overtime as an important factor associated with employee turnover.
* **Commute Distance:** Employees with longer commute distances show higher attrition, reaching up to **42%** beyond 10 km.
* **Role-Specific Attrition:** **Sales Representatives** have an attrition rate of **39.67%**, followed by **Laboratory Technicians** at **23.94%**.
* **Promotion Risk:** Employees with **Performance Ratings 3 and 4** and more than **10 years of experience** were identified with no recorded promotion, highlighting a potential retention risk.
* **Young Employee Risk:** Employees aged **18–29** with low Environment Satisfaction show an attrition rate of **35.29%**, indicating a notable relationship between workplace environment and early-career attrition.

The dashboard allows users to move from the **overall HR Attrition Overview** to detailed **Employee Retention & Risk Analysis** using Drill-through by **Job Role and Department**.


🛠️ ***Tech Stack & Workflow***
### 1. Data Cleaning & Preprocessing (Python)
The raw dataset (`HR-Employee.csv`) was processed using **Python (Pandas)** to ensure data quality and prepare the dataset for Power BI analysis.
* Handled missing values and verified data types.
* Cleaned and standardized categorical columns.
* Prepared and transformed relevant fields for HR analysis.
* Generated the cleaned dataset for seamless Power BI integration.
* *The cleaning script can be found in:* `hr_cleaning.py`.

### 2. Data Modeling & Visualization (Power BI)
The cleaned dataset was imported into **Power BI** to develop an interactive HR Attrition & Retention dashboard.
* Designed an interactive **2-page dashboard** with a clean and professional UI.
* Developed **DAX measures** to calculate dynamic metrics such as Attrition Rate, Attrition Count, and Average Monthly Income.
* Created **Page 1 — HR Attrition Overview** with KPI cards, charts, and filters for Department, Job Role, and Age Group.
* Developed **Page 2 — Employee Retention & Risk Analysis** using **Drill-through** functionality for detailed Job Role and Department analysis.
* Implemented interactive visuals to analyze relationships between **Overtime, Job Role, Promotion, Environment Satisfaction, Job Satisfaction, and Work-Life Balance**.

📂 ***Project Structure***
├── HR-Employee.csv          # Raw HR Dataset
├── hr_cleaning.py           # Python Data Cleaning Script
├── HR_Analytics.pbix        # Power BI Dashboard Project File
└── README.md                # Project Documentation

