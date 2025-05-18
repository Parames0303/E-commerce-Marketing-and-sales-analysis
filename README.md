E-commerce Marketing and Sales Analysis

🧠 Business Case Overview

The e-commerce company aims to leverage data-driven insights to enhance customer acquisition, retention, and revenue optimization. This analysis explores key business questions using transaction, customer, coupon, marketing, and tax data from the year 2019. It applies exploratory data analysis (EDA), statistical methods, and business logic to generate actionable recommendations.

Dataset file: https://github.com/Parames0303/E-commerce-Marketing-and-sales-analysis/blob/main/DAV%20Business%20case-20250508-Data

📊 Dataset Summary

Period Covered: Jan 1, 2019 – Dec 31, 2019

Data Sources:

Online_Sales.csv (transaction-level order data)

Customers_Data.csv (customer demographics)

Discount_Coupon.csv (monthly coupon rules)

Marketing_Spend.csv (day-wise marketing expenses)

Tax_Amount.csv (product-level tax details)

✅ Summary of Findings by Business Question

1. 🔺 Identify the months with highest and lowest acquisition rates

Here is the analysis result visualization on the aquisition rate
### 📈 Monthly Customer Acquisition

![Monthly Customer Acquisition](plots/monthly%20customer%20aquisition.png)

Highest acquisition: January (215 new customers)

Lowest acquisition: November (68 new customers)

Recommendation: Replicate January's success with year-start campaigns. Use offers and referral programs to lift Q4.

2. 📅 Do certain months consistently perform better?

Strong Q1 performance: Jan, Mar, Apr.

Weak Q4: Sep–Nov.

Strategy: Scale Q1 campaigns, retarget dormant users in Q4, and smooth acquisition through always-on efforts.

3. 📈 Identify retention highs and lows

Strong retention: July, Oct–Dec

Weak retention: Feb–Apr

Strategy: Extend retention campaigns into low-months with reminders, loyalty rewards, and behavior-based offers.

4. 🔄 High-retention behavior analysis

Retention > 59% in top 5 months (Nov, Jul, Sep, Oct, Dec)

Driven by: Promotions, campaign continuity, higher coupon usage, popular categories

Strategy: Trigger-based repurchase offers, sequenced campaigns, and loyalty programs

5. 👥 New vs Existing Customer Revenue

![Monthly Revenue New Vs Existing Customers](plots/Monthly_revenue_New_Vs_Existingcustomers.png)

New customers dominate Jan–Mar

Existing customers dominate Apr–Dec

Insight: Retention is strong; acquisition efforts needed in mid-to-late year.

6. 💸 Coupon Usage vs Revenue Impact
   
![Average Order value for Coupon and Noncoupon customers](plots/Coupon_Vs_NonCoupon_Average_order_value.png)
Coupon Users: 17,904 | Non-Coupon Users: 35,020

P-value = 0.304 → No significant difference in AOV

Insight: Coupons useful for engagement, but don't raise order value.

Strategy: Use threshold-based, behavior-triggered coupons.

7. 🏆 Top Performing Products

Top SKUs contribute majority of revenue

Success driven by: High sales volume, coupon usage, key categories

Inventory Action: Prioritize stock levels of high movers

Promo Strategy: Bundle top items, pair with coupons in slow months

(Questions 8 to 20 can be added in continuation with the same summary format once we extract their details)

📁 Repository Structure

📦 E-commerce-Marketing-Case
├── Scaler_business_use_case_1.ipynb        # Full code and analysis
├── README.md                               # Problem summary + insights (this file)
├── plots/                                  # Visuals exported from notebook (optional)
├── data/                                   # Original datasets

📌 Tools Used

Python (Pandas, NumPy, Seaborn, Matplotlib, Scipy)

Jupyter Notebook

🧩 Key Business Recommendations

Replicate high-acquisition campaigns across quarters

Use retargeting and behavior-triggered offers to improve retention

Optimize coupon strategy with smarter rules and timing

Adjust inventory and promotions based on product performance

Focus on boosting acquisition in Q3–Q4 to balance strong retention

For full details, refer to the notebook Scaler_business_use_case_1.ipynb.

