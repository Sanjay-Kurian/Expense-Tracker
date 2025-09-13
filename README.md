# Expense-Tracker
![Flask_UI](/Images/FlaskUI.png)

An end-to-end **personal finance tracking system** that integrates data from **Splitwise, Bank Statements, and Credit Card transactions**, processes it with **Python**, provides an **interactive Flask web app** for expense categorization, and visualizes insights in **Power BI**.

---

## Features
- **API Integration**: Extracts expense data directly from **Splitwise API**.
- **Multi-source ingestion**: Merges Splitwise, Bank, and Credit Card transactions.
- **Data Cleaning & Deduplication**: Removes duplicates when the same expense appears across multiple sources.
- **Fuzzy Matching (RapidFuzz)**: Standardizes merchant/transaction descriptions.
- **Excel + Pandas**: Maintains running balances and historical data.
- **Flask Web App**:  
  - Review uncategorized transactions  
  - Edit categories and notes dynamically  
  - Append new transactions seamlessly  
- **Power BI Dashboard**: Visualizes  
  - Income vs Expenses  
  - Spending by category  
  - Cash flow trends  

---

## Tech Stack
- **Python**: Pandas, Requests, RapidFuzz, OpenPyXL  
- **APIs**: Splitwise API  
- **Flask**: Interactive web app for transaction management  
- **Power BI**: Dashboarding and visualization  
- **Git/GitHub**: Version control  

---

## Project Structure
Expense-Tracker/
│-- app.py # Flask application
│-- requirements.txt # Python dependencies
│-- data/
│ ├── bank_statements/ # Bank CSV/Excel files
│ ├── credit_cards/ # Credit card data
│ └── processed/ # Cleaned/merged data
│-- notebooks/ # Jupyter notebooks for exploration
│-- static/ & templates/ # Flask frontend assets
│-- reports/ # Power BI dashboards/screenshots
│-- README.md

Power BI Dashboard


(Attach a screenshot of your dashboard here)

Future Improvements

Add predictive budgeting using ML models

Automate daily scheduled ingestion with Airflow/Prefect

Deploy Flask app to Heroku/Azure for public access

Acknowledgements

- Splitwise API
- Pandas
- RapidFuzz
- Power BI

Contact

Sanjay Kurian
Data Analyst | Aspiring Data Engineer
LinkedIn | GitHub
