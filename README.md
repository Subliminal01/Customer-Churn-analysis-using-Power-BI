**Case Study: Customer Churn Analysis Using Power BI**

**Objective**
To identify and understand the key factors driving customer churn in an e-commerce setting, and to provide actionable insights for reducing churn and improving customer retention.

**Dataset Overview**
Source: Ecommerce Customer Churn Analysis and Prediction (Kaggle)
Authpor: Ankit Verma

**Size:** 
~5,600 customer records

**Attributes:**
CustomerID
Churn
Tenure
PreferredLoginDevice
CityTier
WarehouseToHome
PreferredPaymentMode
Gender
HourSpendOnApp
NumberOfDeviceRegistered
PreferedOrderCat
SatisfactionScore
MaritalStatus
NumberOfAddress
Complain
OrderAmountHikeFromlastYear
CouponUsed
OrderCount
DaySinceLastOrder
CashbackAmount

**Key Insights**
1. _Tenure Impact_
Retained customers have an average tenure of 11.4 months, while churned customers only stay for 3.86 months.
Insight: Early-stage churn is high. Onboarding and early engagement strategies could help retain users longer.

2. Complaints
Among 948 churned customers, 508 had filed complaints.
Insight: Complaints correlate strongly with churn. Improve customer support and complaint resolution process.

3. Satisfaction Score
Going from 4-5, number of customers churned increases
Insight: Not a strong indicator, in fact it is counter-intuitive.

4. Order Category
Higher churn in categories like Mobile Phones and Fashion compared to Laptops & Accessories.
Insight: High-return or impulsive-buy categories may have higher churn. Tailor retention efforts for such categories.

5. Payment Mode
Higher churn for Credit Cards and Debit Cards, lower for Cash on Delivery.
Insight: Payment preferences might reflect customer trust and experience. Incentivize low-churn payment methods.

💼 Business Recommendations
Early Lifecycle Engagement
Launch loyalty programs for new users within the first 3–6 months.
Complaint Resolution Optimization
Automate and fast-track complaint handling to avoid churn triggers.
Category-Specific Retention
Tailor retention strategies based on order category churn patterns.

Tools Used
Power BI – For dashboard creation and visualization
DAX – For custom calculations
Excel – For initial data cleaning
Python - For data cleaning and visualisation
