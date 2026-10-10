E-Commerce Sales Data Analysis

Comprehensive sales data analysis project covering data cleaning, transformation, statistical analysis, and business intelligence dashboards for an e-commerce platform.

📋 Project Overview

This project provides an end-to-end analysis of sales transactions, customer behavior, product performance, and regional sales trends. The dataset contains over 25,000+ orders with comprehensive data cleaning, feature engineering, and advanced analytics.

Key Highlights
✅ 25,875 orders analyzed across multiple regions
✅ Data Cleaning: Removed inconsistencies and standardized formats
✅ Feature Engineering: Added derived metrics (profit, delivery days, seasonal analysis)
✅ Business Intelligence: Regional performance, product profitability, customer segmentation
✅ Interactive Dashboard: Visual KPIs and trend analysis
📂 Dataset Description
Raw Data
Sales Orders (Main): 25,875 records × 23 attributes
Key Fields: Order ID, Customer ID, Product ID, Employee ID, Order Date, Quantities, Pricing, Payment Methods, Delivery Status, Ratings, Campaign ID
Cleaned & Processed Data
Sales Orders (Cleaned): 24,355 records × 29 attributes
Added Features:
Monthly aggregation
Profit calculations (Total Amount - COGS)
Delivery performance metrics
Product category & subcategory
Unit cost analysis
Supporting Tables
Products: 5,175 products with pricing, inventory, ratings, and supplier information
Categories: Multiple product categories and subcategories
Regional Data: Sales distributed across multiple regions and cities
🧹 Data Cleaning Process
Issues Identified & Resolved
Date Format Inconsistencies:
Mixed date formats (YYYY-MM-DD and DD-MMM-YYYY)
Standardized to consistent datetime format
Duplicate Records:
Removed ~1,500 duplicate entries
Validated Order IDs for uniqueness
Missing Values:
Handled null values in categorical columns
Imputed missing numeric values with appropriate statistics
Data Type Corrections:
Converted price columns from text to numeric
Fixed date columns from object to datetime
Outlier Detection:
Identified unusual delivery times
Flagged extremely high/low prices and discounts
Quality Metrics
Data Retention Rate: 94.1% (24,355 / 25,875 rows)
Data Completeness: 98.7% of fields populated
Duplicate Removal: 1,520 records cleaned
📈 Analysis & Insights
Sales Performance
Total Orders: 24,355
Regional Distribution: Multi-region coverage with varying sales volumes
Peak Ordering Periods: Seasonal trends identified
Customer Rating Analysis: 1-5 star rating distribution
Product Analysis
Product Categories: Electronics, Software, Services, and more
Top Performers: High-rated products with strong sales volumes
Profit Margins: Category-wise profitability analysis
Inventory Health: Stock quantity vs. reorder levels
Payment & Delivery Metrics
Payment Methods: Multiple payment channels analyzed
Delivery Performance: Average delivery time by region
Order Status Distribution: Success, cancelled, and returned orders
Return Rate Analysis: Product return patterns
Customer Insights
Customer Segmentation: By purchase frequency and value
Regional Performance: City and region-wise sales breakdown
Campaign Effectiveness: Campaign ID correlation with sales
🛠️ Technologies & Tools
Data Processing
Excel/XLSX: Data storage and preliminary analysis
Python: (Recommended for advanced analysis)
Pandas: Data manipulation
NumPy: Numerical analysis
Matplotlib/Seaborn: Visualization
Analysis Tools
Pivot Tables: Multi-dimensional data analysis
Statistical Functions: Descriptive and inferential statistics
Dashboard: Interactive KPI visualization
📊 File Structure
project/
├── FİNAL_PROJECT.xlsx
│   ├── sales orders main         # Raw sales data (25,875 records)
│   ├── Sales_Orders cleaned      # Cleaned & enriched data (24,355 records)
│   ├── Products                  # Product master data (5,175 products)
│   ├── pivot                     # Pivot table analysis
│   ├── DASHBOARD                 # Executive KPI dashboard
│   ├── düzəlişlər               # Data cleaning notes (Turkish)
│   └── Problem haradadır        # Data quality issues log
🔍 Key Metrics & KPIs
Metric	Value	Insight
Total Orders	24,355	Core transaction volume
Data Quality	98.7%	High data completeness
Average Delivery Days	~7-10 days	Operational efficiency
Customer Satisfaction	1-5 stars	Quality feedback
Regional Coverage	Multiple	Distributed business
Product Count	5,175	Diverse inventory
🎯 Key Findings
✨ Strengths
✅ Consistent order processing across regions
✅ Diverse product portfolio with strong ratings
✅ Multiple payment channels for customer convenience
✅ Reasonable delivery timelines
🔧 Areas for Improvement
🔍 Analyze high return rates by product category
📈 Optimize delivery performance in slower regions
💰 Review pricing strategy for low-margin products
📊 Investigate customer rating factors
🚀 How to Use
1. Data Exploration
Open Sales_Orders cleaned sheet for prepared data
Review Products sheet for product details
Check DASHBOARD for executive summary
2. Pivot Analysis
Use pivot tables for:
Sales by region
Profit by product category
Delivery performance analysis
Payment method trends
3. Custom Analysis
Filter by date range, region, or product
Create custom calculations using formulas
Generate reports using pivot tables
📝 Data Dictionary
Sales Orders (Cleaned)
Order_ID: Unique order identifier
Order_Date: Date of order placement
month, year: Temporal dimensions
Customer_ID: Customer identifier
Product_ID: Product identifier
Quantity: Items ordered
Unit_Price_AZN: Price per unit in AZN
Discount_Percent: Applied discount percentage
Total_Amount_AZN: Final order amount
Profit AZN: Net profit after COGS
Delivery_Date: Actual delivery date
Delivery_Days: Days to deliver
Rating: Customer satisfaction (1-5)
Return_Flag: Return status (Yes/No)
Order_Status: Current order status
Products
Product_ID: Unique product code
Product_Name: Product description
Category, Subcategory: Product classification
Unit_Cost_AZN: Cost price
Unit_Price_AZN: Selling price
Margin_Percent: Profit margin
Stock_Quantity: Current inventory
Rating: Product rating (1-5)
Review_Count: Number of reviews
💡 Recommendations
Revenue Optimization
Focus on high-margin products
Investigate regional sales variations
Optimize discount strategies
Customer Experience
Improve delivery times in underperforming regions
Address factors affecting low ratings
Implement quality assurance checks
Operational Efficiency
Streamline inventory management
Reduce order cancellations
Improve return rate analysis
Data Enhancement
Implement real-time dashboard updates
Add predictive analytics for demand forecasting
Develop customer lifetime value models

📄 License

This project is for educational and business intelligence purposes.
