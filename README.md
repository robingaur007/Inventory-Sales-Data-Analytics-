# Inventory Sales Data Analytics

This project analyzes inventory and sales data to help retail and
Wholesale businesses improve profitability, optimize vendor performance,
understand bulk purchase impact, and increase inventory efficiency.\
It includes Exploratory Data Analysis (EDA), vendor performance
evaluation, Python-based data processing, and a Power BI dashboard.

## Project Objectives

-   Identify **underperforming brands/SKUs** that need pricing or
    promotional improvements.\
-   Determine **top-performing vendors** based on revenue and gross
    profit.\
-   Analyze the **impact of bulk purchasing** on unit cost and profit
    margins.\
-   Evaluate **inventory turnover** to reduce holding costs and improve
    efficiency.\
-   Compare **profitability differences** between high-performing and
    low-performing vendors.

## Repository Structure

    │
    ├── Exploratory Data Analysis.ipynb         # EDA notebook
    ├── Vendor Performance Analysis.ipynb       # Vendor performance analysis
    ├── Vendor Performance Report.pdf           # Final PDF report
    ├── vendor_performance.pbix                 # Power BI dashboard
    ├── vendor_sales_summary.csv                # Processed dataset
    ├── get_vendor_summary.py                   # Vendor summary generator script
    ├── ingestion_db.py                         # Data ingestion & cleaning script
    └── README.md

## Jupyter Notebooks Overview

### **1. Exploratory Data Analysis (EDA)**

-   Data cleaning & preprocessing\
-   Sales trends and distribution\
-   Brand- and SKU-level performance\
-   Stock movement analysis\
-   Visual insights for decision-making

### **2. Vendor Performance Analysis**

-   Vendor-wise sales, gross profit, and margin analysis\
-   Identification of high- and low-performing vendors\
-   Profitability scoring and comparison\
-   Insights used in Power BI dashboard

## Reports & Dashboards

### **Vendor Performance Report (PDF)**

A summarized report containing key findings, charts, and
recommendations.

### **Power BI Dashboard (.pbix)**

An interactive dashboard that includes: - Vendor performance metrics\
- Cost and margin comparisons\
- Category- and brand-level insights\
- Visual filters for dynamic exploration

## Python Scripts

### **get_vendor_summary.py**

Generates vendor-level summary including: - Total sales\
- Quantity sold\
- Margin percentage\
- Vendor rankings

### **ingestion_db.py**

-   Loads raw CSV data\
-   Cleans and preprocesses fields\
-   Performs transformations for analysis

## How to Use This Project

### **1. Clone the Repository**

``` bash
git clone https://github.com/robingaur007/Inventory-Sales-Data-Analytics-.git
cd Inventory-Sales-Data-Analytics-
```

### **2. Open Jupyter Notebooks**

``` bash
jupyter notebook
```

### **3. Open Power BI Dashboard**

Open `vendor_performance.pbix` using **Power BI Desktop**.

### **4. Run Python Scripts (Optional)**

``` bash
python get_vendor_summary.py
```

## Key Insights (Sample)

-   Top vendors contribute a major portion of revenue and gross profit.\
-   Bulk purchasing lowers unit cost but may reduce margin for some
    SKUs.\
-   Several brands show low inventory turnover → require markdown or
    promotions.\
-   Vendor profitability varies significantly → potential negotiation
    opportunities.\
-   High-performing vendors maintain consistent pricing and margin
    structure.

## Tech Stack

-   **Python** (pandas, numpy, matplotlib, seaborn)\
-   **Jupyter Notebook**\
-   **Power BI**\
-   **CSV Data Processing**\
-   **Data Cleaning & Statistical Analysis**

## Contributing

Pull requests and suggestions are welcome.

## License

This project currently does not include a license.\
You may add MIT or any other license based on your preference.
