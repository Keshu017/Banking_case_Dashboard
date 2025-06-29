# Banking_case_Dashboard
# Banking Customer Analytics 📊

This project explores a synthetic banking dataset using **Python**, **MySQL**, and **Power BI**. It includes full-cycle data analysis—from ingestion and cleaning to visualization—aimed at uncovering customer behavior and financial patterns.

---

## Tools Used
- **Python (pandas, matplotlib, seaborn)** – for data cleaning and EDA.
- **MySQL** – to store and manage structured banking data.
- **Jupyter Notebook (VS Code)** – for coding and analysis (`banking_case1.ipynb`).
- **Power BI** – to build an interactive dashboard (`Banking_dashboard.pbit`).

---

##  Files Included
- `Banking.csv` – The main dataset.
- `banking_case1.ipynb` – Python notebook with cleaning, SQL connection, and EDA.
- `Banking_dashboard.pbit` – Power BI dashboard file.
- `requirements.txt` – Python package list.

---

##  Key Insights from the Project

-  **Younger customers (age 20–35)** tend to have **fewer loans** and **higher deposit ratios**, but lower credit card balances.
-  **Platinum loyalty customers** have the **highest average income and property ownership**, indicating a high-value segment.
-  A **strong correlation** exists between `Estimated Income` and `Bank Deposits`, but not with credit card balances.
-  Occupation type significantly affects customer wealth—**Consultants and Executives** are top tiers in deposits.
-  **Risk Weighting** increases with the number of products held, especially loans and credit cards.

These findings were visualized using Power BI for better understanding by stakeholders.

---

##  How to Run
1. Load `Banking.csv` into MySQL (optional – can use directly in notebook).
2. Run `banking_case1.ipynb` to explore, clean, and analyze the data.
3. Open `Banking_dashboard.pbit` in Power BI and connect to MySQL or CSV.
4. Refresh visuals to explore customer behavior dynamically.

---

## Author
**Keshavan R.**  
_Data Analyst & Machine Learning Enthusiast_
