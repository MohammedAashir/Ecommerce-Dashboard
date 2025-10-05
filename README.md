🛍️ Mugiwara Store Sales Dashboard
An interactive e-commerce sales analytics dashboard built to visualize and analyze sales performance, customer behavior, and product trends for Mugiwara Store.

Image
📊 Overview
This dashboard provides comprehensive insights into e-commerce sales data, featuring real-time metrics and interactive visualizations to support data-driven business decisions.
✨ Key Features
Performance Metrics

Total Revenue: ₹438K in sales amount
Sales Volume: 5,615 units sold
Average Order Value (AOV): ₹121K
Total Profit: ₹37K

Interactive Visualizations

Geographic Analysis

Sales distribution across Indian states (Uttar Pradesh, West Bengal, Tamil Nadu, Sikkim)
Helps identify top-performing regions


Product Performance

Category breakdown showing Clothing (63%), Electronics (21%), and Furniture (17%)
Sub-category profit analysis including Printers, Bookcases, Sarees, Accessories, and Tables


Customer Insights

Top customers by purchase amount
Customer segmentation and behavior analysis


Payment Analysis

Payment mode distribution: COD (44%), UPI (21%), Credit Card (12%), Debit Card (13%), EMI (10%)
Helps understand customer payment preferences


Temporal Trends

Monthly profit tracking throughout the year
Identifies seasonal patterns and trends



Filters

Quarter Selection: Filter data by Q1, Q2, Q3, or Q4
Custom Dropdown: Additional filtering options for detailed analysis

🛠️ Technologies Used

Data Processing: Microsoft Excel
Visualization Tool: Power BI Desktop
Data Source: E-commerce transaction data (Excel format)

📁 Project Structure
├── dashboard/
│   ├── Mugiwara_Sales_Dashboard.pbix
│   └── screenshot.png
├── data/
│   ├── sales_data.xlsx
│   └── data_dictionary.md
├── README.md
└── LICENSE
🚀 Getting Started
Prerequisites

Microsoft Excel (2016 or later)
Power BI Desktop (free download from Microsoft)
Windows OS (for Power BI Desktop)

Installation

Clone the repository

bashgit clone https://github.com/yourusername/mugiwara-sales-dashboard.git
cd mugiwara-sales-dashboard

Open the Excel data file

Navigate to data/sales_data.xlsx
Review the data structure and fields


Open the Power BI Dashboard

Open dashboard/Mugiwara_Sales_Dashboard.pbix in Power BI Desktop
If prompted, update the data source path to point to your local Excel file
Refresh the data to ensure all visualizations load correctly



Updating Data Source Path (if needed)

In Power BI Desktop, go to Home > Transform Data > Data Source Settings
Select the Excel file and click Change Source
Browse to the location of sales_data.xlsx on your computer
Click OK and then Close

📈 Key Insights

Top Performing State: Uttar Pradesh leads in sales amount
Most Popular Category: Clothing dominates with 63% of quantity sold
Preferred Payment Method: Cash on Delivery (COD) remains the most popular at 44%
Profitable Months: [Identify peak months from your data]

🔄 Data Pipeline

Data Collection: Raw transaction data from e-commerce platform
Data Cleaning: Handled missing values, standardized formats
Data Transformation: Aggregated metrics, calculated KPIs
Visualization: Created interactive dashboard with multiple views

📊 Sample Data Schema
Column NameDescriptionData TypeOrderIDUnique order identifierStringCustomerNameCustomer nameStringStateCustomer locationStringCategoryProduct categoryStringSubCategoryProduct sub-categoryStringAmountTransaction amountNumericQuantityUnits soldIntegerPaymentModePayment method usedStringProfitProfit per transactionNumericDateTransaction dateDate
🎯 Use Cases

Sales Performance Monitoring: Track revenue and profit trends
Inventory Planning: Understand product category demand
Regional Strategy: Identify growth opportunities by state
Customer Analytics: Analyze top customers and buying patterns
Payment Optimization: Optimize payment gateway strategy

📝 Future Enhancements

 Add predictive analytics for sales forecasting
 Implement customer segmentation using clustering
 Create mobile-responsive version
 Add real-time data refresh
 Include product recommendation insights
 Add year-over-year comparison

🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.
📧 Contact
Your Name - Mohammed Aashir
Project Link: https://github.com/mohammedaashir/sales-dashboard
📄 License
This project is licensed under the MIT License - see the LICENSE file for details.
🙏 Acknowledgments

