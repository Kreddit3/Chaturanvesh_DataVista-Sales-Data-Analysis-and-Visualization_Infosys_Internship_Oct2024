# DataVista-Sales-Data-Analysis-and-Visualization_Infosys_Internship_Oct2024

📊 Overview
This project focuses on analyzing and predicting US regional sales trends using historical sales data. The dataset contains information about various sales channels, products, customer details, and order specifics. By applying visualization techniques and machine learning models, we aim to gain insights and make accurate revenue predictions.

🗂️ Project Structure
Data Preprocessing and Cleaning:

Handled missing values.
Converted date columns to a usable format.
Aggregated sales data for trend analysis.
Data Analysis and Visualization:

Used interactive plots (e.g., with Plotly) to explore:
Regional sales trends.
Sales performance by channel.
Top-performing products and stores.
Visualized monthly and yearly sales performance.
Machine Learning Models:

Implemented predictive models for:
Revenue Prediction:
Linear Regression
Random Forest Regression
Gradient Boosting
Time Series Forecasting:
ARIMA
LSTM
Evaluated models using metrics like MSE and R² Score.
Insights and Business Applications:

Identified top-performing regions, stores, and products.
Predicted future revenue to assist in inventory and financial planning.
Highlighted sales channel performance to optimize marketing efforts.
💾 Dataset
Name: US_Regional_Sales_Data.csv
Size: 17,992 rows and 15 columns
Features:

Order Information: OrderNumber, OrderDate, ShipDate, DeliveryDate.
Sales Details: Revenue, Order Quantity, Discount Applied, Unit Cost, Unit Price.
Channel & Location: Sales Channel, StoreID, WarehouseCode.
Customer Information: SalesTeamID, CustomerID.
Target: Revenue – Used as the primary variable for predictive analysis.

🔧 Technologies Used
Programming: Python
Libraries:
Data Analysis: Pandas, NumPy
Visualization: Matplotlib, Seaborn, Plotly
Machine Learning: scikit-learn, statsmodels, TensorFlow/Keras
Time Series Analysis: ARIMA, LSTM
Tools: Jupyter Notebook, GitHub
📈 Key Visualizations
Monthly and Yearly Sales Trends:
Line charts showing historical sales performance.
Channel-Wise Sales Analysis:
Pie charts and bar plots highlighting contributions from each sales channel.
Top Products and Stores:
Bar plots and heatmaps of revenue contributions.
Time Series Forecasting:
Historical vs. forecasted sales using ARIMA and LSTM.
🧠 Machine Learning Models and Results
Model	Purpose	Metrics (on Test Set)
Linear Regression	Revenue Prediction	MSE: X, R²: Y
Random Forest	Revenue Prediction	MSE: X, R²: Y
Gradient Boosting	Revenue Prediction	MSE: X, R²: Y
ARIMA	Time Series Forecasting	Next 12-month revenue trends
LSTM	Time Series Forecasting	Long-term forecasting accuracy
🚀 How to Run the Project
Clone the Repository:

git clone https://github.com/yourusername/sales-analysis-ml.git
cd sales-analysis-ml
Install Dependencies:

pip install -r requirements.txt
Run the Jupyter Notebook:

Open Sales_Analysis.ipynb in Jupyter Notebook or Jupyter Lab.
Execute the cells step-by-step.
Explore Visualizations:

Visual outputs are generated inline in the notebook.
Interactive charts (Plotly) open in a browser.
Model Predictions:

Modify steps in ARIMA/LSTM to forecast further into the future.
Change input features to test with different scenarios.
🎯 Future Enhancements
Expand analysis to include seasonality and holidays.
Build a recommendation system for inventory optimization.
Use advanced deep learning models like Transformer for time series forecasting.
Explore additional datasets to identify broader market trends.
🤝 Contributing
Contributions, issues, and feature requests are welcome!
Feel free to fork the repository and submit pull requests.

📜 License
This project is licensed under the MIT License. See LICENSE for details.

