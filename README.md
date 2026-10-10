E-Commerce Sales Data Analysis

A comprehensive data analysis project covering data cleaning, transformation, and business intelligence insights for a multi-regional e-commerce platform. This dataset contains detailed sales transactions, customer behavior, product performance metrics, and regional analytics.

🎯 Project Overview

This project analyzes 25,875 sales orders across multiple regions and product categories. Through rigorous data cleaning and feature engineering, we've created a robust dataset for business intelligence, predictive analytics, and strategic decision-making.

Key Highlights
✅ 25,875 raw orders → 24,355 clean records (94.1% retention)
✅ 5,175 products analyzed with detailed profitability metrics
✅ 98.7% data completeness after cleaning process
✅ 6 additional features engineered for deeper analysis
✅ Interactive dashboards with regional and category insights
📊 Dataset Overview
Metric	Value	Details
Total Raw Orders	25,875	Original transaction records
Cleaned Orders	24,355	After duplicate/error removal
Product Count	5,175	Unique products in catalog
Data Retention	94.1%	Quality vs Quantity balance
Data Completeness	98.7%	Fields with valid data
Regional Coverage	8+ regions	Multi-city distribution
Time Period	2023-2026	3+ years of transactions
📁 Data Structure & Sheets
Sheet Name	Records	Columns	Purpose
Sales Orders Main	25,875	23	Raw sales data, original format
Sales Orders Cleaned	24,355	29	Processed data with engineered features
Products	5,175	18	Product master data, pricing, inventory
Pivot	—	—	Aggregated analysis by region/category
Dashboard	—	—	KPI metrics and visual summaries
düzəlişlər	Notes	—	Data cleaning documentation (Turkish)
🧹 Data Cleaning Process
Issues Identified & Resolved
Issue	Root Cause	Solution	Impact
Date Format Inconsistency	Mixed formats (YYYY-MM-DD, DD-MMM-YYYY)	Standardized to ISO 8601	✅ All dates normalized
Duplicate Records	Data entry errors, system duplicates	Identified & removed duplicates	Removed 1,520 rows
Missing Values	Incomplete data entry	Imputed with statistical methods	98.7% complete
Data Type Errors	Price stored as text	Converted to numeric columns	✅ Ready for calculations
Inconsistent Categories	Spelling variations, abbreviations	Standardized naming	✅ Unified categories
Data Quality Metrics
Metric	Before Cleaning	After Cleaning	Status
Total Records	25,875	24,355	✅ Cleaned
Data Completeness	94.2%	98.7%	✅ Enhanced
Duplicate Entries	1,520	0	✅ Removed
Null Values	3.2%	1.3%	✅ Reduced
Type Errors	Multiple	None	✅ Fixed
🔍 Core Data Fields
Sales Data Attributes
Field Name	Data Type	Description	Example
Order_ID	String	Unique order identifier	SO0012550
Order_Date	DateTime	Date order was placed	2023-12-20
Customer_ID	String	Customer reference	CUST001
Product_ID	String	Product reference	P01662
Quantity	Integer	Items ordered	12
Unit_Price_AZN	Float	Price per unit (AZN currency)	2,495.50
Discount_Percent	Float	Applied discount (0-100)	15.5
Total_Amount_AZN	Float	Order total amount	25,445.75
Tax_Amount_AZN	Float	Tax charged	3,063.00
Shipping_Cost_AZN	Float	Shipping charges	150.00
Profit_AZN	Float	Net profit (engineered)	5,234.50
Delivery_Days	Integer	Time to delivery	8
Delivery_Date	DateTime	Actual delivery date	2023-12-28
Rating	Float	Customer satisfaction (1-5)	4.5
Return_Flag	String	Product returned status	No/Yes
Payment_Method	String	Payment type used	Credit Card
Order_Status	String	Current order status	Completed
Region	String	Geographic region	Baku
City	String	City location	Baku
Product Attributes
Field	Type	Description
Product_ID	String	Unique product identifier
Product_Name	String	Product description
Category	String	Product category
Subcategory	String	Product subcategory
Brand	String	Product brand
Unit_Cost_AZN	Float	Cost price to company
Unit_Price_AZN	Float	Selling price
Margin_Percent	Float	Profit margin %
Stock_Quantity	Integer	Current inventory level
Reorder_Level	Integer	Minimum stock threshold
Rating	Float	Product rating (1-5)
Review_Count	Integer	Number of customer reviews
📈 Key Metrics & Analysis
Sales Performance
Metric	Value	Insight
Average Order Value	~1,050 AZN	Mid-range typical transaction
Total Revenue	25.5M+ AZN	Cumulative sales
Average Profit Margin	12-18%	Healthy profitability
Peak Sales Month	Seasonal pattern	Varies by category
Payment Success Rate	98.5%+	Reliable transactions
Delivery & Logistics
Metric	Value	Detail
Average Delivery Time	7-10 days	Regional average
On-Time Delivery Rate	~92%	Operational efficiency
Return Rate	10-15%	Product quality indicator
Shipping Cost Average	~150 AZN	Per order cost
Customer Experience
Metric	Value	Meaning
Average Customer Rating	3.5-4.0 stars	Good satisfaction
5-Star Rating %	~35%	Satisfied customers
1-Star Rating %	~15%	Dissatisfied customers
Review Engagement	Varies	Product dependent
🎯 Business Insights
Strengths ✅
Item	Details
Data Quality	98.7% completeness ensures reliable analysis
Product Diversity	5,175+ products across multiple categories
Regional Coverage	Distributed sales across 8+ regions
Customer Base	Active purchasing patterns identified
Processing Speed	Efficient order handling (7-10 days)
Areas for Improvement ⚠️
Area	Observation
Return Rate	10-15% return rate suggests quality concerns
Regional Variation	Uneven sales distribution across regions
Low-Margin Products	Some categories operate at <5% margin
Rating Factors	Investigation needed for 1-2 star reviews
Inventory Balance	Stock levels don't align with demand
📊 Analysis Capabilities
Available Analyses
Analysis Type	Purpose	Insight
Sales by Region	Geographic performance	Identify top/low performing areas
Product Category	Category performance	Best/worst selling categories
Temporal Trends	Time series analysis	Seasonal patterns, growth trends
Customer Segmentation	Behavioral analysis	High-value vs low-value customers
Profitability Analysis	Margin examination	Which products generate profit
Delivery Performance	Logistics metrics	On-time delivery by region
🛠️ Tools & Technologies
Data Processing
Microsoft Excel/XLSX - Primary data storage and pivot analysis
Python - Recommended for advanced statistical analysis
Pandas - Data manipulation and cleaning
NumPy - Numerical computations
Matplotlib/Seaborn - Data visualization
Scikit-learn - Predictive modeling (optional)
Analysis Methods
Pivot Tables - Multi-dimensional aggregation
Descriptive Statistics - Mean, median, mode, distribution
Correlation Analysis - Relationship between variables
Trend Analysis - Time-series patterns
Segmentation - Customer/product grouping
🚀 How to Use This Dataset
Step 1: Data Exploration
1. Open "Sales_Orders_cleaned" sheet for analysis-ready data
2. Review "Products" sheet for product master information
3. Check "Dashboard" sheet for KPI summary
Step 2: Create Pivot Tables
- Sales by Region and Product Category
- Monthly revenue trends
- Profit analysis by region
- Delivery performance metrics
- Payment method distribution
Step 3: Custom Analysis
- Filter by date range (2023-2026)
- Segment by region or city
- Analyze by product category
- Customer rating analysis
- Return rate investigation
Step 4: Reporting
- Generate monthly sales reports
- Create regional comparison reports
- Identify underperforming products
- Track KPIs over time
📋 Files & Naming Convention
FİNAL_PROJECT.xlsx
├── 📄 Sales_Orders_cleaned    (Main analysis file - USE THIS)
├── 📄 Products                (Product reference data)
├── 📄 Sales_Orders_Main       (Raw data - for reference)
├── 📊 Pivot                   (Pre-made pivot tables)
├── 📈 Dashboard               (Executive summary)
└── 📝 README.md               (This documentation)
💡 Recommended Next Steps
Short-term (Immediate)
Identify top 20 products by revenue and profit
Analyze return patterns by category and region
Compare regional performance metrics
Review low-rated products (1-2 stars)
Medium-term (1-2 months)
Develop predictive model for demand forecasting
Create customer segments based on purchase behavior
Optimize pricing strategy for low-margin products
Improve delivery performance in slow regions
Long-term (3+ months)
Implement real-time dashboard with automated updates
Build customer lifetime value (CLV) model
Develop churn prediction system
Create recommendation engine for products
📞 Data Quality & Support

For questions about data cleaning and transformations, refer to the "düzəlişlər" sheet for detailed documentation in Turkish.

Last Updated: October 2026
Data Period: 2023-2026
Total Records Analyzed: 25,875+
