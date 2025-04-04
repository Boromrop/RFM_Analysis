# RFM_Analysis

## 📊 Project Overview

This project performs **Customer Segmentation** using the **RFM (Recency, Frequency, Monetary)** model. It was developed as part of the *Data Analytics* course at the Royal University of Phnom Penh, Faculty of Engineering, Department of Data Science and Engineering.

The goal is to analyze customer purchasing behavior and segment them into meaningful groups to support personalized marketing, retention strategies, and revenue optimization.

---

## 🧠 What is RFM?

RFM stands for:
- **Recency (R)** – How recently a customer made a purchase.
- **Frequency (F)** – How often they purchase.
- **Monetary (M)** – How much they spend.

These three metrics are scored and used to classify customers into specific segments such as **Champions**, **Loyal Customers**, **At-Risk**, and **Lost** customers.

---

## 📂 Files Included

- `RFM_Analysis.ipynb`: Jupyter notebook with complete analysis code and visualizations.
- `Customer_Segmentation_RFM.pdf` / `.docx`: Report summarizing the project findings and methodology.
- `README.md`: You're reading it!

---

## 🧪 Methodology

1. **Data Collection**
   - 4,905 orders from 995 unique customers
   - Fields: Customer ID, Order Date, Revenue per transaction

2. **Preprocessing**
   - Fixed column names, removed unnecessary data
   - Converted dates, cleaned nulls, removed duplicates
   - Removed data before 2004

3. **RFM Scoring**
   - Calculated recency relative to last order (Dec 30, 2006)
   - Frequency = total orders
   - Monetary = total spending
   - Applied quintile scoring (1–5)

4. **Segmentation**
   - Grouped customers into:
     - Champions
     - Loyal Customers
     - Potential Loyalists
     - At-Risk Customers
     - Lost Customers

---

## 📈 Key Results

- **Total Revenue**: \$463,980
- **Unique Customers**: 995
- **Average Order Value**: \$94.59
- **Churn Rate**: 59.4% of customers inactive in last 180 days
- **Champions**: 15.98% – most valuable group

---

## 💡 Recommendations

1. **Retention Strategies** for at-risk and high-value customers
2. **Loyalty Programs** for Potential Loyalists
3. **Reactivation Campaigns** for Lost Customers
4. **Data-Driven Personalization** for all marketing efforts

---

## 📚 References

1. Marketing91 - What is RFM Analysis?
2. Rsquared Academy Blog - Customer Segmentation using RFM
3. rfm Package Documentation
4. Towards Data Science - RFM Segmentation with Python
5. Medium Blog by Adi Saputra - What is RFM?

---

## 👨‍💻 Authors

- **ROP BOROM**
- **VARN CHORRATTANAK**

**Lecturer**: Mr. CHAP CHAN PISETH  
**Academic Year**: 2024–2025

---

## 🧠 License

This project is for academic use only. Contact the authors for further collaboration or inquiries.

