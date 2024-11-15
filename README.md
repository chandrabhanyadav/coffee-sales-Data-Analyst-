#☕Coffee Sales Analysis 📊
📋 Project Overview
This project focuses on analyzing coffee sales data to extract insights and predict future sales. The project includes Exploratory Data Analysis (EDA), Time Series Forecasting, and a Machine Learning model to predict sales using historical data. The primary goal is to understand sales trends, identify peak sales periods, and forecast future sales to drive data-driven business strategies.
DATASET =(https://github.com/chandrabhanyadav/coffee-sales-Data-Analyst-/blob/main/Coffee_sales.csv)
🗂️ Table of Contents
Project Overview
Technologies Used
Dataset Description
Project Workflow
Exploratory Data Analysis (EDA)
Time Series Forecasting
Machine Learning Model
Results
Conclusion
💻 Technologies Used
Python (Pandas, Numpy, Matplotlib, Seaborn, Statsmodels, Scikit-learn)
Jupyter Notebook for analysis and visualization
📊 Dataset Description
The dataset, Coffee_sales.csv, includes the following columns:

date: The date of the sale.
datetime: Timestamp of the sale (date and time).
coffee_name: Name of the coffee sold.
money: Revenue generated by the sale.
card: Customer card identifier (or 'Unknown' for missing values).
🛠️ Project Workflow
Data Loading & Preprocessing:

Loading the data using pandas.
Converting date and datetime columns to datetime format.
Handling missing values by filling missing customer card information with 'Unknown'.
Exploratory Data Analysis (EDA):

Analyzing sales trends over time.
Identifying the most popular coffee types.
Visualizing sales distribution by hour and day of the week.
Understanding customer purchasing behavior.
Time Series Forecasting:

Using the ARIMA model to forecast daily and monthly sales.
Machine Learning Model:

Building a Random Forest Regressor to predict daily sales based on features like day of the week, month, hour, and previous day sales.
🔍 Exploratory Data Analysis (EDA)
Sales Trend Analysis
Total Sales Over Time: A line plot visualizing how sales have changed over time.
Sales by Coffee Type: A bar chart showing total revenue generated by each coffee type.
Hourly Sales Distribution: A bar chart visualizing sales peaks during the day.
Sales by Day of the Week: Analysis to identify which days generate the highest sales.
Customer Purchase Analysis
Top 10 Frequent Customers: Identifying the most frequent customers.
Top 10 Customers by Average Spend: Finding the customers with the highest average spend.
📈 Time Series Forecasting
Daily Sales Forecast: Using the ARIMA model to forecast sales for the next 30 days.
Monthly Sales Forecast: Forecasting total sales for the next 3 months.
🤖 Machine Learning Model
Feature Engineering: Extracted features like day_of_week, month, hour, and prev_day_sales.
Model Used: Trained a Random Forest Regressor to predict sales.
Model Evaluation:
Mean Squared Error (MSE): Measures prediction error.
R-squared: Indicates how well the model fits the data.
Results
The model achieved an R-squared score of X.XX (replace with your actual result).
The Mean Squared Error (MSE) was X.XX (replace with your actual result).
📝 Conclusion
The EDA revealed key insights into customer behavior and sales trends, helping optimize inventory and marketing strategies.
The time series forecast provides an estimate of future sales, aiding in demand planning.
The Random Forest model predicts daily sales with a reasonable accuracy, supporting strategic decision-making.
