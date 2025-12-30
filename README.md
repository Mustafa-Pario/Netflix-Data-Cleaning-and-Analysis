# End-To-End Netflix Data Analysis Project

This repository contains an end-to-end data analysis pipeline that extracts,
cleans, transforms, and analyzes Netflix dataset data using Python and SQL Server.

The project demonstrates a practical data workflow from raw CSV ingestion
to structured SQL-based analysis.


<p align="center">
  <img width="1200" height="600" alt="ELT Diagram"
       src="https://github.com/user-attachments/assets/f96f82f7-eacc-4b70-973b-2ca7091b69c1" />
</p>


---

## 🚀 Project Overview

The pipeline automates the ingestion of the Netflix dataset, loads it into
Microsoft SQL Server, performs data cleaning and normalization using SQL,
and answers real-world analytical questions using advanced SQL queries.

The project focuses on:
- Data extraction using Python (Pandas)
- Persistent storage in SQL Server
- Data cleaning and normalization using T-SQL
- Analytical querying for business insights

---

## ✨ Key Features

- **Data Extraction**: Uses Pandas to read and load CSV data into SQL Server.
- **Database Connectivity**: Utilizes SQLAlchemy for SQL Server connections.
- **Data Cleaning**: Removes duplicates, handles missing values, and standardizes formats.
- **Data Normalization**: Splits multi-valued columns into relational tables.
- **SQL Analysis**: Answers business-driven analytical questions using T-SQL.

---

## 📁 Project Structure

- Netflix-Data-Cleaning-and-Analysis
   - Dataset/netflix_titles.csv
   - data_extraction/netflix_data_extract.ipynb
   - data_Analysis/netflix_data_analysis.ipynb
   - requirements.txt
   - README.md



---

## ⚙️ Execution Flow

The data pipeline follows these steps:

- **Read CSV Data**
 Loads netflix_titles.csv using Pandas.

- **Database Connection**
Establishes connection to Microsoft SQL Server using SQLAlchemy and pyodbc.

- **Load Raw Data**
Inserts data into the netflix_raw table.

- **Data Cleaning (SQL)**
Removes duplicates
Normalizes columns (genre, director, country, cast)
Handles missing values
Creates final cleaned table netflix

- **Data Analysis (SQL)**
Executes analytical queries for insights.



## 📊 Data Analysis Use Cases

- Directors who created both Movies and TV Shows
- Country with the highest number of Comedy movies
- Director with the most movies released per year
- Average movie duration by genre
- Directors who created both Comedy and Horror movies


## 🧰 Tech Stack

- Language: Python 3.x
- Data Processing: Pandas
- Database: Microsoft SQL Server
- ORM / Connectivity: SQLAlchemy
- Query Language: SQL


## ✅ Final Output

- Cleaned and normalized Netflix dataset
- Relational SQL tables ready for reporting
- Actionable insights from SQL analysis




