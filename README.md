🍕 Pizza Sales Analysis Dashboard - Power BI Project
📊 Project Overview
This Power BI dashboard project presents an in-depth analysis of pizza sales data, aimed at uncovering actionable insights to boost business performance, improve customer satisfaction, and optimize operational decisions for a pizza chain. The goal is to demonstrate data storytelling and analytical thinking through the use of visualizations and interactive reporting in Power BI.

Whether you're a data analyst, business owner, or Power BI enthusiast, this dashboard showcases how real-world data can be transformed into a compelling business intelligence solution.

🔍 Objective
The primary objectives of this project are:

To identify top-selling pizza types and categories

To analyze sales trends over time (daily, weekly, monthly)

To determine the busiest times and days for pizza orders

To understand customer preferences by slice size, category, and ingredients

To support decision-making in marketing, inventory, and operations

🧩 Data Source
The dataset used for this project is a fictional but realistic pizza sales dataset, which includes:

Order ID

Date and time of order

Pizza name and category

Quantity ordered

Pizza size

Unit price

You can find the CSV file in the data/ folder of this repository.

🛠️ Tools & Technologies Used
Power BI – for building dashboards and performing data modeling

Power Query – for data cleaning and transformation

DAX (Data Analysis Expressions) – for calculated measures and KPIs

Microsoft Excel – for minor data manipulation and review

GitHub – for version control and project showcase

📈 Key Insights
🔥 Best-Selling Pizzas: Identified the most and least popular pizza items

🗓️ Peak Order Times: Pinpointed peak hours and days with the highest sales

💵 Revenue Trends: Visualized revenue performance over time

📏 Size Preference: Analyzed which pizza sizes generated the most revenue

🍕 Category Analysis: Compared sales across categories (Veg, Non-Veg, Classic, etc.)

🧮 DAX Measures Used
Some of the important DAX measures created:

Total Revenue = SUM(Orders[Total Price])

Total Orders = COUNTROWS(Orders)

Average Order Value = DIVIDE([Total Revenue], [Total Orders])

Best-Selling Pizza = RANKX(...)

Sales by Hour = HOUR(Orders[Time])

📌 Dashboard Features
Interactive Filters: Date range, Pizza Category, Pizza Size

Dynamic Charts: Line, Bar, Pie, and Matrix visualizations

KPIs & Cards: Real-time calculation of key metrics

User-Friendly Layout: Clean and intuitive design for quick insights

📁 Repository Structure
kotlin
Copy
Edit
├── data/
│   └── pizza_sales_data.csv
├── visuals/
│   └── dashboard_screenshots.png
├── PowerBI_Dashboard/
│   └── Pizza_Sales_Analysis.pbix
├── README.md
🚀 How to Use
Download or clone this repository

Open the .pbix file in Power BI Desktop

Refresh the data if needed

Explore the interactive dashboard and visuals

💡 Future Enhancements
Incorporate geospatial analysis for store locations

Add customer segmentation and lifetime value metrics

Create a web-based version using Power BI Service

Integrate with real-time order APIs

👨‍💻 Author
Ujjwal Kumar
Data Analyst | Power BI Developer | GitHub: analyst-ujjwal
Feel free to connect with me on www.linkedin.com/in/ujjwal-kumar-840ba2224

📬 Feedback
If you find this project useful or have suggestions for improvement, feel free to open an issue or create a pull request. Contributions are welcom
