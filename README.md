# Sales Data Analysis Dashboard

## Project Overview
This project analyzes a retail sales dataset to uncover insights into **revenue trends, top-performing products, seasonal patterns, and customer behavior**. The goal is to support data-driven decision-making through **EDA (Exploratory Data Analysis)** and interactive dashboards.

## Key Features
- Data cleaning and preprocessing using **Python (pandas, numpy)**
- Exploratory Data Analysis (EDA) with **Matplotlib/Seaborn**
- KPIs: Monthly revenue, top products, customer segmentation
- Interactive dashboard built with **Tableau/Power BI**

## Tech Stack
- **Languages**: Python
- **Libraries**: pandas, numpy, matplotlib, seaborn
- **Tools**: Jupyter Notebook,Power BI


## Project Structure
```
sales-data-analysis/
│
├── data/
│   ├── raw/                 # Original dataset (CSV from Kaggle, etc.)
│   └── processed/           # Cleaned dataset after preprocessing
│
├── notebooks/
│   └── sales_analysis.ipynb # Jupyter Notebook with EDA & visualizations
│
├── dashboard/
│   ├── tableau_dashboard.twbx   # If using Tableau
│   └── powerbi_dashboard.pbix   # If using Power BI
│
├── scripts/
│   ├── data_cleaning.py     # Script to clean & preprocess data
│   └── visualization.py     # Script to generate plots
│
├── requirements.txt         # Python dependencies
└── README.md                # Project documentation
```

## How to Run
1. Clone this repo
   ```bash
   git clone https://github.com/your-username/sales-data-analysis.git
   cd sales-data-analysis
   ```
2. Install dependencies
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter notebook to reproduce the analysis.
4. Open to explore the interactive dashboards.

## Insights
- Revenue peaks during holiday seasons (Nov–Dec).
- Top 10 products contribute ~40% of total sales.
- Repeat customers generate higher average order values compared to new customers.
