# Customer Shopping Behavior Analysis

## Project Overview
This project analyzes customer shopping behavior using Python, SQL, and Power BI. The objective is to clean, transform, store, and visualize customer shopping data to identify purchasing patterns and generate actionable business insights.

## Objectives
- Clean and preprocess customer shopping data.
- Store the processed data in a PostgreSQL database.
- Perform exploratory data analysis (EDA).
- Build an interactive Power BI dashboard.
- Generate insights to support business decision-making.

---

## Technologies Used

- Python
- Pandas
- NumPy
- PostgreSQL
- SQLAlchemy
- Power BI
- Jupyter Notebook

---

## Project Structure

```
Customer Shopping Behavior Analysis/
│
├── Customer_Shopping_Behavior_Analysis.ipynb
├── Customer Behaviour Analysis.pbix
├── customer_shopping_data.csv
├── README.md
```

---

## Workflow

### 1. Data Collection
- Imported customer shopping dataset.
- Loaded data into a Pandas DataFrame.

### 2. Data Cleaning
- Checked for missing values.
- Removed duplicate records.
- Corrected data types.
- Prepared data for analysis.

### 3. Database Integration
- Connected Python with PostgreSQL using SQLAlchemy.
- Loaded cleaned data into PostgreSQL.

### 4. Exploratory Data Analysis
Analyzed:
- Customer demographics
- Purchase frequency
- Product categories
- Spending patterns
- Payment methods

### 5. Dashboard Creation
Created an interactive Power BI dashboard displaying:
- Total Sales
- Number of Customers
- Category-wise Sales
- Gender Distribution
- Payment Method Analysis
- Monthly Sales Trend
- Age Group Analysis

---

## Key Insights

- Identified the most purchased product categories.
- Compared customer spending across different age groups.
- Analyzed preferred payment methods.
- Examined shopping behavior by gender.
- Tracked sales trends over time.

---

## Tools & Libraries

### Python Libraries
```python
pandas
numpy
sqlalchemy
psycopg2
```

### Database
- PostgreSQL

### Visualization
- Microsoft Power BI

---

This project is intended for educational and portfolio purposes.
