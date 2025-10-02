E-commerce Sales Data Analysis (India)

Project Overview
This project analyzes E-commerce sales data from multiple platforms (Amazon, Flipkart, Myntra, Ajio, Paytm, Snapdeal, etc.) to uncover insights on sales trends, pricing strategies, platform comparisons, and discount patterns.
The goal is to:
Clean and preprocess raw sales and pricing data.
Perform Exploratory Data Analysis (EDA) to identify trends.
Compare product pricing across platforms.
Visualize sales performance and profitability opportunities.
Highlight potential business insights for decision-making.

Dataset
The dataset comes from Kaggle: Unlock Profits with E-Commerce Sales Data.
It contains multiple CSV files, including:
Amazon Sale Report.csv → Order-level Amazon sales data.
International Sale Report.csv → International marketplace sales.
May-2022.csv → Sales data for May 2022.
Expense IIGF.csv → Expense report.
P & L March 2021.csv → Product pricing across multiple platforms.
Cloud Warehouse Comparison Chart.csv → Warehouse costs and comparisons.
Sale Report.csv → Overall aggregated sales.
 Note: Due to licensing restrictions, the raw dataset is not included in this repository. Please download it directly from Kaggle.

Tools & Libraries
The project is built using Python in Google Colab.
Key libraries:
pandas → Data manipulation & cleaning
numpy → Numerical operations
matplotlib & seaborn → Visualizations
plotly → Interactive charts
missingno → Missing data visualization
kagglehub → Kaggle dataset integration
holidays → Marking special events in sales analysis

Key Insights & Visualizations
Some of the EDA and analysis performed:
Daily Sales Trends → Total sales quantity & amount per day.
Category-Level Analysis → Which product categories perform best.
Discount Analysis → Comparing MRP Old vs Final MRP Old.
Platform Price Comparisons → Amazon vs Flipkart vs Myntra, etc.
Weight vs Price Analysis → Correlation of product weight with pricing.
Profitability & Arbitrage Opportunities → Identifying products priced significantly lower on one platform compared to others.
Outlier Detection → Spotting unusually high/low pricing.

Example Visualizations :
Sales trends over time
Category-wise revenue contribution
Heatmap of price correlations across platforms
Discount distribution
