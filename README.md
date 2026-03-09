# customer_behaviour_analysis
Data Analytics project showcasing customer behaviour analysis using Python ,SQL and Power-BI.
# Customer Behaviour Data Analytics Project

## 1. Overview

This project focuses on analyzing customer behaviour data to generate meaningful insights. The workflow includes loading the dataset using Python, performing exploratory data analysis (EDA), cleaning the data, running analytical queries using PostgreSQL, and visualizing the results with an interactive Power BI dashboard.

The goal of the project is to transform raw customer data into clear insights that help understand purchasing patterns and customer segments.

---

## 2. Dataset

The dataset contains customer-related information such as:

* Customer ID
* Purchase history
* Previous purchases
* Product category
* Payment method
* Location
* Other behavioural attributes

The data was initially processed in Python before being stored in PostgreSQL for further analysis.

---

## 3. Tools & Technologies

The following tools and technologies were used in this project:

* **Python** – Data loading, cleaning, and exploratory data analysis
* **Pandas & NumPy** – Data manipulation and analysis
* **Matplotlib / Seaborn** – Data visualization during EDA
* **PostgreSQL** – Database storage and SQL querying
* **SQLAlchemy & psycopg2** – Connecting Python with PostgreSQL
* **Power BI** – Dashboard creation and data visualization

---

## 4. Project Steps

### Step 1: Data Loading

* The dataset was loaded into Python using Pandas.
* Data was inspected to understand structure, columns, and data types.

### Step 2: Exploratory Data Analysis (EDA)

* Summary statistics were generated.
* Data distributions and patterns were analyzed.
* Initial visualizations were created to identify trends.

### Step 3: Data Cleaning

* Missing values were handled.
* Data types were corrected where required.
* Duplicate or inconsistent records were removed.

### Step 4: Database Integration

* Cleaned data was loaded into a PostgreSQL database using SQLAlchemy.
* Tables were created to store customer information.

### Step 5: SQL Analysis

SQL queries were used to analyze the dataset, including:

* Customer segmentation based on purchase behaviour
* Purchase frequency analysis
* Category-wise analysis
* Customer distribution insights

### Step 6: Power BI Dashboard

A Power BI dashboard was built to visualize key insights such as:

* Customer segments (New, Returning, Loyal)
* Purchase trends
* Product category distribution
* Key customer metrics

---

## 5. Dashboard Insights

The dashboard provides a clear view of customer behaviour including:

* Distribution of customers across different segments
* Insights into purchasing patterns
* Category-wise product preferences
* Key metrics that help understand customer engagement

---

## 6. How to Run the Project

1. Clone the repository

2. Install required Python libraries:

   pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2

3. Run the Python script to:

   * Load the dataset
   * Perform data cleaning and EDA
   * Store the cleaned dataset in PostgreSQL

4. Run SQL queries in PostgreSQL for analysis.

5. Open the Power BI dashboard file to explore the visual insights.

---

## 7. Project Outcome

This project demonstrates a complete data analytics workflow including:

* Data preprocessing
* Database integration
* SQL-based analysis
* Interactive dashboard creation

It highlights the ability to work with real-world data and transform it into meaningful business insights.
