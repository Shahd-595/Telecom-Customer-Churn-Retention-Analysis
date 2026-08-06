# Telecom-Customer-Churn-Retention-Analysis📊
## Project Description:-
### This project aims to analyze customer data from a telecommunications provider to identify the primary drivers behind Customer Churn—specifically evaluating whether customer departure is driven by service quality, pricing structures, lack of tailored promotional offers, or contract terms.​Through standard data preprocessing and exploratory data analysis (EDA), the project will uncover key patterns in customer behavior. The final outcome includes an Interactive Dashboard designed to visualize essential Key Performance Indicators (KPIs) and track retention metrics, alongside actionable strategic recommendations to reduce churn and enhance customer loyalty.
---------------------------------------------------------------------------------------------------------------------------------------------------

## 📁Dataset Columns Description:-

| Column Name | Description |
|-------------|-------------|
| CustomerID | Unique identifier for each customer |
| Count | Static value of '1' for counting/aggregation |
| Country | Country of residence (United States) |
| State | US State (California) |
| City | City of residence |
| Zip Code | US postal zip code |
| Lat Long | Geographical coordinates (combined string) |
| Latitude | Latitudinal coordinate |
| Longitude | Longitudinal coordinate |
| Gender | Customer gender (Male/Female) |
| Senior Citizen | Indicates if customer is senior citizen (Yes/No) |
| Partner | Indicates if customer has a partner (Yes/No) |
| Dependents | Indicates if customer has dependents (Yes/No) |
| Tenure Months | Number of months with the company |
| Phone Service | Customer has phone service (Yes/No) |
| Multiple Lines | Customer has multiple phone lines |
| Internet Service | Type of internet service (Fiber optic/DSL/No) |
| Online Security | Has online security add-on service |
| Online Backup | Has online backup add-on service |
| Device Protection | Has device protection add-on service |
| Tech Support | Has tech support add-on service |
| Streaming TV | Has streaming TV add-on service |
| Streaming Movies | Has streaming movies add-on service |
| Contract | Type of contract (Month-to-month/One year/Two year) |
| Paperless Billing | Uses paperless billing (Yes/No) |
| Payment Method | Preferred payment method |
| Monthly Charges | Monthly charges amount |
| Total Charges | Total charges over tenure |
| Churn Label | Customer churned (Yes/No) |
| Churn Value | Binary value (1=churned, 0=not churned) |
| Churn Score | Predicted churn likelihood score |
| CLTV | Customer Lifetime Value |
| Churn Reason | Reason for churning (if applicable) |
---------------------------------------------------------------------------------------------------------------------------------------------------

### number of columns : 33
### number of rows : 7043

---------------------------------------------------------------------------------------------------------------------------------------------------

## ⚙Business Problem:-
- Telco Customer Churn.
---------------------------------------------------------------------------------------------------------------------------------------------------

## 🎯Goal:-
- Identifying the segments most likely to unsubscribe to help the marketing and service teams make customer retention decisions.
---------------------------------------------------------------------------------------------------------------------------------------------------

## 🔑Key Insights:-
- **Contract Type:** Customers on Month-to-month contracts experience the highest churn rate at 42.7%.
- **Customer Tenure:** The first six months are the most critical, with churn peaking at 52.9%.
- **Payment Method:** Electronic check users are the most likely to churn, reaching 45.3%.
- **Internet Service:** Fiber optic subscribers report a notably high churn rate of 41.9%.
- **Churn Reasons:** Technical support attitude is the primary churn driver (192 customers), followed by aggressive competitor offers.
- **Monthly Charges:** Mid-to-high spenders ($60–$90) account for the largest proportion of churn (33.7%), closely followed by the $90+ segment (32.9%).

---------------------------------------------------------------------------------------------------------------------------------------------------

## Quick Business Recommendations💡:-
- Offering incentive discounts to new customers to convert them from month-to-month contracts to annual contracts.
- Focusing on supporting and following up with new customers during the first six months to reduce the very high churn rate (52.9%).
- Training and qualifying the technical support team to address customer service issues, while reviewing the pricing and quality of fiber optic services to compete with external offers.

---------------------------------------------------------------------------------------------------------------------------------------------------

## 🛠️ Tools Used:-
**Microsoft Excel / Power Query:** Data cleaning, transformation, and initial exploratory analysis, Data modeling.
* **Power BI Desktop:** and interactive dashboard creation/visualization.
