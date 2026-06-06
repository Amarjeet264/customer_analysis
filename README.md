# Customer Shopping Behavior Analysis

## Overview

This project analyzes customer shopping behavior using transactional retail data. The goal is to identify purchasing patterns, customer segments, product preferences, and factors influencing customer engagement and spending. The project follows a complete data analytics workflow, from data preparation and exploration to SQL-based analysis and dashboard creation.

---

## Dataset

The dataset contains customer demographic information, purchase details, shopping behavior metrics, subscription status, review ratings, discounts, and shipping preferences.

### Key Attributes

* Customer ID
* Age
* Gender
* Location
* Item Purchased
* Category
* Purchase Amount
* Season
* Review Rating
* Subscription Status
* Discount Applied
* Shipping Type
* Previous Purchases
* Frequency of Purchases

---

## Tools & Technologies

* **Python**

  * Pandas
  * NumPy
  * Matplotlib
  * Seaborn

* **Database**

  * PostgreSQL

* **SQL**

  * Business analysis queries
  * Aggregations
  * Customer segmentation

* **Visualization**

  * Power BI

* **Documentation & Presentation**

  * Gamma
  * PowerPoint

---

## Project Workflow

### 1. Data Loading & Exploration

* Imported dataset using Pandas
* Performed initial data exploration
* Generated descriptive statistics
* Identified data quality issues

### 2. Data Cleaning & Preparation

* Handled missing values
* Standardized column names
* Removed redundant fields
* Created derived features for analysis

### 3. Exploratory Data Analysis (EDA)

* Customer demographic analysis
* Spending behavior analysis
* Category-wise sales analysis
* Subscription behavior analysis
* Review rating analysis

### 4. Database Integration

* Connected Python with PostgreSQL
* Loaded cleaned data into database tables
* Created structured datasets for analysis

### 5. SQL Analysis

Performed business-focused SQL queries including:

* Revenue by gender
* Customer segmentation
* Top-rated products
* Subscription analysis
* Discount impact analysis
* Revenue by age group
* Repeat customer analysis
* Product category performance

### 6. Dashboard Development

Built an interactive Power BI dashboard featuring:

* Customer overview metrics
* Revenue analysis
* Sales by category
* Customer segmentation
* Subscription insights
* Age group analysis
* Interactive filters and slicers

### 7. Reporting & Presentation

* Created a detailed business report
* Documented findings and recommendations
* Developed presentation slides using Gamma

---

## Key Insights

* Identified high-value customer segments
* Analyzed spending patterns across demographics
* Evaluated the impact of discounts on purchases
* Determined top-performing products and categories
* Examined subscription behavior and customer loyalty
* Generated actionable business recommendations

---

## Project Structure

```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
├── notebooks/
├── sql_queries/
├── dashboard/
├── reports/
├── presentation/
├── screenshots/
└── README.md
```

## How to Run

### 1. Clone Repository

```bash
git clone <repository-url>
cd Customer-Shopping-Behavior-Analysis
```

### 2. Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn sqlalchemy psycopg2-binary
```

### 3. Run Notebook

Open Jupyter Notebook and execute the notebook cells sequentially.

### 4. Load Data into PostgreSQL

Update database credentials and execute the database integration script.

### 5. Execute SQL Queries

Run the provided SQL scripts to generate business insights.

### 6. Open Power BI Dashboard

Open the dashboard file and refresh the data source if required.

---

## Business Value

This project demonstrates how data analytics can be used to understand customer behavior, improve customer engagement, optimize marketing strategies, and support data-driven business decision-making.

---

## Author

Amarjeet Singh
