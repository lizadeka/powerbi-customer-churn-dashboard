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
- **Churn %** = Lost Revenue / Lost Revenue + Retained Revenue 

---

## 📊 Dashboard Highlights
### **Page 1 – Overview**

<img width="1300" height="730" alt="image" src="https://github.com/user-attachments/assets/626ccb34-2246-4444-aa0d-f2dc9f8533ec" />


### **Page 2 – Deep Dive**

<img width="1302" height="711" alt="image" src="https://github.com/user-attachments/assets/37f5a0b7-c2a3-47d2-b3d0-5ca1040ff1fc" />


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

