# 📊 Samsung Global Product Sales — Exploratory Data Analysis

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-Numerical-013243?logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Visualization-orange)
![Seaborn](https://img.shields.io/badge/Seaborn-Statistical%20Plots-4C72B0)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626?logo=jupyter&logoColor=white)
![Kaggle](https://img.shields.io/badge/Kaggle-Dataset-20BEFF?logo=kaggle&logoColor=white)

An end-to-end Exploratory Data Analysis (EDA) on Samsung's Global Product Sales Dataset — covering data cleaning, type fixing, statistical analysis, and advanced visualizations of revenue trends by product category, customer age group, and region.

---

## 📌 Table of Contents

- [Overview](#-overview)
- [Dataset](#-dataset)
- [Analysis Highlights](#-analysis-highlights)
- [Visualizations](#-visualizations)
- [Tech Stack](#️-tech-stack)
- [Project Structure](#-project-structure)
- [How to Run](#-how-to-run)
- [Key Insights](#-key-insights)
- [Author](#-author)

---

## 🌍 Overview

This project performs a comprehensive EDA on Samsung's global product sales data to uncover patterns in revenue generation, customer demographics, and regional performance. The analysis moves from raw data through cleaning, to statistical summaries, and finally to rich visualizations that tell the story of Samsung's global sales trends.

**Goal:** Extract meaningful, actionable insights from Samsung's product sales data that reveal which products, customer segments, and regions drive the most revenue.

---

## 📂 Dataset

- **Source:** [Samsung Global Product Sales Dataset — Kaggle](https://www.kaggle.com/datasets/ashyou09/samsung-global-product-sales-dataset)
- **Format:** CSV
- **Notebook:** `samsung-global-product-dataset-analyze.ipynb` (1,752 lines · 622 KB)

### Key Features / Columns

| Column | Description |
|--------|-------------|
| `Product_Category` | Type of Samsung product (e.g., Smartphones, TVs, Tablets) |
| `Region` | Global sales region (e.g., Asia, Europe, North America) |
| `Customer_Age` / `Age_Group` | Buyer's age or grouped age bracket |
| `Revenue` | Total revenue generated per transaction |
| `Units_Sold` | Number of units sold per record |
| `Customer_Segment` | Market segment classification of customers |
| `Date` / `Year` / `Month` | Temporal data for trend analysis |
| `Price` | Product price per unit |

---

## 🔍 Analysis Highlights

### 🧹 1. Data Cleaning & Type Fixing
- Identified and corrected incorrect data types across columns
- Handled missing values and null entries
- Standardized categorical variables (regions, product names)
- Converted date columns to proper `datetime` format for time-series analysis

### 📊 2. Descriptive Statistics
- Summary statistics: mean, median, standard deviation, min/max for all numeric columns
- Skewness and kurtosis analysis to understand revenue distribution
- Value counts and frequency analysis for categorical columns

### 🧮 3. Revenue Analysis
- **Revenue by Product Category** — which Samsung product line generates most revenue
- **Revenue by Customer Age Group** — which demographic drives the most sales
- **Revenue by Region** — geographic breakdown of global sales performance
- **Revenue by Customer Segment** — B2B vs B2C and other segment comparisons

### 📈 4. Advanced Visualizations
- Revenue heatmaps for identifying sales patterns across dimensions
- Trend analysis across time periods
- Distribution plots for revenue and units sold
- Correlation analysis between key numerical features

---

## 📉 Visualizations Used

| Chart Type | Purpose |
|---|---|
| Bar Charts | Revenue comparison by product category and region |
| Heatmaps | Sales pattern detection across time and product dimensions |
| Distribution Plots | Understanding revenue spread and skewness |
| Box Plots | Outlier detection in pricing and revenue |
| Line Charts | Revenue trends over time |
| Pie / Donut Charts | Market share by product and region |
| Count Plots | Frequency of transactions by segment and category |
| Correlation Matrix | Relationship between numerical features |

---

## 🛠️ Tech Stack

```
Python 3.x
├── pandas          # Data loading, cleaning, manipulation
├── numpy           # Numerical operations, skewness calculations
├── matplotlib      # Base plotting and chart customization
└── seaborn         # Statistical visualizations and heatmaps
```

---

## 📁 Project Structure

```
Samsung-Global-Product-DataSet-Analyze/
│
├── samsung-global-product-dataset-analyze.ipynb   # Full EDA notebook
│                                                   # 1,752 lines · 622 KB
│                                                   # Data cleaning → Stats → Visualizations
│
└── README.md                                       # Project documentation
```

> **Note:** The dataset CSV is not included in the repo. Download it from [Kaggle](https://www.kaggle.com/datasets/ashyou09/samsung-global-product-sales-dataset) and place it in the project root before running the notebook.

---

## 🚀 How to Run

### 1. Clone the Repository
```bash
git clone https://github.com/Azharaliii/Samsung-Global-Product-DataSet-Analyze.git
cd Samsung-Global-Product-DataSet-Analyze
```

### 2. Install Dependencies
```bash
pip install pandas numpy matplotlib seaborn jupyter
```

### 3. Download the Dataset
- Go to [Kaggle Dataset](https://www.kaggle.com/datasets/ashyou09/samsung-global-product-sales-dataset)
- Download the CSV file
- Place it in the project root directory

### 4. Launch the Notebook
```bash
jupyter notebook samsung-global-product-dataset-analyze.ipynb
```

---

## 💡 Key Insights

- 📱 **Product Performance** — Smartphones lead revenue generation across all regions compared to other Samsung product categories
- 🌏 **Regional Trends** — Revenue heatmaps reveal strong performance in specific global markets, with Asia and North America as key drivers
- 👥 **Customer Demographics** — Specific age groups show significantly higher purchasing activity, helping identify Samsung's core buyer persona
- 📅 **Seasonal Patterns** — Revenue heatmaps uncover time-based sales cycles useful for inventory and marketing planning
- 📊 **Revenue Distribution** — Skewness analysis reveals that a small percentage of transactions account for a disproportionately large share of total revenue

---

## 🔮 Future Improvements

- 🤖 Add predictive modeling (Linear Regression / XGBoost) for revenue forecasting
- 📍 Geographic map visualizations using `folium` or `plotly`
- 📊 Interactive dashboard with `Plotly` or `Streamlit`
- 🔁 Automate data pipeline for updated datasets
- 📈 Customer segmentation using K-Means clustering

---

## 👤 Author

**Azhar Ali Soomro**
[![GitHub](https://img.shields.io/badge/GitHub-Azharaliii-181717?logo=github&logoColor=white)](https://github.com/Azharaliii)
[![Kaggle](https://img.shields.io/badge/Kaggle-azharalisoomro-20BEFF?logo=kaggle&logoColor=white)](https://www.kaggle.com/azharalisoomro)

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

---

⭐ **If you found this analysis useful, please give it a star!**
