# 🍔 Food Delivery Data Analysis

## 📌 Project Overview
This project analyzes a real-world food delivery dataset to understand customer behavior, restaurant performance, and revenue trends. The goal was to clean, merge, and analyze data from three different sources (CSV, JSON, and SQL) to derive actionable business insights.

## 📂 Dataset Description
The analysis is based on three simulated datasets:
1. **orders.csv**: Transactional data containing order IDs, dates, and amounts.
2. **users.json**: Customer demographic data including membership status (Gold/Regular).
3. **restaurants.sql**: Restaurant details including cuisine, city, and ratings.

## 🛠️ Tech Stack
- **Python**: Core programming language.
- **Pandas**: For data manipulation and merging (Left Joins).
- **SQLite3**: To parse and extract data from SQL files.
- **Data Cleaning**: Handling missing values, parsing dates, and type conversion.

## 📊 Key Insights & Results
- **Top Revenue City (Gold Members):** Chennai
- **Highest Revenue Cuisine:** Mexican
- **Customer Behavior:** Over 2,500 users spent more than ₹1000.
- **Membership Impact:** Gold members contribute approximately 50% of total orders.

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone [https://github.com/amitgavane/Food-Delivery-Hackathon.git](https://github.com/amitgavane/Food-Delivery-Hackathon.git)
  2. pip install pandas
  3. jupyter notebook Food_Delivery_Analysis.ipynb