# Telecom-Customer-Churn-Retention-Analysis📊
## Project Description:-
### This project aims to analyze customer data from a telecommunications provider to identify the primary drivers behind Customer Churn—specifically evaluating whether customer departure is driven by service quality, pricing structures, lack of tailored promotional offers, or contract terms.​Through standard data preprocessing and exploratory data analysis (EDA), the project will uncover key patterns in customer behavior. The final outcome includes an Interactive Dashboard designed to visualize essential Key Performance Indicators (KPIs) and track retention metrics, alongside actionable strategic recommendations to reduce churn and enhance customer loyalty.
---------------------------------------------------------------------------------------------------------------------------------------------------

# Column Descriptions:-
### CustomerID: Unique identifier for each customer in the dataset.

Count: A static value of '1', likely used for counting or aggregation purposes.

Country: The country where the customer resides. In this dataset, all customers are from the "United States".

State: The US state where the customer is located. All entries are from "California".

City: The city within California where the customer lives.

Zip Code: The US postal zip code for the customer's address.

Lat Long: A combined string representing the geographical coordinates (latitude and longitude) of the customer's location.

Latitude: The latitudinal coordinate of the customer's location.

Longitude: The longitudinal coordinate of the customer's location.

Gender: The self-identified gender of the customer (Male or Female).

Senior Citizen: Indicates if the customer is a senior citizen (Yes or No). A value of '1' is used in some rows to indicate "Yes", and '0' for "No".

Partner: Indicates if the customer has a partner (Yes or No).

Dependents: Indicates if the customer has dependents (e.g., children) (Yes or No).

Tenure Months: The total number of months the customer has been with the company. A value of '0' indicates a new customer who has been with the company for less than a month.

Phone Service: Indicates if the customer has phone service (Yes or No).

Multiple Lines: Indicates if the customer has multiple phone lines (Yes, No, or No phone service).

Internet Service: The type of internet service the customer has (Fiber optic, DSL, or No if they don't have internet service).

Online Security: Indicates if the customer has the online security add-on service (Yes, No, or No internet service if they don't have internet).

Online Backup: Indicates if the customer has the online backup add-on service (Yes, No, or No internet service).

Device Protection: Indicates if the customer has the device protection add-on service (Yes, No, or No internet service).

Tech Support: Indicates if the customer has the tech support add-on service (Yes, No, or No internet service).

Streaming TV: Indicates if the customer has the streaming TV add-on service (Yes, No, or No internet service).

Streaming Movies: Indicates if the customer has the streaming movies add-on service (Yes, No, or No internet service).

Contract: The type of contract the customer has (Month-to-month, One year, or Two year).

Paperless Billing: Indicates if the customer uses paperless billing (Yes or No).

Payment Method: The customer's preferred payment method (e.g., Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)).

Monthly Charges: The monthly amount charged to the customer.

Total Charges: The total amount charged to the customer over their entire tenure.

Churn Label: Indicates whether the customer has churned (left the company). Yes means they left, No means they are still a customer.

Churn Value: A binary representation of the churn label (1 for churned, 0 for not churned).

Churn Score: A numerical score (likely a model's prediction) indicating the likelihood of churn. Higher scores suggest a higher risk of churning.

CLTV: Customer Lifetime Value. A metric that estimates the total revenue a business can reasonably expect from a single customer account.

Churn Reason: The primary reason provided by the customer for churning (e.g., Competitor made better offer, Moved, Price too high). This column is empty for customers who have not churned.

​
