# 📘 Fitness Analytics Dashboard – Power BI Project

A complete Fitness/Gym Analytics Dashboard built using **Power BI**, designed to help gym owners and managers understand their members, revenue, expenses, BMI, goals, and overall business performance through clear and interactive visuals.

---

## 🧩 Project Overview

This Power BI dashboard combines member data, payments, expenses, and fitness metrics into a single analytical platform.  
It provides insights into:

- Active vs Expired memberships  
- Revenue, expenses, and profit trends  
- Age & Gender distribution  
- Membership plan performance (Platinum/Gold/Silver)  
- BMI categories & fitness goals  
- Individual calorie calculations (BMR, TDEE, Maintenance Calories)  

The dashboard makes it easy for gym owners to make **data-driven decisions**, improve member retention, and optimize operational efficiency.

---

## 📑 Dashboard Pages

### **1️⃣ Home Page**
A clean introduction page showing total clients, trainers, revenue, and expenses.

### **2️⃣ Overall Dashboard**
- Monthly Revenue & Expenses  
- Profit trends  
- Membership plan insights  
- Active vs Expired comparisons  
- Membership percentage  
- Monthly membership count  

### **3️⃣ Members Dashboard**
- Age category analysis  
- Gender distribution  
- Active vs expired members by age  
- Member-level details (BMI, Goals, Status, Join Date)

### **4️⃣ Calculator Page**
A personalized fitness calculator that computes:
- BMI  
- BMR  
- TDEE  
- Maintenance calories  
- Mild/Weight loss calories  
- Extreme weight loss calories  

Includes **Gender selection** and **Activity Type dropdown** for accurate results.

---

## 🗂️ Dataset Information

### **Users Table**
Contains member demographics and fitness data:
- UserID, UserName, Age, Gender  
- JoinDate, Goal, Trainer Name  
- Membership plan, Start/End date, Status  
- Height, Weight, BMI  

### **Payments Table**
Contains gym revenue data:
- PaymentID  
- UserID  
- Amount  
- PaymentDate  
- PaymentType  
- MembershipPlan  

### **Expenses Table**
Tracks operational spending:
- ExpenseID  
- ExpenseType  
- Amount  
- ExpenseDate  

---

## 🧠 Data Model (Star Schema)

The project is built with a **clean star schema**:

- **Users** (Main table)
- **Payments** (Fact)
- **Expenses** (Fact)
- **Calendar** (Dimension for time intelligence)
- **_Measures** (DAX calculations)
- **ColorCodes** (UI formatting)

This structure keeps the model simple, scalable, and optimized for performance.

---

## 📊 Key Measures (DAX)

- Total Revenue  
- Total Expenses  
- Profit  
- Active Members  
- Expired Members  
- Monthly Membership Count  
- BMI Category Measures  
- TDEE, BMR, Calorie Calculations  

Each measure is designed to support fitness and business insights.

---

## 🖼️ Dashboard Screenshots

All screenshots are included in the **/Screenshots** folder:

- Home Page  
- Overall Dashboard  
- Members Dashboard  
- Calculator Page  
- Data Model  

---

## 🛠️ Tools Used
- Power BI Desktop  
- Microsoft Excel  
- DAX (Data Analysis Expressions)  
- Data Cleaning & Modeling  

---

## 🎯 Conclusion

This project provides a **360° analytical view** of gym operations.  
It helps the gym understand member activity, financial performance, BMI patterns, and seasonal membership trends — enabling smarter decisions and better member engagement.

---

## 👤 Author
**Roopesh**  
Power BI | Data Analytics | Fitness Analytics
