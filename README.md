# customer-behaviour-analytics
# Data Analytics Project

## Overview

This project demonstrates an end-to-end **Data Analytics workflow**, from loading and cleaning raw data to generating insights through SQL and Power BI.

The project covers:

* Loading and exploring data using Python
* Exploratory Data Analysis (EDA)
* Data cleaning and preprocessing
* Storing and querying data using PostgreSQL
* Creating SQL queries to extract business insights
* Building an interactive Power BI dashboard
* Presenting key findings and insights

---

## Dataset

The project uses a dataset containing business/customer-related information for analysis.

The dataset was first loaded into Python for exploration and cleaning. After preprocessing, the cleaned data was loaded into a **PostgreSQL database** for SQL analysis and dashboard development.

### Data Preparation

The following activities were performed:

* Checked dataset structure and data types
* Identified missing values
* Checked for duplicate records
* Handled inconsistent or incorrect data
* Performed basic data transformations
* Prepared the cleaned dataset for SQL analysis and visualization

---

## Tools & Technologies

| Tool                     | Purpose                                 |
| ------------------------ | --------------------------------------- |
| **Python**               | Data loading, cleaning and EDA          |
| **Pandas**               | Data manipulation and preprocessing     |
| **NumPy**                | Numerical analysis                      |
| **Matplotlib / Seaborn** | Data visualization                      |
| **PostgreSQL**           | Database storage and SQL analysis       |
| **SQL**                  | Data querying and business analysis     |
| **Power BI**             | Interactive dashboard and visualization |
| **Jupyter Notebook**     | Python-based analysis                   |
| **Git & GitHub**         | Project version control                 |

---

## Project Steps

### 1. Load the Dataset

The dataset was imported into Python using Pandas.

```python
import pandas as pd

df = pd.read_csv("dataset.csv")
```

The initial dataset was inspected to understand its structure, columns, data types and number of records.

### 2. Exploratory Data Analysis

EDA was performed to understand the dataset and identify patterns.

Key activities included:

* Checking rows and columns
* Understanding data types
* Generating descriptive statistics
* Identifying missing values
* Checking duplicate records
* Analyzing numerical and categorical variables
* Creating visualizations to identify trends and patterns

### 3. Data Cleaning

The dataset was cleaned and prepared for further analysis.

Major steps included:

* Handling missing values
* Removing duplicate records
* Correcting data types
* Handling inconsistent values
* Renaming columns where required
* Removing unnecessary columns
* Validating the final dataset

### 4. PostgreSQL & SQL Analysis

The cleaned dataset was imported into a PostgreSQL database.

SQL queries were written to answer business-related questions and generate insights.

Examples of SQL analysis include:

```sql
SELECT COUNT(*) 
FROM customers;
```

```sql
SELECT category, COUNT(*) AS total
FROM customers
GROUP BY category
ORDER BY total DESC;
```

```sql
SELECT category, AVG(sales) AS average_sales
FROM customers
GROUP BY category;
```

SQL was used for filtering, aggregation, grouping, sorting and extracting meaningful information from the data.

### 5. Power BI Dashboard

The analyzed data was connected to Power BI to create an interactive dashboard.

The dashboard includes:

* Key Performance Indicators (KPIs)
* Charts and graphs
* Category-wise analysis
* Trend analysis
* Interactive filters/slicers
* Business insights

The dashboard was designed to provide a quick and clear overview of the most important findings.

---

## Dashboard

The Power BI dashboard provides an interactive view of the analyzed data.

**Key dashboard features:**

* Overall KPIs
* Trend analysis
* Category/segment performance
* Comparative analysis
* Interactive slicers
* Business-focused visualizations

> Add your Power BI dashboard screenshot here.

```text
![Power BI Dashboard](images/dashboard.png)
```

---

## Results

The project helped transform raw data into meaningful business insights through a structured analytics workflow.

### Key Outcomes

* Successfully loaded and explored the dataset using Python.
* Performed EDA to identify patterns, trends and data-quality issues.
* Cleaned and prepared the dataset for analysis.
* Used PostgreSQL and SQL to perform structured data analysis.
* Created an interactive Power BI dashboard.
* Converted analytical findings into easy-to-understand business insights.

### Business Value

The analysis helps stakeholders understand **key trends, performance indicators and patterns in the data**, supporting better data-driven decision-making.

---

## How to Run

### 1. Clone the Repository

```bash
git clone <your-github-repository-url>
cd <project-folder>
```

### 2. Install Required Python Libraries

```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Run the Python Analysis

Open the Jupyter Notebook:

```bash
jupyter notebook
```

Run the notebook to perform:

Data Loading → EDA → Data Cleaning → Export Clean Data

### 4. Set Up PostgreSQL

* Install PostgreSQL.
* Create a database.
* Import the cleaned dataset.
* Run the SQL scripts provided in the project.

### 5. Open Power BI

* Open the `.pbix` Power BI file.
* Update the data source connection if required.
* Refresh the data.
* Explore the interactive dashboard.

---

 Project Structure

```text
Data-Analytics-Project/
│
├── data/
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── notebooks/
│   └── data_analysis.ipynb
│
├── sql/
│   └── analysis_queries.sql
│
├── powerbi/
│   └── dashboard.pbix
│
├── images/
│   └── dashboard.png
│
└── README.md
```

---

 Skills Demonstrated

**Python | Pandas | NumPy | EDA | Data Cleaning | SQL | PostgreSQL | Power BI | Data Visualization | Business Analysis**

---

 Conclusion

This project demonstrates an end-to-end **Data Analytics pipeline** using Python, PostgreSQL, SQL and Power BI. It showcases the ability to work with raw data, clean and analyze datasets, extract insights using SQL, and communicate findings through an interactive dashboard.
M
