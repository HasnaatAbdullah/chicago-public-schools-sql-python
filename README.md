# 🏫 Chicago Public Schools SQL + Python Project

Hi, I'm **Hasnaat Abdullah** 👋  

This is my project where I used **Python** and **SQL** to analyze the **Chicago Public Schools Performance Dataset**.  
In this lab, I practiced how to load data into a **SQLite database**, run **SQL queries**, retrieve useful insights, and integrate SQL with Python for data analysis.

---

## 📌 What I Learned

- How to **load a real-world dataset** into a **SQLite database**.
- How to **write SQL queries** to analyze school performance data.
- Retrieving **metadata** about tables and columns.
- Working with **mixed-case columns** in SQL.
- Using **built-in SQL functions** to solve real-world problems.
- Integrating **Python** with SQL for better data analysis.

---

## 🗂 About the Dataset

This dataset contains information about the performance ratings of **Chicago Public Schools**.  
Some of the details included:

- School Name  
- Location  
- School Type  
- Student Performance  
- Ratings & Scores  
- Performance Categories  

- **Dataset Name:** Chicago Public School Level Performance  
- **Format:** CSV / Excel  
- **Source:** [Chicago Data Portal](https://data.cityofchicago.org/)

---

## 🛠 Tools & Libraries I Used

- **Python** → Pandas, SQLite3, SQLAlchemy  
- **SQLite** → For storing and querying the dataset  
- **Jupyter Notebook** → For running my analysis  
- **SQL** → To write and execute database queries

---

## 📂 My Project Structure

```bash
chicago-public-schools-sql-python/
│
├── data/
│   └── Chicago_Public_Schools.csv        # Dataset file
│
├── notebooks/
│   └── chicago_schools_analysis.ipynb    # My Jupyter Notebook with SQL + Python code
│
├── scripts/
│   └── create_database.py                # Script to load data into SQLite
│   └── query_examples.py                 # Example SQL queries
│
├── README.md                            # This file
└── requirements.txt                     # Libraries I used
