# Sales Analytics & Forecasting Project

This project demonstrates an end-to-end sales analytics and forecasting solution using **Azure Data Factory, Synapse Analytics, Databricks, Python (Pandas, Prophet)** for ETL, data transformation, and machine learning, and **Power BI** for interactive business dashboards. The workflow is inspired by enterprise-grade Azure architectures and includes both cloud and local implementations for accessibility and speed.

## Project Overview

**Objective:**
Analyze and forecast retail sales data, visualize trends, and build a resume-worthy analytics dashboard using Azure and local tools.

**Dataset:**
- Walmart Sales Forecasting Dataset ([Kaggle link](https://www.kaggle.com/c/walmart-recruiting-store-sales-forecasting/data))
- File used: `train.csv` (contains store, department, date, and weekly sales)

## Steps

### 1. Azure Data Preparation & ETL
- Upload raw sales data (`train.csv`) to Azure Blob Storage/Data Lake.
- Use **Azure Data Factory** to automate ETL: move data from Blob Storage to **Azure Synapse Analytics** tables.
- Transform and aggregate data in Synapse using SQL.

### 2. Data Transformation (Local & Cloud)
- Load and clean the sales dataset using Python and Pandas (local or Databricks).
- Aggregate sales by store and by month.
- Export results as CSVs for visualization.

### 3. Forecasting (Machine Learning)
- Use **Azure Databricks** (or local Python) with Facebook Prophet to forecast sales for the next 3 months.
- Export forecast results as CSV.

### 4. Visualization (Power BI)
- Import CSVs into Power BI Desktop.
- Create interactive dashboards:
  - Sales by Store (bar chart)
  - Monthly Sales Trend (line chart)
  - Forecast vs Actual (line chart with confidence interval)
- Save the dashboard as a `.pbix` file for sharing and portfolio use.
<img width="1099" height="623" alt="image" src="https://github.com/user-attachments/assets/449bbbb8-09bf-45d1-9c83-a23c6f393fa5" />

## How to Run

1. **Download the Dataset:**
   - Get `train.csv` from Kaggle and place it in the project folder or upload to Azure Blob Storage.

2. **Azure ETL & Transformation:**
   - Use Data Factory to move data to Synapse and run SQL transformations.

3. **Run the Jupyter Notebook or Databricks Notebook:**
   - Open `Sales_Analytics_Forecasting.ipynb` and run all cells (locally or in Databricks).
   - This will generate `store_sales.csv`, `monthly_sales.csv`, and `sales_forecast.csv`.

4. **Open Power BI Desktop:**
   - Import the generated CSVs.
   - Build the dashboard visuals as described above.
   - Save your dashboard as `Sales_Analytics_Forecasting.pbix`.

## Resume-Ready Description

> Designed and implemented a sales analytics and forecasting solution using **Azure Data Factory, Synapse Analytics, Databricks, Python (Pandas, Prophet)** for ETL, transformation, and machine learning, and **Power BI** for interactive dashboards. Aggregated, visualized, and forecasted retail sales data, delivering actionable insights and predictive trends using both cloud and local tools.

## Files Included
- `Sales_Analytics_Forecasting.ipynb` — Jupyter notebook for ETL, transformation, and forecasting
- `train.csv` — Raw sales data (not included, download from Kaggle)
- `store_sales.csv` — Aggregated sales by store
- `monthly_sales.csv` — Monthly sales trend
- `sales_forecast.csv` — Prophet forecast results
- `Sales_Analytics_Forecasting.pbix` — Power BI dashboard (save after building)
- Azure pipeline and SQL scripts (if applicable)

## Credits
- Project inspired by MAQ Software's Azure analytics workflow
- Dataset: Walmart Sales Forecasting (Kaggle)

---

**Quick Build Plan:**
1. Download dataset
2. Upload to Azure & run ETL
3. Run notebook (local or Databricks)
4. Import CSVs to Power BI
5. Build and save dashboard

For more details, see the notebook and dashboard files.
