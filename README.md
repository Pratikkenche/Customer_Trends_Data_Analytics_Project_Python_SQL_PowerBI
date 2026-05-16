# Customer Shopping Behavior Analysis Dashboard

## Project Overview
This project analyzes customer shopping behavior using Python, PostgreSQL, SQL, and Power BI. The dashboard uncovers insights related to customer demographics, spending habits, subscriptions, loyalty trends, discount usage, and product preferences.

The analysis was performed on 3,900 customer transactions across multiple product categories to generate business insights and support data-driven decision-making.

---

## Objectives
- Analyze customer purchase behavior
- Identify high-value customer segments
- Explore subscription and loyalty trends
- Understand discount impact on spending
- Visualize key business KPIs using Power BI

---

## Dataset Summary
- **Total Purchases:** 3,900
- **Features:** 18
- **Product Categories:** 4
- **Missing Ratings Handled:** 37

### Features Included
- Age
- Gender
- Location
- Subscription Status
- Item Purchased
- Category
- Purchase Amount
- Shipping Type
- Discount Applied
- Review Rating
- Purchase Frequency
- Season

---

## Tools & Technologies
- Python
- Pandas
- PostgreSQL
- SQL
- Power BI
- DAX

---

## Data Preparation
### Python Data Cleaning & Feature Engineering
- Loaded and explored dataset using Pandas
- Handled missing review ratings using category median
- Created:
  - `age_group`
  - `purchase_frequency_days`
- Prepared dataset for SQL and Power BI analysis

---

## SQL Analysis
Performed SQL queries for:
- Customer segmentation
- Revenue analysis
- Product ranking
- Subscription trends
- Loyalty analysis
- Discount behavior analysis

---

## Power BI Dashboard Features
### KPI Cards
- Average Purchase Value
- Average Rating
- Total Customers
- Subscriber Percentage

### Visualizations
- Revenue by Gender
- Revenue by Age Group
- Subscription Analysis
- Shipping Preference Analysis
- Top Rated Products
- Discount Usage Insights
- Loyalty Segmentation

---

## Key Insights
- Young Adults generated the highest revenue
- Male customers contributed nearly 2× more revenue
- Only 27% customers were subscribers
- 80% customers were loyal buyers
- Express shipping users spent slightly more
- High-value customers frequently used discounts

---

## Business Recommendations
- Increase subscriber conversion campaigns
- Launch loyalty reward programs
- Optimize discount strategies
- Target high-spending customer segments

---

## Dashboard Preview
(Add dashboard screenshots here)

---

## Project Structure
```text
Customer-Shopping-Behavior-Analysis/
│
├── data/
├── notebooks/
├── sql_queries/
├── dashboard/
├── presentation/
└── README.md
