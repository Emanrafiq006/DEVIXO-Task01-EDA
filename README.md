# DEVIXO Solutions – Data Science Internship Task 01

## Exploratory Data Analysis on Supermarket Sales

This project was completed for the **DEVIXO Solutions Data Science Internship Program – Task 01**. The goal is to explore a real-world supermarket transaction dataset, clean the data, find patterns, create meaningful visualizations and turn the findings into practical business recommendations.

### Dataset
The project uses the **Supermarket Sales** dataset from Kaggle. It contains 1,000 transactions and 17 columns covering branches, cities, customer type, gender, product lines, prices, quantities, payment methods, sales totals and ratings. The dataset covers January–March 2019.

Source: https://www.kaggle.com/datasets/aungpyaeap/supermarket-sales

### Technologies
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook / Google Colab

### Analysis performed
- Dataset structure and data types
- Missing-value and duplicate checks
- Date/time conversion and feature creation
- Numerical and categorical feature analysis
- Correlation matrix
- 12+ business-focused visualizations
- Business insights
- Practical recommendations

### Repository structure
```text
DEVIXO_EDA_Task01/
├── data/
│   ├── supermarket_sales.csv
│   └── DOWNLOAD_DATASET.txt
├── notebook/
│   └── DEVIXO_Task01_EDA.ipynb
├── report/
│   └── DEVIXO_Task01_EDA_Report.pdf
├── screenshots/
├── visualizations/
├── README.md
└── requirements.txt
```

### How to run
1. Download the Kaggle CSV and save it as `data/supermarket_sales.csv`.
2. Open `notebook/DEVIXO_Task01_EDA.ipynb` in Jupyter Notebook or Google Colab.
3. Run the cells from top to bottom.
4. The chart images will be saved in the `visualizations` folder.

### Key findings
- The dataset contains 1,000 transactions with 17 original columns.
- Average transaction value is about **$322.97** and average customer rating is about **6.97/10**.
- Food and Beverages is among the strongest product lines by revenue.
- Branch C / Naypyitaw is the strongest branch by total sales.
- Payment behaviour is spread across cash, E-wallet and credit card.
- Quantity and transaction value have a strong positive relationship.

### Recommendations
1. Protect inventory for high-performing product lines.
2. Use targeted promotions for weaker categories.
3. Improve member-only offers and loyalty engagement.
4. Schedule staff according to peak transaction hours.
5. Use ratings to identify customer-experience issues.

### Note
The notebook is the main source of analysis. Run it with the CSV to reproduce the calculations and visualizations.
