# UK E-Commerce Data Analysis

<div align="center">
  <a href="https://github.com/your-username/ecommerce_analytics/issues">
    <img src="https://img.shields.io/github/issues/your-username/ecommerce_analytics.svg" alt="Issues">
  </a>
  <a href="https://github.com/your-username/ecommerce_analytics/stargazers">
    <img src="https://img.shields.io/github/stars/your-username/ecommerce_analytics.svg" alt="Stargazers">
  </a>
</div>

<br />

This project presents a comprehensive end-to-end analysis of a UK-based e-commerce dataset containing transactions from December 2010 to December 2011. The analysis covers data cleaning, exploratory data analysis (EDA), and advanced analytical techniques to derive actionable business insights.

---

## 📂 Project Structure

The project is organized into a clear directory structure to separate data from the analytical notebooks.

```
ecommerce_analytics/
├── data/
│   └── data.csv
├── notebooks/
│   ├── 01_exploratory_data_analysis.ipynb
│   ├── 02_rfm_customer_segmentation.ipynb
│   ├── 03_geographic_sales_analysis.ipynb
│   ├── 04_market_basket_analysis.ipynb
│   └── 05_sales_forecasting.ipynb
└── README.md
```

---

## 📖 Notebook Descriptions

The analysis is broken down into a series of Jupyter Notebooks, each focusing on a specific aspect of the data. They are numbered to suggest a logical order of progression.

### 1. `01_exploratory_data_analysis.ipynb`
This notebook covers the initial data loading, cleaning, and exploratory analysis. It addresses data quality issues (nulls, invalid entries) and provides initial insights into sales trends, top products, and customer behavior.

### 2. `02_rfm_customer_segmentation.ipynb`
This notebook implements RFM (Recency, Frequency, Monetary) analysis to segment customers into meaningful groups like "Champions," "At-Risk," and "New Customers." This is a powerful technique for targeted marketing.

### 3. `03_geographic_sales_analysis.ipynb`
Focuses on analyzing sales performance by country. It uses a choropleth map to visualize the global distribution of revenue and identify key international markets.

### 4. `04_market_basket_analysis.ipynb`
This notebook uses the Apriori algorithm to perform market basket analysis, uncovering association rules between products that are frequently purchased together.

### 5. `05_sales_forecasting.ipynb`
Implements time series forecasting using the Prophet library to predict future sales revenue based on historical trends and seasonality.

---

## 🚀 Getting Started

1.  **Clone the repository:**
    ```sh
    git clone https://github.com/your-username/ecommerce_analytics.git
    ```
2.  **Install dependencies:**
    Ensure you have pandas, numpy, plotly, mlxtend, and prophet installed.
3.  **Run the notebooks:**
    Navigate to the `notebooks/` directory and open the Jupyter Notebooks to explore the analysis.