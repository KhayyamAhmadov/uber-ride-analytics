# Uber Ride Booking Data Analysis

This repository contains a **comprehensive ride booking data analysis** using Python, Pandas, and Matplotlib/Seaborn. The analysis covers customer, driver, ride, financial, and location insights.  

The dataset used in this project is from [Uber Ride Analytics Dashboard - Kaggle](https://www.kaggle.com/datasets/yashdevladdha/uber-ride-analytics-dashboard).

---

## 📝 Project Description

The Python script performs the following analyses:

1. **Data Loading & Cleaning**  
   - Load CSV dataset.  
   - Clean column names and format date/time.  
   - Convert numeric columns and handle missing values.  

2. **General Overview & Basic Statistics**  
   - Total rides, date range, unique customers, and vehicle types.  
   - Booking status distribution.  
   - Vehicle type distribution.  

3. **Booking Status Analysis**  
   - Pie chart for booking statuses.  
   - Bar chart for top vehicle types.  
   - Hourly ride distribution.  
   - Daily ride distribution by day of the week.  

4. **Financial Analysis**  
   - Revenue statistics: total, average, max, min, median.  
   - Payment method distribution.  
   - Visualizations: booking value histogram, average by vehicle type, monthly revenue trend.  

5. **Customer & Driver Analysis**  
   - Customer statistics: total rides, total spending, completed rides.  
   - Top customers by ride count.  
   - Average driver and customer ratings.  
   - Visualizations: rides per customer, ratings distribution, cancellation reasons, ride distances.  

6. **Popular Locations**  
   - Top pickup and drop-off locations.  
   - Horizontal bar charts for top 10 locations.

---

## 📊 Visualizations

The script generates multiple plots:

- Booking status pie chart  
- Vehicle type bar chart  
- Hourly and daily ride distributions  
- Booking value histogram & average by vehicle type  
- Monthly revenue trend  
- Customer ride distribution and ratings  
- Cancellation reasons and ride distances  
- Top pickup & drop-off locations

---

## ⚡ Dependencies

- Python 3.13+  
- pandas  
- numpy  
- matplotlib  
- seaborn  

Install dependencies using:

```bash
pip install pandas matplotlib
