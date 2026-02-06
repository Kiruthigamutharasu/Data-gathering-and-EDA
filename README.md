# Assignment 13 – Data Gathering, Preprocessing and Exploratory Data Analysis

This repository contains the implementation of Assignment 13, which focuses on pre-ML foundations including data collection from multiple sources, data preprocessing, cleaning, and Exploratory Data Analysis (EDA).  


---

## Objective

The purpose of this assignment is to:

- Gather data from different sources (CSV, JSON, SQL, API)  
- Perform data preprocessing and cleaning  
- Conduct Exploratory Data Analysis to understand patterns and issues in the data  
- Visualize relationships using Matplotlib and Seaborn

---

## Libraries Used

- pandas  
- numpy  
- matplotlib  
- seaborn  
- requests  
- sqlite3  

No other external libraries or machine learning frameworks were used as per restrictions.

---

## Data Sources

### 1. Kaggle Dataset
- Dataset: Titanic  
- File Used: train.csv  
- Link: https://www.kaggle.com/c/titanic/data  

### 2. JSON Data  
- File: sample.json  
- Loaded using pandas and converted to DataFrame.

### 3. SQLite Database  
- Database: sample.db  
- Table: employees  
- Operations: table creation, insertion of records, and retrieval using SQL query.

### 4. TMDB API  
- API Endpoint: /movie/popular  
- Method: GET using requests library  
- Output File: tmdb_movies.csv  
- Extracted Fields:
  - movie title  
  - release date  
  - rating  
  - popularity  
  - vote count  
  - original language  

Note: The API key has been removed before submission for security reasons.

---

## Tasks Performed

### Part 1 – Data Gathering
- Loading CSV dataset using pandas  
- Reading JSON file and conversion to DataFrame  
- Creating SQLite database and performing SQL queries  
- Collecting movie data from TMDB API

### Part 2 – Data Preprocessing and Cleaning
- Checking dataset structure and data types  
- Handling missing values  
- Removing duplicate records  
- Renaming columns to lowercase and snake_case  
- Fixing incorrect data types  
- Encoding categorical variables  
- Separating features and target column

### Part 3 – Exploratory Data Analysis
- Univariate analysis using histograms, KDE, and count plots  
- Bivariate analysis using scatter plots, box plots, and heatmaps  
- Identification of outliers  
- Analysis of relationships between variables  
- Documentation of insights and observations

---

## Repository Contents

- train.csv – Kaggle dataset  
- sample.json – JSON data source  
- sample.db – SQLite database  
- tmdb_movies.csv – Data collected from TMDB API  
- Assignment_13.ipynb – Complete implementation notebook  
- README.md – Project documentation

---

## Execution Instructions

1. Install required libraries:
pip install pandas numpy matplotlib seaborn requests


2. Open the notebook:


3. Run all cells sequentially to reproduce results.

---

## Key Insights

- Missing values were present in several columns and handled appropriately.  
- Numerical variables such as Fare showed skewed distribution.  
- Passenger class demonstrated strong relationship with survival.  
- Outliers were detected in Age and Fare features.  
- TMDB data was successfully collected and stored using official API.

---

## Submission Details

- Kaggle dataset link has been provided.  
- TMDB API usage details are documented in the notebook.  
- All required files are included in this repository as per instructions.

