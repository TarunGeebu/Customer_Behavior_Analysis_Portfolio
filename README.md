# Customer_Behavior_Analysis_Portfolio
This project provides an end-to-end data analytics solution, transforming raw retail data into actionable business intelligence. By leveraging Python, SQL, and Power BI, the analysis uncovers key drivers of customer engagement and purchasing patterns across a dataset of 3,900 records.

**Data Foundations & EDA (Python)**
1. Data Ingestion: Processed a dataset with 18 features, including demographics (Age, Gender, Location) and transactional details (Item Purchased, Category, Purchase Amount).
2. Cleaning: Identified and addressed missing values, specifically within the Review Rating column, to maintain analysis accuracy.
3. SQL Integration: Utilized SQLAlchemy to establish a connection and migrate the cleaned DataFrame directly into a MySQL environment for high-performance querying.

**Advanced Analysis (MySQL)**
1. Revenue Segmentation: Calculated total revenue by gender, identifying that male customers contributed $157,890 compared to $75,191 from female customers.
2. Customer Categorization: Implemented WITH clauses and CASE statements to segment users into New, Returning, and Loyal categories based on their previous purchase history.
3. Demographic Performance: Analyzed revenue contribution by age group, classifying shoppers into 'young adult', 'adult', 'middle aged', and 'senior' categories.
4. Product Insights: Identified the top 3 most purchased products within each retail category using window functions (ROW_NUMBER).

**Business Intelligence Dashboard (Power BI)**
Key Performance Indicators (KPIs):
1. Total Customer Base: 3,900 records analyzed.
2. Average Purchase Value: $59.76 per transaction.
3. Average Review Rating: 3.75/5.0, providing a baseline for customer satisfaction.

Core Visualizations:
1. Revenue by Category: Identified Clothing as the dominant revenue driver ($104K), followed by Accessories ($74K), Footwear ($36K), and Outerwear ($19K).
2. Demographic Distribution: A specialized donut chart highlighting the gender split (68% Male / 32% Female).
3. Subscription Analysis: Visualized that 27% of the customer base are active subscribers, identifying a significant opportunity for loyalty program growth among the 73% non-subscribers.
4. Age Group Performance: Ranked revenue contribution across four life stages: Adult, Middle-Aged, Young Adult, and Senior.

Interactive Features:
1. Integrated multi-select slicers for Subscription Status, Product Category, and Gender, allowing stakeholders to perform ad-hoc cross-sectional analysis.
2. Developed a clean, user-centric UI designed for quick decision-making and trend identification.

**Key Findings**
1. Top Performer: Clothing is the primary revenue driver, contributing $104K (nearly 45% of total sales).
2. Customer Profile: The base is 68% Male, with the "Adult" (30–49) group being the most profitable demographic ($88.5K).
3. Subscription Gap: 73% of customers are not subscribers, despite subscribers having a higher average spend.
4. Customer Loyalty: Most shoppers are "Returning" (2,500), followed by "Loyal" (1,000) and "New" (400).
5. Product Quality: Shorts (4.9) and Handbags (4.8) are the highest-rated items, while Sweaters and Jackets are the most discount-driven.

**Strategic Recommendations**
1. Convert "Returning" Shoppers: Target the 2,500 returning customers with a subscription incentive (e.g., 20% off) to secure recurring revenue.
2. Narrow the Gender Gap: Launch targeted marketing for Female shoppers focusing on high-rated categories like Handbags and Dresses to balance the 68/32 split.
3. Optimize Seasonal Stock: Increase inventory for high-rated summer items (Shorts) and use promo codes to drive growth in the underperforming Outerwear category.
4. Prioritize the 30–64 Demographic: Focus ad spend on this "high-lifetime-value" bracket to maximize ROI.

**Tech Stack & Tools**
1.  Python: Pandas, NumPy, SQLAlchemy, PyMySQL.
2.  SQL: MySQL (Advanced Window Functions, CTEs, Aggregations).
3.  BI: Power BI Desktop (DAX, Interactive Reporting).
4.  Environments: Google Colab, VS Code
