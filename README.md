#  Customer Behavior Analysis Project

##  Project Overview
This project analyzes customer shopping behavior using transactional data to uncover insights into spending patterns, customer segments, product preferences, and subscription behavior.

The project follows a complete **data analytics workflow**, from data cleaning and exploratory analysis to SQL querying, dashboard development, and business reporting.

---

##  Dataset
- **Source:** Kaggle
- **Records:** 3,900 customer purchases
- **Features:** 18 columns

### Key Attributes
- Customer demographics (Age, Gender, Location, Subscription Status)
- Purchase details (Item Purchased, Category, Purchase Amount, Season, Size, Color)
- Shopping behavior (Discount Applied, Purchase Frequency, Review Ratings, Shipping Type)

---

##  Tools & Technologies
- **Python:** Pandas, NumPy, Matplotlib, Seaborn
- **SQL:** PostgreSQL 
- **Business Intelligence:** Power BI 
- **Documentation:** Analytical report & presentation
- **Version Control:** Git & GitHub

---

##  Project Workflow

### 1️. Data Cleaning & Preparation (Python)
- Imported raw dataset from Kaggle
- Performed data quality checks and exploratory analysis
- Handled missing values in review ratings using median imputation per product category
- Standardized column names using snake_case
- Engineered new features such as customer age groups and purchase frequency
- Exported cleaned data to a local PostgreSQL database for SQL analysis

---

### 2️. Exploratory Data Analysis (EDA)
- Analyzed customer spending patterns across demographics
- Explored purchasing behavior trends
- Identified high-value and repeat customer segments
- Examined product popularity and rating distributions

---

### 3️. SQL Analysis (PostgreSQL)
All SQL analysis was performed on a **local PostgreSQL database**.

Key business questions addressed include:
- Revenue contribution by gender and age group
- Spending differences between subscribers and non-subscribers
- Impact of discounts on purchase amounts
- Shipping method comparison (Standard vs Express)
- Customer segmentation (New, Returning, Loyal)
- Relationship between repeat purchases and subscriptions
- Top-performing products by category and rating

 **SQL Scripts:**  
All SQL queries used in this analysis are available in the [`customer_analysis_queries.sql`](customer_analysis_queries.sql)


---

### 4️. Data Visualization (Power BI)
An interactive Power BI dashboard was developed locally to present insights in a clear and actionable manner.

 **Dashboard File:**  
The Power BI dashboard file is included in the  [`customer_behavior_dashboard.pbix`](customer_behavior_dashboard.pbix).
 
Key dashboard screenshots are included in the screenshots to showcase major insights and visualizations.

---

### 5. Project Report

A detailed analytical report documenting the methodology, analysis, and insights is available here:

 [`customer_behavior_analysis_report.pdf`](customer_behavior_analysis_report.pdf)
 


---
### 6. Presentation Slides  
Executive-level presentation slides summarizing the findings and recommendations:

 [`customer_behavior_analysis_slides.pptx`](customer_behavior_analysis_slides.pptx)


 ---

##  Key Insights
- Subscribers have higher average purchase values than non-subscribers
- Loyal customers contribute a significant portion of total revenue
- Certain products rely heavily on discounts to drive sales
- Express shipping users tend to spend more per transaction
- Specific age groups generate the highest revenue

---

##  Business Recommendations
- Strengthen subscription programs with exclusive benefits
- Introduce loyalty incentives for repeat customers
- Review discount strategies to protect profit margins
- Promote high-performing and highly rated products
- Apply targeted marketing to high-value customer segments

---

## Repository Structure
```
Customer-Behavior-Analysis/
├── customer_behavior_dashboard.pbix
├── README.md
├── customer_behavior_analysis_report.pdf
├── customer_behavior_analysis_slides.pptx
├── customer_analysis_queries.sql

```
---

##  How to Run This Project Locally
1. Review the cleaned dataset in the `data/` folder
2. Load the dataset into PostgreSQL using the provided schema or scripts
3. Execute SQL queries from the `/sql` directory
4. Open the Power BI `.pbix` file to explore the dashboard
5. Read the report and presentation for detailed insights

---

##  Contact
**Author:** Abigael Wambui 
**Field:** Data Analytics / Data Science 
**Email:** abigaelwambui1@gmail.com
 

---

 *This project demonstrates an end-to-end customer behavior analysis workflow using real-world data.*

