# Sales Analytics & Forecasting Project

This project demonstrates an end-to-end sales analytics and forecasting solution using Python (Pandas, Prophet) for ETL, data transformation, and machine learning, and Power BI for interactive business dashboards. The workflow is inspired by enterprise-grade Azure architectures, but implemented locally for accessibility and speed.

## Project Overview

**Objective:**
Analyze and forecast retail sales data, visualize trends, and build a resume-worthy analytics dashboard.

**Dataset:**
- Walmart Sales Forecasting Dataset ([Kaggle link](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting/data))
- File used: `train.csv` (contains store, department, date, and weekly sales)

## Steps

### 1. Data Preparation (ETL & Transformation)
- Load and clean the sales dataset using Python and Pandas.
- Aggregate sales by store and by month.
- Export results as CSVs for visualization.

### 2. Forecasting (Machine Learning)
- Use Facebook Prophet to forecast sales for the next 3 months.
- Export forecast results as CSV.

### 3. Visualization (Power BI)
- Import CSVs into Power BI Desktop.
- Create interactive dashboards:
  - Sales by Store (bar chart)
  - Monthly Sales Trend (line chart)
  - Forecast vs Actual (line chart with confidence interval)
- Save the dashboard as a `.pbix` file for sharing and portfolio use.

## How to Run

1. **Download the Dataset:**
   - Get `train.csv` from Kaggle and place it in the project folder.

2. **Run the Jupyter Notebook:**
   - Open `Sales_Analytics_Forecasting.ipynb` and run all cells.
   - This will generate `store_sales.csv`, `monthly_sales.csv`, and `sales_forecast.csv`.

3. **Open Power BI Desktop:**
   - Import the generated CSVs.
   - Build the dashboard visuals as described above.
   - Save your dashboard as `Sales_Analytics_Forecasting.pbix`.

## Resume-Ready Description

> Designed and implemented a sales analytics and forecasting solution using Python (Pandas, Prophet) for ETL and machine learning, and Power BI for interactive dashboards. Aggregated, visualized, and forecasted retail sales data, delivering actionable insights and predictive trends.

## Files Included
- `Sales_Analytics_Forecasting.ipynb` — Jupyter notebook for ETL, transformation, and forecasting
- `train.csv` — Raw sales data (not included, download from Kaggle)
- `store_sales.csv` — Aggregated sales by store
- `monthly_sales.csv` — Monthly sales trend
- `sales_forecast.csv` — Prophet forecast results
- `Sales_Analytics_Forecasting.pbix` — Power BI dashboard (save after building)

## Credits
- Project inspired by MAQ Software's Azure analytics workflow
- Dataset: Walmart Sales Forecasting (Kaggle)

---

**Quick Build Plan:**
1. Download dataset
2. Run notebook
3. Import CSVs to Power BI
4. Build and save dashboard

For more details, see the notebook and dashboard files.
