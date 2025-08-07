# 📊 Walmart Data Analysis: SQL + Python Project

This end-to-end data analysis project extracts actionable business insights from Walmart sales data using Python and SQL. It is designed for data analysts looking to build real-world skills in data cleaning, SQL querying, and data pipeline development.

---

## 🚀 Project Overview

- 🔧 **Tools Used**: Python, MySQL, PostgreSQL, SQLAlchemy, Pandas, Kaggle API
- 📚 **Skills Practiced**: Data wrangling, feature engineering, SQL analytics, business problem solving
- 💡 **Outcome**: Gain experience in structured analysis and data flow from raw ingestion to actionable insights

---

## 🧱 Project Workflow

### 1. Environment Setup
- IDE: Visual Studio Code (VS Code)
- Organized project folders for data, scripts, and documentation

### 2. Kaggle API Setup
- Configure API via `kaggle.json`
- Pull dataset using:  
  `kaggle datasets download -d`

### 3. Dataset
- Source: [Walmart Sales Data on Kaggle](https://www.kaggle.com/datasets/benroshan/factors-affecting-campus-placement)
- Save in `data/` folder

### 4. Data Analysis & Cleaning
- Remove duplicates & missing values
- Standardize column types (e.g., datetime, float)
- Format currency and ensure consistency

### 5. Feature Engineering
- New feature: `Total_Amount = unit_price × quantity`

### 6. Load into MySQL & PostgreSQL
- Use `SQLAlchemy` to automate table creation & data insertion
- Verify integrity with test queries

### 7. SQL Business Analysis
Solve business problems such as:
- 📈 Revenue trends by branch/category
- 🛒 Best-selling categories
- 🕒 Peak sales hours & days
- 💳 Payment method analysis
- 💰 Profit margin comparisons

### 8. Project Publishing
- Publish on GitHub with:
  - `README.md` (this file)
  - SQL scripts
  - Jupyter Notebooks or `.py` scripts
  - Instructions for dataset access

---

## 🧰 Requirements

- Python 3.8+
- MySQL & PostgreSQL
- Python Libraries:
  - `pandas`, `numpy`, `sqlalchemy`
  - `mysql-connector-python`, `psycopg2`
- Kaggle API key

---

## 📎 Dataset Reference

- 🔗 **[Walmart Sales Dataset – Kaggle](https://www.kaggle.com/datasets/benroshan/factors-affecting-campus-placement)**  
- If not available, you can substitute with similar structured sales datasets with store, product, and sales features.

---

## 📌 Project Highlights

- 💼 Real-world business analysis use-cases
- 🧠 Structured problem-solving with SQL
- 🔄 End-to-end workflow: raw data → insights

---

## 📬 Contact

Feel free to reach out via [LinkedIn](https://www.linkedin.com/) or raise an issue in this repo if you have questions or suggestions!

