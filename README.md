# Churn Rate Dashboard

This repository contains a PDF version of a churn rate dashboard that visualizes customer churn trends and provides insights into factors contributing to churn. The dashboard segments data across different demographic categories and services, helping businesses identify high-risk segments and create effective retention strategies.

## Key Data Fields
- **customerID**: Unique identifier for each customer.
- **gender**: Gender of the customer.
- **SeniorCitizen**: Whether the customer is a senior citizen (1 = Yes, 0 = No).
- **Partner**: Whether the customer has a partner (Yes/No).
- **Dependents**: Whether the customer has dependents (Yes/No).
- **tenure**: Number of months the customer has been with the service.
- **PhoneService**: Whether the customer subscribes to phone service (Yes/No).
- **MultipleLines**: Whether the customer has multiple phone lines (Yes/No).
- **InternetService**: Type of internet service (DSL/Fiber optic).
- **OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport**: Service subscriptions related to security, backup, protection, and tech support.
- **StreamingTV, StreamingMovies**: Streaming service subscriptions (Yes/No).
- **Contract**: Type of contract (Month-to-Month, One year, Two year).
- **PaperlessBilling**: Whether the customer uses paperless billing (Yes/No).
- **PaymentMethod**: Payment method used (e.g., Electronic check, Mailed check, Bank transfer).
- **MonthlyCharges**: Monthly charges for the customer.
- **TotalCharges**: Total amount charged to the customer.
- **Churn**: Whether the customer has churned (Yes/No).

## Dashboard Sections

### 1. Overview KPIs
- **Total Customers**
- **Churn Rate (%)**
- **Avg. Monthly Charges**
- **Avg. Tenure**
- Visualization Type: **Scorecards, KPI Tiles**

### 2. Churn Trend
- **Churn by Tenure**: A line chart or histogram showing churn trends over the customer's tenure.
- **Monthly Churn Rate**: If time-based data is available, this shows churn by month.

### 3. Demographics Breakdown
- **Churn by Gender**: A pie chart visualizing churn based on gender.
- **Churn by Senior Citizen**: A bar chart showing churn by senior citizen status.
- **Churn by Partner/Dependents**: A stacked bar chart showing churn based on whether customers have a partner or dependents.

### 4. Services & Churn
- **Churn by Internet Service**: A bar chart showing churn based on the type of internet service.
- **Churn by Online Security, Tech Support, Streaming**: Grouped bar charts showing churn based on service subscriptions.
- **Churn vs. Multiple Lines or Phone Service**: A comparison of churn with respect to phone service and multiple lines.

### 5. Contract & Billing
- **Churn by Contract Type**: A bar chart showing churn by contract type (e.g., Month-to-Month contract = higher churn).
- **Churn by Paperless Billing**: A bar chart showing churn based on paperless billing status.
- **Churn by Payment Method**: A bar chart showing churn based on payment method.

### 6. Revenue Impact
- **Avg. Monthly Charges by Churn Status**: A bar chart showing the average monthly charges for customers who churned versus those who did not.
- **Total Revenue Lost to Churn**: A metric showing the total revenue lost due to churn.

## Conclusion
This dashboard provides valuable insights into customer churn, enabling companies to pinpoint high-risk segments and take action to improve retention strategies and reduce churn. The PDF version of the dashboard is available in this repository for reference.
