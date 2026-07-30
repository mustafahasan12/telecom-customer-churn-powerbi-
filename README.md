# 📊 Telecom Customer Churn Analysis Dashboard

An interactive **Power BI** dashboard designed to analyze customer churn patterns for a telecom company. The dashboard helps stakeholders monitor customer retention, identify high-risk customer segments, and understand the key factors contributing to customer churn through interactive KPIs and visualizations.

---

## 🚀 Features

### 🎯 Interactive Filters
- Gender
- Contract Type
- Internet Type
- City
- Payment Method
- Customer Status
- Churn Reason

### 📈 KPI Cards
- Total Customers
- Churn Customers
- Active Customers
- Total Population
- Total Revenue
- Average Monthly Charges

### 📊 Visualizations
- Customer Status Distribution
- Customer Churn by Contract
- Customer Churn by City
- Customer Churn by Internet Type
- Customer Churn by Gender
- Payment Method Analysis
- Monthly Charges Distribution

---

## 🗄️ Data Model

This project follows a **Star Schema** design.

### Fact Table
- `telecom_customer_churn`

### Dimension Table
- `telecom_zipcode_population`

### Relationship
- One-to-Many (`Zip Code`)

---

## 📐 DAX Measures

The dashboard includes several DAX measures, including:

- Total Customers
- Churn Customers
- Active Customers
- Churn Rate
- Total Revenue
- Average Monthly Charges
- Total Population

---

## 📌 Business Insights

- Customers with **Month-to-Month** contracts have the highest churn rate.
- **Fiber Optic** customers experience the highest number of churn cases.
- **Bank Withdrawal** is the most commonly used payment method among churned customers.
- Customer churn varies significantly across different cities.
- Customer demographics and service types provide valuable insights for improving retention strategies.

---

## 🛠️ Tools & Technologies

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Star Schema
- Data Visualization

---

## 💡 Skills Demonstrated

- Data Cleaning
- Data Modeling
- Relationship Management
- DAX Calculations
- KPI Development
- Interactive Dashboard Design
- Business Intelligence
- Customer Churn Analysis
- Data Visualization

---

⭐ If you found this project helpful, consider giving it a **Star** on GitHub.
