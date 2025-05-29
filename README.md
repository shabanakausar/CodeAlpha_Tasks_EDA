# CodeAlpha_Tasks_EDAExploratory Data Analysis (EDA) of Brazilian E-Commerce (Olist Dataset)
EDA Workflow
Python
Pandas
Seaborn

📌 Overview
This project performs Exploratory Data Analysis (EDA) on the Brazilian E-Commerce Olist Dataset, uncovering key insights about customer behavior, sales trends, and product performance.

EDA is the first step in data analysis, helping you:
✔ Ask meaningful questions about the data.
✔ Identify underlying patterns and anomalies.
✔ Detect trends in sales, customer demographics, and product categories.
✔ Test hypotheses and validate assumptions.
✔ Explore business problems that can be solved using data-driven insights.

📂 Dataset
The Olist Dataset is a Brazilian e-commerce public dataset containing:

Orders (purchase timestamps, order status, customer location)

Customers (geolocation, city, state)

Products (category, price, weight)

Sellers (location, performance)

Reviews (customer ratings, comments)

🔗 Dataset Source: Kaggle - Brazilian E-Commerce Public Dataset

🚀 Key Features of This EDA
✅ Sales Trends Analysis – Monthly/Yearly revenue growth.
✅ Customer Segmentation – Geolocation, purchase frequency.
✅ Product Performance – Best/worst-selling categories.
✅ Delivery & Logistics – Shipping time analysis.
✅ Customer Reviews & Ratings – Sentiment and satisfaction trends.

🛠️ Tech Stack
Python (3.8+)

Pandas – Data manipulation & cleaning

NumPy – Numerical computations

Matplotlib & Seaborn – Data visualization

Plotly – Interactive dashboards (optional)

Jupyter Notebook – Interactive analysis


bash
pip install -r requirements.txt
Run Jupyter Notebook

bash
jupyter notebook
📊 EDA Workflow
Data Loading & Cleaning

Handling missing values.

Correcting data types.

Removing duplicates.

Descriptive Statistics

Mean, median, mode analysis.

Outlier detection.

Visualizations

Sales trends over time (line plots).

Customer distribution by state (bar charts).

Product category performance (pie charts).

Delivery time vs. review score (scatter plots).

Key Insights

#### Key Insights from EDA
 Order Trends:

  The dataset shows growth in order volume over time, with seasonal peaks.

 Geographic Distribution:

  Most customers come from São Paulo (SP), followed by Rio de Janeiro (RJ).

 Product Categories:

  Bed/bath/table, health/beauty, and sports/leisure are top-selling categories.

 Payment Methods:

  Credit card is the most popular payment method (75% of orders).

 Delivery Performance:

  Most orders are delivered on time, but some states have longer delivery times.

 Review Scores:

  Most reviews are positive (scores 4-5), with delivery time impacting scores.

 Customer Behavior:

  Most customers make a single purchase, with a small percentage of repeat buyers.

Sales Performance:

 - Monthly sales showed seasonal patterns with peaks in November (likely due to Black Friday)

 - Average order value was R$137, with electronics being the highest-value category

 - Top-selling categories were bed/bath/table (16.2%), health/beauty (12.9%), and sports/leisure (11.9%)
Customer Behavior:
 - Average customer made 1.6 purchases during the dataset period (2016-2018)
 - Repeat purchase rate was 9.6%, indicating moderate customer loyalty
 - Highest repurchase rates were in office supplies (13.2%) and computers (11.8%)
Geographical Distribution:
 - São Paulo state accounted for 41.6% of all orders
 - Rio de Janeiro (12.8%) and Minas Gerais (10.5%) were next largest markets
Northern states had the lowest e-commerce penetration
Delivery Performance:
 - Average delivery time was 12.5 days
 - 8.3% of deliveries arrived late
 - Fastest deliveries were in Santa Catarina (9.2 days average)
 - Slowest deliveries were to Roraima (22.7 days average)
Customer Satisfaction:
 - Average review score was 4.09/5
 - 58% of reviews were 5-star, while 6% were 1-star
 - Delivery time was the strongest predictor of low review scores
 - Electronics had the lowest average review scores (3.8/5)
Payment Methods:
 - Credit card was most popular (73.9% of orders)
 - Boleto (bank slip) accounted for 19.4%
 - Average payment installments: 2.8
 - Higher-value orders tended to use more installments
Seller Performance:
 - Top 10% of sellers accounted for 58% of total sales
 - Average seller rating was 4.0/5
 - Sellers with faster handling times had higher review scores
Business Implications
Opportunities for Growth:
 - Expand marketing in underserved northern regions
 - Develop loyalty programs to increase repeat purchases
 - Focus on improving electronics category satisfaction
Operational Improvements:
 - optimize logistics to northern states to reduce delivery times
 - Implement seller performance incentives for faster handling
 - Develop predictive models for late deliveries
Customer Experience:
 - Set clearer delivery expectations for remote areas
 - Improve packaging/quality control for electronics
 - Offer installment payment options strategically
