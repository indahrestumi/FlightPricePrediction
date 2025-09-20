# Final Project Data Science : Flight Price Prediction
This project focuses on predicting **flight ticket prices** using machine learning.  
Accurate price prediction can help **airlines** optimize pricing strategies and **customers** find the best time to buy tickets.

## Business Objective
Flight ticket pricing is dynamic and influenced by multiple factors such as departure date, duration, airline, and stops.  
The main objectives of this project are:
- Understand key factors that affect flight prices.  
- Build a machine learning model to predict flight ticket prices.  
- Provide insights that can support **revenue management** for airlines and **better decision-making** for customers.  

## Dataset
- **Source**: Flight Price Dataset (Kaggle) 
- **Key Features**:
  - Airline   
  - Source & Destination  
  - Total Stops  
  - Duration  
  - Departure & Arrival time  
  - Price (target variable)
    
## Methodology
1. **Data Inspection**
   - Conducting a comprehensive data inspection by thoroughly examining the dataset’s structure
   - Verifying the data types of each column to ensure consistency, identifying and handling any missing values to maintain data integrity
   - Detecting duplicated records to prevent redundancy and potential bias in subsequent analyses
   - 
1. **Exploratory Data Analysis (EDA)**  
   - Price distribution & outlier detection  
   - Relationship between features  

2. **Data Preprocessing**  
   - Handling missing values  
   - Encoding categorical features  
  
3. **Modeling**  
   - Models tested: Linear Regression, Decision Tree, Random Forest, XGBoost & LightBM 
   - Evaluation metrics: MAE, RMSE, R², MAPE  

4. **Model Selection**  
   - Compare model performance and choose the best predictor
     
## Results & Insights 
- The analysis results indicate that Random Forest is the best model as it provides the most accurate and stable ticket price predictions with a low error rate. 
- The main factors influencing the price are flight class, duration, and booking time.

## Business Recommendation
- Revenue Growth: Implementing dynamic pricing based on class, duration, and booking timing to maximize revenue.

- Operational Efficiency: Optimizing load factor to reduce empty seats and increase profitability.

- Customer Loyalty: Leveraging price predictions to personalize promotions, thereby enhancing customer retention and value.

  

