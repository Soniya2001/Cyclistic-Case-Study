# 🚴 Cyclistic Bike Share Analysis Project

![License: MIT]

### 📊 Google Data Analytics Capstone Project  
**Prepared by:** Soniya B (GitHub: [@Soniya2001](https://github.com/Soniya2001))  
**Year:** 2025  

---

## 📘 Project Overview

This project analyzes **Cyclistic bike-share data (Q1 2019)** to understand how **annual members** and **casual riders** use bikes differently.  
The goal is to identify trends and provide recommendations to **convert casual riders into members**, improving customer engagement and revenue.

---

## 🎯 Business Task

> Cyclistic, a bike-share company in Chicago, aims to understand how casual riders and annual members use bikes differently.  
> Insights from this analysis will guide marketing strategies to convert casual riders into annual members.

**Stakeholder:** Lily Moreno — Marketing Director, Cyclistic

---

## 🧰 Tools Used
- **Google Sheets** – Data cleaning, transformation, pivot tables, Data organization and chart formatting  


---

## 🧹 Phase II – Prepare

**Dataset:** Cyclistic Trip Data (January–March 2019)  
- Includes columns: `trip_id`, `trip_duration`, `start_time`, `end_time`, `usertype`, `gender`, `birthyear`, `weekday`, and `month`.  
- Open-source, publicly available dataset.  
- Organized and stored in Google Sheets for analysis.

---

## ⚙️ Phase III – Process

Performed complete data cleaning and transformation:

- Removed null, blank, and duplicate values.  
- Calculated **trip duration** in minutes:  
  `=ROUND((C2-B2)*1440)`  
- Extracted **month** and **weekday** from date columns using:  
  `=TEXT(A2,"mmm")` and `=WEEKDAY(B2,1)`  
- Calculated **age** from birth year:  
  `=2019-D2`  
- Filtered out unrealistic trip durations (`>90 minutes`) and ages (`>80 years`).  
- Verified and formatted all data types for consistency.

---

## 🔍 Phase IV – Analyze

### 📈 Pivot Tables & Charts

#### 1️⃣ User Type Distribution by Gender
- Majority of riders are **male** in both user groups.  
- **Subscribers account for 98%** of total rides.  

#### 2️⃣ Average Trip Duration by User Type
- **Casual riders** take longer trips than subscribers — likely for leisure.  

#### 3️⃣ Trips per Month
- Trips increase from **January → March**, reflecting seasonal weather improvements.

#### 4️⃣ Trips by Weekday
- Higher usage on **weekdays** — indicates commuting by subscribers.

#### 5️⃣ Average Trip Duration by User Type per Weekday
- Casual riders have longer average durations, especially on weekends.

#### 6️⃣ Trip Duration Distribution (Histogram)
- Most trips last **5–15 minutes**, suggesting short-distance use.

#### 7️⃣ Age Distribution
- Most riders fall between **25–45 years** — working professionals and students.

---

### 🔗 Correlation / Relationship Analysis

- **User Type vs Day of Week:**  
  Casual riders are more active on **weekends**, members on **weekdays**.

- **Gender vs Trip Duration:**  
  **Male riders** show slightly higher average trip durations.

- **Age vs Trip Duration:**  
  Riders aged **25–40** tend to have the longest average rides.

---

## 📢 Phase V – Share

**Key Findings:**
- Subscribers dominate ridership (98%).  
- Casual riders take longer trips but ride less frequently.  
- Trips increase with warmer weather (March > February).  
- Weekday rides are higher — commuting trend among subscribers.

---

## 🚀 Phase VI – Act

**Recommendations:**
1. Offer **discounted membership trials** for casual riders during warmer months.  
2. Promote **weekday commuting benefits** (priority docking, flexible passes).  
3. Develop **marketing campaigns targeting women** to increase participation.  
4. Create **weekend leisure plans** and **group discounts** to attract casual users.

---

## 🧾 Conclusion

The analysis highlights strong engagement from subscribers and potential growth opportunities among casual riders.  
By promoting tailored membership offers and improving inclusivity, Cyclistic can enhance both customer satisfaction and membership revenue.

---

## 🪪 License

This project is licensed under the **MIT License** — see the [LICENSE](./LICENSE) file for details.  
© 2025 Soniya2001

---

## 🙌 Acknowledgments

- **Google Data Analytics Capstone Case Study**
- **Cyclistic Bike Share Dataset** (Public data provided for educational use)
- Thanks to the [Google Data Analytics Professional Certificate](https://www.coursera.org/professional-certificates/google-data-analytics) team for guiding this learning journey.

---

## 📬 Connect with Me
**👩‍💻 Soniya B**  
📧 Email: soniyabaskaran2001@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/soniya-baskaran-617216244) | [GitHub](https://github.com/Soniya2001)

---

