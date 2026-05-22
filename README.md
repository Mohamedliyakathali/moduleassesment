# Online Retail Data Analysis

## Project Overview
This project performs complete data analysis on the Online Retail Dataset from the UCI Repository using Python.  
The project includes:

- Data Cleaning
- Feature Engineering
- Data Exploration
- Statistical Analysis
- Data Visualization
- Business Insights
- GitHub Project Implementation

---

# Dataset Information

Dataset: Online Retail Dataset – UCI Repository

The dataset contains transactional data of an online retail store including:
- Invoice details
- Product information
- Customer details
- Quantity purchased
- Product prices
- Country information

---

# Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook
- VS Code
- Git & GitHub

---

# Project Structure

```text
Online-Retail-Analysis/
│
├── data/
│   └── Online Retail.csv
│
├── notebooks/
│   └── analysis.ipynb
│
├── scripts/
│   └── analysis.py
│
├── images/
│
├── README.md
├── requirements.txt
└── .gitignore
```

---

# Tasks Performed

## Task 1 – Data Import & Setup
- Loaded dataset using Pandas
- Explored dataset structure
- Converted InvoiceDate to datetime format

## Task 2 – Data Cleaning
- Removed missing CustomerID values
- Removed duplicate records
- Fixed invalid quantity and price values

## Task 3 – Feature Engineering
- Created TotalPrice column
- Extracted Year, Month, Day, Hour
- Created Customer Segment and Order Size categories

## Task 4 – Data Exploration
- Used describe() and info()
- Analyzed unique values and value counts
- Performed groupby() analysis

## Task 5 – Data Wrangling
- Aggregated data using groupby()
- Identified top customers and countries
- Created pivot tables

## Task 6 – Statistical Analysis
- Calculated:
  - Mean
  - Median
  - Mode
  - Variance
  - Standard Deviation
  - Percentiles

## Task 7 – Data Visualization
Created the following plots:
- Line Chart
- Bar Chart
- Histogram
- Box Plot
- Count Plot
- Violin Plot
- Heatmap
- Pair Plot

## Task 8 – Business Insights
Identified:
- Top country by sales
- Best sales month
- Peak sales time
- High-value customers
- Top-selling products

---

# Installation

## Clone Repository

```bash
git clone https://github.com/yourusername/Online-Retail-Analysis.git
```

---

# Install Required Libraries

```bash
pip install -r requirements.txt
```

---

# Run Project

## Jupyter Notebook

```bash
jupyter notebook
```

## Python Script

```bash
python scripts/analysis.py
```

---

# Libraries Required

```txt
pandas
numpy
matplotlib
seaborn
openpyxl
jupyter
```

---

# Sample Visualizations

- Monthly Sales Trend
- Country-wise Sales
- Customer Segmentation
- Correlation Heatmap
- Product Analysis

---

# Business Insights

- The highest sales were generated from the top-performing country.
- Peak sales occurred during specific months and hours.
- High-value customers contributed major revenue.
- Certain products dominated total sales quantity.

---

# Future Improvements

- Build machine learning sales prediction models
- Create interactive dashboards using Power BI or Tableau
- Deploy project using Streamlit

---

# Conclusion

This project demonstrates complete end-to-end data analytics workflow using Python, including:
- Data preprocessing
- Data analysis
- Visualization
- Business insight generation

The project helps understand customer purchasing behavior and retail sales performance.

---

# Author

Mohamed Liyakath Ali

B.Tech – Artificial Intelligence and Data Science  
M.A.M College of Engineering

---

# GitHub

Upload project using:

```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin <repo_link>
git push -u origin main
```
