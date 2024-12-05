# hemavathi
Dominos - Predictive Purchase Order System

# Problem Statement:
Dominos wants to optimize the process of ordering ingredients by predicting future sales and creating a purchase order. By accurately forecasting sales, Dominos can ensure that it has the right amount of ingredients in stock, minimizing waste and preventing stockouts. This project aims to leverage historical sales data and ingredient information to develop a predictive model and generate an efficient purchase order system.

# Business Use Cases:
1. Inventory Management: Ensuring optimal stock levels to meet future demand without overstocking.
3. Cost Reduction: Minimizing waste and reducing costs associated with expired or excess inventory.
4. Sales Forecasting: Accurately predicting sales trends to inform business strategies and promotions.
5. Supply Chain Optimization: Streamlining the ordering process to align with predicted sales and avoid disruptions.

# Data Preprocessing and Exploration
#  * Data Cleaning: 
            Remove any missing or inconsistent data entries, handle outliers, and format the data appropriately.
#  * Exploratory Data Analysis (EDA):
            Analyze sales trends, seasonality, and patterns in the historical sales data. Visualize the data to identify significant features.
# Sales Prediction
  # < Feature Engineering: 
          Create relevant features from the sales data, such as day of the week, month, promotional periods, and holiday effects.
  # < Model Selection: 
          Choose an appropriate time series forecasting model (e.g., ARIMA, SARIMA, Prophet, LSTM, Regression Model).
  # < Model Training: 
          Train the predictive model on the historical sales data.
  # < Model Evaluation: 
          Use metric Mean Absolute Percentage Error (MAPE) to evaluate model performance.

# Purchase Order Generation
     Sales Forecasting:
         Predict pizza sales for the next one week (your choice of months or weeks) using the trained model.
     Ingredient Calculation: 
         Calculate the required quantities of each ingredient based on the predicted sales and the ingredient dataset.
     Purchase Order Creation: 
         Generate a detailed purchase order listing the quantities of each ingredient needed for the predicted sales period.

 # Skills Infused
      Data cleaning and preprocessing
      Exploratory data analysis (EDA)
      Time series forecasting
      Predictive modeling
      Business decision making
      Real-world application of data science
      Regression Models


 # Technical Tags:
       * Data Cleaning
       * EDA
       * Time Series Forecasting
       * ARIMA/SARIMA/Prophet/LSTM/Regression Model
       * Predictive Modeling
       * Inventory Management
       * Python
       * Pandas
       * Scikit-learn
       * Matplotlib/Seaborn


# Data Set Explanation:
           Sales Data: Historical sales records (Date, Pizza Type, Quantity Sold, Price, Category, Ingredients)
           Ingredient Data: Ingredient requirements for each pizza type (Pizza Type, Ingredient, Quantity Needed)


# Project Deliverables & Evaluation metrics:
     1. Cleaned and preprocessed datasets
     2. Exploratory Data Analysis report
     3. Predictive model with code and evaluation metrics
     4. Detailed purchase order for the next week
     5. Project report documenting methodology, findings, and business implications







