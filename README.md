🚀 Project Overview

This project focuses on understanding customer buying behavior, revenue patterns, subscription impact, and demographic insights using a synthetic dataset containing 3.9K customers.

The workflow includes:

✔ Data Understanding
✔ Python EDA
✔ Feature Engineering
✔ SQL Business Queries
✔ Power BI Dashboard

📁 Dataset Columns

.customer_id
.age
.gender
.item_purchased
.category
.purchase_amount
.location
.size
.color
.season
.review_rating
.subscription_status
.shipping_type
.discount_applied
.previous_purchases
.payment_method
.frequency_of_purchases
.age_group
.purchase_frequency_days

🧪 Python EDA

.Handled missing values & outliers
.Created new features (age_group, purchase frequency buckets, discount flag, etc.)
   Analyzed revenue patterns by:
   Category
   Age group
   Gender
   Subscription status
   Shipping type

🛠 Feature Engineering

.Binning age into groups
.Calculating customer purchase frequency
.Creating categorical encodings
.Aggregating customer-level metrics (avg purchase, total purchases, avg rating)

🗄 SQL Queries

You will find SQL scripts answering business questions:

✔ Top-selling categories
✔ Average spend per subscription type
✔ Customer segments contributing max revenue
✔ Category-wise order frequency
✔ High-value customer identification
✔ Seasonal sales trends

📊 Power BI Dashboard

The dashboard includes:

🔹 KPI Cards

Total Customers: 3.9K
Average Revenue: $59.76
Average Rating: 3.75

🔹 Key Visuals
% Customers by Subscription
Revenue by Category
Sales by Category
Revenue by Age Group
Sales by Age Group

🔹 Slicers

Gender
Subscription Status
Category
Shipping Type

🎯 Key Insights

Clothing generates the highest revenue.
Young Adults are the most active buyers.
73% customers are non-subscribers, yet subscribers spend more on average.
2-Day Shipping is the most preferred option.
Accessories are the 2nd highest revenue generator.

🧰 Tech Stack

Python (Pandas, Matplotlib/Seaborn, NumPy)
SQL
Power BI
Excel (optional preprocessing)

📦 How to Use

Clone repo
Run Python notebook for EDA
View SQL queries folder
Open .pbix file for dashboard
Explore insights & modify filters

🧑‍💻 Author

Ganesh Longre
LinkedIn: https://www.linkedin.com/in/ganesh-longre-a30573316/
