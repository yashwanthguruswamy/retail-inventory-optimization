# Retail Inventory Optimization

A data analytics project to forecast SKU-level demand and optimize inventory restocking using Python and visualization tools.

## Objective
Forecast product demand and identify at-risk SKUs in a retail inventory dataset to optimize restocking decisions and reduce stockouts.

## 📂 Data Source
Simulated data inspired by [Kaggle Multi-category eCommerce Behavior Dataset](https://www.kaggle.com/datasets/mkechinov/ecommerce-behavior-data-from-multi-category-store)


## Tools Used
- Python (Pandas, Seaborn, Matplotlib)
- Jupyter Notebook
- CSV-based simulation data

## Techniques
- Rolling averages (7-day moving)
- SKU-level grouping and summary stats
- Inventory vs. reorder point comparison
- Heatmaps and bar plots for visualization

## Outputs
- SKU summary table with reorder rate and recommendations
- Inventory health heatmaps
- Visual dashboards for Units Sold per SKU

## 📂 Project Structure
```
retail-inventory-optimization/
│ └── retail_inventory_data.csv
│ └── retail_inventory_analysis.ipynb
│ ├── inventory_sku_summary.csv
│ ├── units_sold_per_sku.png
│ └── restock_recommendation_heatmap.png
└── README.md
```
### 📸 Sample Visuals

### Dashboard Overview
![Inventory Dashboard](inventory_dashboard.png)

---

## 🔗 Live Tableau Dashboard
[View on Tableau Public](https://public.tableau.com/views/RetailInventoryOptimizationDashboard/Inventory_dashboard)

