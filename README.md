**📘 Credit Card Data Analysis:**
This project analyzes customer acquisition data, credit card spending patterns, and repayment behaviour to derive insights for improving profitability, customer targeting, and portfolio management.
The analysis follows a complete data science workflow—including cleaning, feature engineering, exploratory analysis, visualization, and custom function development.

**🎯 Project Objectives:**
•	Correct invalid or extreme values using business rules
•	Generate customer-level and city-level spending insights
•	Evaluate monthly profitability based on spend vs repayment
•	Identify top customers and high-spend segments
•	Build dynamic reporting function for top customers by product & time period

**🧹 Data Cleaning Rules Applied:**
**Customer Acquisition-**
•	Age < 18 → replaced with mean age.
**Spend Data-**
•	Spend amount > customer limit → replaced with 50% of limit.
**Repayment Data-**
•	Repayment > limit → capped at limit amount.
**Common Processing-**
•	Created Month / Year features using transaction date.
•	Merged datasets to form a complete customer view.

**📊 Key Insights & Outputs:**
•	Count of distinct customers and categories
•	Average monthly spend vs average monthly repayment
•	Monthly bank profit (using 2.9% interest on positive profit only)
•	Top 5 product types by usage
•	City with maximum spend
•	Age group with highest spending
•	Top 10 customers by repayment amount
•	Yearly city-wise spend by product
•	Seasonality & monthly trends across products and cities

**📈 Visualizations Included:**
•	City-wise yearly spend by product (bar chart)
•	Monthly spend comparison across cities (line plot)
•	Yearly spend on air tickets (bar chart)
•	Monthly spend trend per product (line plot)

**🛠 Custom Python Function Implemented:**
top10_customers(product, period)
A fully dynamic reporting function:
•	Filters by product type (Gold, Silver, Platinum)
•	Selects monthly or yearly time period
•	Returns top 10 customers per city based on repayment amount
•	Automatically aggregates and sorts results
This allows analysts to quickly generate targeted marketing or collection lists.

**🧰 Tech Stack:**
•	Python
•	Pandas, NumPy
•	Matplotlib, Seaborn
•	Jupyter Notebook
