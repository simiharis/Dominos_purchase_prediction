# Dominos_purchase_prediction
A machine learning project that forecasts pizza sales and automates ingredient purchase orders for optimized inventory management at Dominos.

Problem Statement
This project focuses on optimizing Domino's inventory management by building a predictive system that forecasts pizza sales and generates purchase orders for ingredients. By leveraging historical sales data, the goal is to develop a model that accurately predicts future sales, allowing Domino's to order the right amount of ingredients, minimizing waste, and preventing stockouts.

🎯 Objective:
To Develop a predictive model to forecast pizza sales.
To Create a purchase order system that calculates the required quantities of ingredients based on the sales forecast.
🔍 Dataset Overview
The project involves two datasets: Pizza Sales and Pizza Ingredients.

The Pizza Sales Dataset comprises 48,620 entries, each detailing an individual sale. This includes information such as pizza_id (a unique identifier for the sale), order_id (linking to a specific order), pizza_name_id (a unique identifier for each pizza), quantity (number of pizzas sold), order_date and order_time (when the sale occurred), unit_price and total_price (pricing details), as well as pizza_size and pizza_category (size and type of pizza). This dataset offers a thorough view of sales, covering pricing, timing, and pizza characteristics.

The Pizza Ingredients Dataset consists of 518 entries that describe the ingredients for various pizzas. It includes pizza_name_id (a unique identifier for each pizza), pizza_name (name of the pizza), pizza_ingredients (list of ingredients), and Items_Qty_In_Grams (the quantity of each ingredient used). This dataset provides detailed insights into the composition of each pizza and the amounts of ingredients required.

You can download the datasets from the following links:

Download pizza_sales Dataset

Download pizza_ingredients Dataset

📊 Metrics
Mean Absolute Percentage Error: Used to evaluate the accuracy of forecasting models. It measures the average absolute percentage error between the predicted values and the actual values.
💡 Business Use Cases
Inventory Management: Ensuring optimal stock levels to meet future demand without overstocking.
Cost Reduction: Minimizing waste and reducing costs associated with expired or excess inventory.
Sales Forecasting: Accurately predicting sales trends to inform business strategies and promotions.
Supply Chain Optimization: Streamlining the ordering process to align with predicted sales and avoid disruptions.
🛠️ Approach
I. Data Preprocessing
Data Cleaning ensures the dataset's accuracy and consistency through:

Handling Missing Data:

Detected missing values.
Replaced missing values using mean, median, mode, or placeholders.
Removed columns or rows with excessive missing data if necessary.
Removing Inconsistent Data:

Checked for format consistency and valid ranges.
Fixed inconsistencies, such as standardizing text and correcting typos.
Handling Outliers:

Identified outliers using statistical methods or visualizations.
Removed, transformed, or categorized outliers based on their impact.
II. Exploratory Data Analysis (EDA)
Exploratory Data Analysis (EDA) discovers patterns, relationships, and anomalies in the data.

III. Sales Prediction
Sales Prediction involves Time Series Forecasting, a technique used to predict future values based on historical data collected over time. 

Features
Forecast weekly sales for each pizza type using historical sales data.
Calculate the total quantity of ingredients required for the forecasted sales.
Provide visualizations and summary reports for inventory planning.

Results
Sales Forecast:
Predicts weekly sales for each pizza type using ARIMA.
Ingredient Planning:
Calculates the total quantity of each ingredient required for the forecasted sales.
Visualizations:
Includes bar charts for ingredient requirements and sales trends.
