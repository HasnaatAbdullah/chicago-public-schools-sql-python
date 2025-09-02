# chicago-public-schools-sql-python
A data analysis project using SQL and Python to explore Chicago Public School performance data. The dataset is stored in a SQLite database, and various SQL queries are executed to retrieve insights, solve real-world problems, and practice database functions. Perfect for learning SQL + Python integration.
# 🏫 Working with a Real-World Dataset using SQL and Python

This project demonstrates how to work with a real-world dataset of **Chicago Public School Level Performance** using **Python** and **SQL**.  
It walks you through **loading data**, **storing it in a SQLite database**, **querying metadata**, and **solving real-world problems** using built-in SQL functions.

---

## 📌 Project Objectives

By completing this project, you will:

- Understand the **Chicago Public School Performance Dataset**.
- Store the dataset into a **SQLite database** using Python.
- Retrieve **metadata** about tables and columns.
- Query data from **mixed-case columns**.
- Use built-in **SQL functions** to analyze data.
- Strengthen your **SQL + Python integration** skills.

---

## 🗂 Dataset

The dataset contains information about the **performance ratings of Chicago Public Schools**, including details like:

- School Name  
- Student Performance  
- Location  
- School Type  
- Performance Category  
- Ratings & Scores

- **Dataset Name:** Chicago Public School Level Performance  
- **Format:** CSV / Excel  
- **Source:** [Chicago Data Portal](https://data.cityofchicago.org/)

---

## 🛠️ Technologies Used

- **Python** → Pandas, SQLite3, SQLAlchemy  
- **SQLite** → Relational Database  
- **Jupyter Notebook** → For interactive analysis  
- **SQL** → For querying and analyzing the dataset

---

## 📂 Project Structure

```bash
chicago-public-schools-sql-python/
│
├── data/
│   └── Chicago_Public_Schools.csv        # Dataset file
│
├── notebooks/
│   └── chicago_schools_analysis.ipynb    # Jupyter notebook with SQL + Python code
│
├── scripts/
│   └── create_database.py                # Script to load data into SQLite
│   └── query_examples.py                 # Example SQL queries
│
├── README.md                            # Project documentation
└── requirements.txt                     # Python dependencies
