📊 Data Analysis Projects

This repository contains multiple end-to-end data analysis workflows across diverse domains. Each dataset is explored, cleaned, and analyzed with reproducible Python workflows, visualizations, and insights.

Datasets Included
EV Sales Historical Cars  
Electric vehicle adoption trends across countries (2010–2023). Includes sales, stock, and market share for BEV, PHEV, and FCEV.

Heart Disease Prediction  
Patient health records with attributes like age, cholesterol, blood pressure, ECG results, and heart disease presence/absence.

Stock Market Data  
Daily OHLC (Open, High, Low, Close) data for major tickers (AAPL, MSFT, NFLX, GOOG) with volume and adjusted close.

Indian Rainfall Dataset (District-wise Daily Measurements)  
Large-scale rainfall data across Indian districts. (Due to file size, processed in chunks.)

Udemy Courses Dataset  
Online course metadata including subject, price, subscribers, and ratings. (Large dataset handled with sampling and aggregation.)

🔧 Workflow Overview
Data Preparation

Import datasets using pandas

Handle missing values, duplicates, and outliers

Standardize column names and data types

Exploratory Data Analysis (EDA)

Summary statistics and distributions

Correlation analysis

Visualizations with matplotlib and seaborn

Domain-Specific Insights

EV Sales: Growth trends, country comparisons, BEV vs PHEV adoption

Heart Disease: Feature importance, risk factor distributions

Stocks: Price trends, moving averages, volatility analysis

Rainfall: Seasonal patterns, district-level aggregation

Udemy Courses: Popular subjects, pricing vs subscribers, ratings impact

Advanced Analytics

Time-series forecasting (EV sales, stock prices, rainfall)

Classification models (Heart disease prediction)

Regression models (Udemy course subscribers vs features)

Reporting

Visual dashboards

Exported figures with clear titles and captions

Jupyter notebooks for reproducibility

📂 Repository Structure
Code
Data_Analysis/
│
├── datasets/               # Raw and cleaned datasets
├── notebooks/              # Jupyter notebooks for each dataset
├── scripts/                # Modular Python scripts
├── reports/                # Generated plots and summaries
└── README.md               # Project documentation
🚀 Getting Started
Clone the repository:

bash
git clone https://github.com/Ramchethan03/Data_Analysis.git
cd Data_Analysis
Install dependencies:

bash
pip install -r requirements.txt
Explore notebooks:

bash
jupyter notebook notebooks/
📈 Tools & Libraries
Python (pandas, numpy, matplotlib, seaborn, scikit-learn, statsmodels)

Jupyter Notebook for interactive analysis

GitHub for version control and collaboration

✨ Highlights
Modular, reproducible workflows

Clear documentation of preprocessing steps

Visual storytelling with charts and dashboards

Domain-specific insights for business and research use

