# EDA on Retail Sales Data — Level 1

## Objective
Perform a thorough Exploratory Data Analysis on a retail sales dataset to uncover patterns, customer behaviour trends, and actionable business insights.

## Tech Stack
- Python 3.x
- pandas
- matplotlib
- seaborn
- Jupyter Notebook

## Project Structure
```
retail-eda/
├── README.md
├── retail_eda.ipynb       # Main analysis notebook
├── requirements.txt
└── data/
    └── retail_sales.csv   # Place your dataset here
```

## Dataset
**retail_sales_dataset.csv** — downloaded from [Kaggle: Retail Sales Dataset](https://www.kaggle.com/datasets/mohammadtalib786/retail-sales-dataset)

Columns: `Transaction ID, Date, Customer ID, Gender, Age, Product Category, Quantity, Price per Unit, Total Amount`

## Setup

1. Install dependencies:
```bash
pip install -r requirements.txt
```

2. Place `retail_sales_dataset.csv` in the same folder as the notebook.

3. Launch the notebook:
```bash
jupyter notebook retail_eda.ipynb
```

**In Google Colab:** Upload the notebook + CSV, then click Runtime → Run all.

## Feature Checklist
- [x] Load dataset and perform initial inspection: shape, column dtypes, null value check
- [x] Descriptive statistics: mean, median, mode, standard deviation for all numerical columns
- [x] Time series analysis: plot monthly and quarterly sales trends using line charts
- [x] Customer demographics analysis: distribution of customer age groups, gender breakdown
- [x] Product analysis: top 10 best-selling products; revenue by product category (bar chart)
- [x] Heatmap: correlation matrix between numerical variables
- [x] Additional visualisation revealing a non-obvious insight
- [x] Markdown cells throughout the notebook with written observations after each chart
- [x] Conclusion section: at least 3 specific, actionable business recommendations

## Dataset Notes
The notebook is built to work with common retail sales CSV structures. Expected columns (adjust cell 2 if your dataset differs):
- `Date` or `Order Date` — transaction date
- `Sales` or `Revenue` — sales amount
- `Quantity` — units sold
- `Category` or `Product Category` — product category
- `Product Name` — individual product
- `Customer Age` or `Age` — customer age
- `Gender` — customer gender

## Key Insights Covered
- Monthly and quarterly revenue trends
- Top revenue-generating product categories
- Customer age group and gender distribution
- Correlation between sales, quantity, and other numerical features
- Profit margin analysis by category (bonus insight)
