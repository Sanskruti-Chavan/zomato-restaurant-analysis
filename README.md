# 🍽️ Zomato Data Analysis Project

## 📌 Overview
This project focuses on analyzing restaurant data from Zomato using Python.  
The goal is to understand customer preferences, restaurant performance, and key factors influencing ratings.

The project uses **Pandas, NumPy, Matplotlib, and Seaborn** for data cleaning, transformation, and visualization.

---

## 🎯 Objective
- Analyze restaurant data to identify patterns in ratings, cost, and popularity  
- Understand customer behavior and preferences  
- Generate meaningful insights for better decision-making  

---

## 📊 Dataset Information
- Dataset contains **50,000+ restaurant records**  
- Key features:
  - Location  
  - Cuisines  
  - Ratings  
  - Votes  
  - Cost  
Source: Kaggle Zomato Dataset  

---

## 🧹 Data Cleaning
- Removed unnecessary columns (url, phone, reviews, etc.)  
- Handled missing values  
- Cleaned **rate column** (converted from string to numeric)  
- Converted cost into numeric format  
- Removed duplicate records  

---

## ⚙️ Feature Engineering
- Created **cost_per_person** for better affordability analysis  
- Created **rating_category**:
  - Excellent (≥ 4)  
  - Good (3–4)  
  - Average (< 3)  

---

## 📈 Visualizations

The project includes multiple visualizations:

- 🥧 Pie Chart → Top Cuisines  
- 📊 Histogram → Rating Distribution  
- 📦 Boxplot → Online Order vs Rating  
- 🎻 Violin Plot → Table Booking vs Rating  
- 🔵 Bubble Chart → Restaurant Type vs Rating  
 
---

## 🔍 Key Insights
- Most restaurants have ratings between **3.5 and 4.2**  
- North Indian and Chinese cuisines dominate the market  
- Restaurants offering **online ordering** tend to have better ratings  
- **Table booking restaurants** show higher and more stable ratings  
- Higher cost does not always guarantee higher ratings  


---

## 🍽️ Food Journal Insight
- Customers prefer familiar and popular cuisines  
- Convenience (online ordering, booking) improves satisfaction  
- Votes indicate trust and repeated visits  
- Customer decisions depend on **quality, cost, and location**  

---

## 🏁 Conclusion
Customer experience, service quality, and convenience play a bigger role than cost in determining restaurant success.  
Data analysis helps transform raw data into actionable insights.

---

## 🛠️ Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  

---

## 👩‍💻 Author
**Sanskruti Chavan**


---

## ⭐ Acknowledgement
Dataset sourced from Kaggle for educational and analytical purposes.
