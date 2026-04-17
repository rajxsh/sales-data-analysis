# Sales Data Analysis using Python

## Project Overview
Analyzed 49,000+ online sales records to identify top products and top customers, providing actionable business insights.

## Tools Used
- Python (Pandas, Matplotlib)
- Jupyter Notebook
- Git & GitHub

## Key Steps
1. **Data Cleaning** – Handled missing values in CustomerID, ShippingCost, etc.
2. **Feature Engineering** – Created `Total Sales` = Quantity × UnitPrice × (1-Discount)
3. **Analysis** – Grouped by product and customer to find top 10 performers
4. **Visualization** – Generated bar charts for clear presentation

## Results
- Top 10 products by sales (see `visuals/top_10_products.png`)
- Top 10 customers by purchase volume (see `visuals/top_10_customers.png`)

## How to Run
1. Clone this repo
2. Install dependencies: `pip install pandas matplotlib jupyter`
3. Launch Jupyter: `jupyter notebook`
4. Open `sales_analysis.ipynb` and run all cells

## Business Impact
- Marketing can focus on top products
- Sales team can create loyalty programs for top customers
- Analysis can be automated monthly with new data
