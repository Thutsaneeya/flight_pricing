# ✈️ Flight Ticket Price Analysis
View the full analysis: [flight_pricing.ipynb](notebooks/flight_pricing.ipynb)

## 📌 Project Overview
This project explores the distribution and variability of flight ticket prices across different airlines, destinations, and departure times.  
It applies data cleaning, outlier filtering, and visualization techniques to uncover pricing patterns and insights.

## 🎯 Objectives
- Analyze ticket prices across airlines and destinations  
- Explore how time and cabin class affect fare variability  
- Uncover pricing patterns driven by demand and airline strategy

## 📂 Dataset
- **Source**: [Flight Ticket Price Prediction – Kaggle](https://www.kaggle.com/datasets/shubhambathwal/flight-price-prediction/data)
- **Rows**: ~300,153 flight records
- **Key Columns**: `price`, `airline`, `destination_city`, `departure_time`, `class`

## 🧼 Data Cleaning
- Removed null values and irrelevant columns
- Applied IQR method to filter out price outliers
- Standardized categorical values for consistency

## 📊 Exploratory Data Analysis (EDA)
- Histogram of ticket price distribution
- Boxplot comparing top 3 destinations vs others
- Barplot of average price by airline
- Heatmap showing price variation by airline and departure time

## ✨ Key Insights
- Full-service airlines (e.g., Vistara, Air India) show significantly higher fares than low-cost carriers (e.g., AirAsia, IndiGo)
- Top 3 destinations (Bangalore, Mumbai, Delhi) have relatively stable and lower average prices
- Ticket prices peak during Evening 🌇 and drop during Late-Night 🌙 hours
- Pricing is influenced by market demand, airline strategy, and passenger behavior

## 🛠️ Tools & Libraries
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- Jupyter Notebook

## 📁 File Structure
- flight_pricing
    - |data/ → Raw data
    - notebooks/ → EDA and visualization
    - README.md → Project overview