🛍️ Customer Shopping Behaviour Dashboard
📖 Project Overview

The Customer Shopping Behaviour Dashboard is a comprehensive data analytics project designed to understand customer purchasing patterns, spending behavior, and loyalty trends.
The project follows a complete data lifecycle — from data cleaning and preprocessing using Python, to data analysis with SQL in PostgreSQL, and finally, data visualization in Power BI.

The goal is to uncover insights that help businesses make informed marketing and operational decisions based on customer behavior.

🧰 Tools and Technologies Used

Python: Data cleaning, transformation, and preprocessing

PostgreSQL: Data storage and SQL-based analytical queries

Power BI: Data visualization and dashboard creation

Pandas and NumPy: Data handling and manipulation

SQLAlchemy and Psycopg2: Connecting Python to PostgreSQL

Jupyter Notebook: Interactive analysis environment

🧩 Project Workflow
1️⃣ Data Import and Exploration

The dataset containing customer shopping information was imported from a CSV file. The structure and content of the dataset were explored to understand data quality, missing values, and potential inconsistencies.

2️⃣ Data Cleaning and Preprocessing

The data cleaning process included:

Handling missing and erroneous values

Renaming and standardizing column names

Removing duplicates and irrelevant fields

Formatting and rearranging columns for better readability

Ensuring consistency for seamless database integration

This stage helped prepare high-quality data suitable for analysis and reporting.

3️⃣ Data Integration with PostgreSQL

After cleaning, the processed dataset was uploaded into a PostgreSQL database using Python connectivity libraries.
The integration ensured structured data storage and enabled advanced SQL-based querying.
A database named customer and a table named customer_behavior were created to store the cleaned records.

4️⃣ Data Analysis Using SQL

Analytical queries were performed in PostgreSQL to derive meaningful insights.
Key analysis areas included:

Revenue by Gender: Identified purchasing trends between male and female customers.

High-Spending Discount Users: Found customers who spent more while availing discounts.

Repeat Customers: Highlighted customers with frequent purchases.

Top Purchased Products: Listed the top three most purchased product categories.

Customer Segmentation: Classified customers into New, Returning, and Loyal based on purchase frequency.

Top Products by Revenue Percentage: Determined the products contributing the most to total revenue.

Subscribed Customers and Average Revenue: Analyzed revenue patterns among subscribed users.

Customers Using Discounts: Counted customers who availed discounts during purchases.

Revenue by Gender: Compared revenue contribution between male and female customers.

High-Spending Loyal Customers: Identified loyal customers with high total spending.

5️⃣ Data Visualization with Power BI

An interactive dashboard was designed in Power BI to visualize the key insights derived from SQL queries.
The dashboard provided a user-friendly view of customer behavior and business performance, allowing for data-driven decisions.

Key visuals included:

Total Revenue by Gender

Customer Segmentation (New, Returning, Loyal)

High-Spending and Discount Usage Analysis

Top Product Categories by Purchase Volume

Average Revenue and Customer Retention Metrics

These visuals helped convert complex data into actionable insights for stakeholders.

💡 Key Insights

Loyal customers generate the highest percentage of total revenue.

Discount usage has a strong positive correlation with higher spending.

The top three product categories dominate most of the total purchases.

Subscribed customers show higher average revenue per transaction.

There are noticeable gender-based variations in shopping behavior.

💼 Business Recommendations

Based on insights from the dashboard, the following recommendations were made:

Focus on Loyal Customers
Introduce loyalty programs and exclusive offers to retain high-value customers.

Enhance New and Returning Customer Engagement
Use personalized recommendations, first-purchase offers, and reminder emails to convert new users into repeat buyers.

Optimize Discount Strategies
Offer targeted discounts to high-value customers rather than broad offers to maximize profit margins.

Strengthen Top Product Categories
Prioritize inventory management and promotional efforts for the most purchased categories.

Implement Gender-Based Marketing Campaigns
Use gender-segmented promotions to enhance customer engagement and sales.

Encourage Subscription Models
Promote membership and subscription programs by offering special perks such as early access or free delivery.

Utilize Predictive Analytics
Apply machine learning to predict customer churn, recommend products, and forecast sales trends.

Leverage Power BI Dashboard for Decision-Making
Use the live dashboard during strategy meetings for real-time insights into customer and sales performance.

🚀 Project Outcomes

Cleaned and standardized the dataset using Python.

Uploaded and analyzed data effectively in PostgreSQL.

Generated actionable business insights through SQL queries.

Designed an interactive Power BI dashboard for visualization.

Provided clear recommendations to support data-driven business decisions.

🧾 Project Deliverables

Cleaned dataset ready for analysis

PostgreSQL database with structured tables

SQL queries for data analysis

Power BI interactive dashboard

Business insights and recommendations report
