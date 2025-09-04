# 📊 Power BI Customer Churn Analysis Dashboard

This project analyzes customer churn for a telecom dataset using **Power BI**.  
The dashboard is designed to highlight key patterns in customer attrition and uncover business insights to improve retention.

---

## 🚀 Project Overview
Customer churn (when customers stop using a service) is a critical metric for subscription-based businesses.  
This dashboard answers:
- How big is churn and where is it concentrated?
- Which customer segments are most likely to churn?
- What revenue is lost due to churn?
- Which services and pricing tiers drive customer retention?

---

## ⚙️ Data Preparation
Performed in **Power Query**:
- Converted `Yes/No` columns into binary (1/0)
- Handled missing values (e.g., replaced blank `TotalCharges` with 0)
- Grouped customers by **tenure ranges**
- Created clean datasets for **analysis-ready modeling**

---

## 📐 DAX Measures
Some of the custom measures:
- **Churn Rate** = % of customers who churned  
- **Lost Revenue** = Total monthly charges of churned customers  
- **Retained Revenue** = Total monthly charges of retained customers  
- **Profit Margin %** (for scenario analysis)  

---

## 📊 Dashboard Highlights
### **Page 1 – Overview**
- Donut Chart → Churn split (Yes vs No)  
- KPI Cards → Churn Rate, Lost Revenue, Retained Revenue  
- Column Chart → Churn by Monthly Charges (bucketed)  

### **Page 2 – Deep Dive**
- Churn by **Tenure Groups**  
- Churn by **Contract Type**  
- Churn by **Services (Internet, Streaming, Security, etc.)**  
- Churn by **Monthly Charges (Bins)**  
- **Slicers** for Gender, Senior Citizen, Payment Method, Internet Service  

---

## 🎯 Key Insights
- 📈 **New customers (0–12 months)** show the highest churn.  
- 📉 **Month-to-Month contracts** have significantly higher churn than longer contracts.  
- 💸 Customers with **higher monthly charges** tend to churn more.  
- 🛠️ Additional services (like Online Security) reduce churn probability.  

---

## 🛠️ Tools Used
- **Power BI** – Dashboarding & DAX measures  
- **Power Query** – Data transformation  
- **Excel/CSV dataset** – Telecom churn data  

---

## 📌 How to Use
1. Download the `.pbix` file from this repo  
2. Open with Power BI Desktop  
3. Explore visuals and interact with slicers  

---

## 🙌 Acknowledgments
Dataset inspired by common **Telco Customer Churn** datasets used for analytics practice.  
This project helped me understand how to:  
- Build a Power BI dashboard from scratch  
- Apply DAX for metrics  
- Use slicers and visuals for storytelling  

---

