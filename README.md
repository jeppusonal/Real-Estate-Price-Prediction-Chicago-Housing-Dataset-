📊 Real Estate Price Prediction (Chicago Housing)



📌 Overview
This project focuses on predicting real estate listing prices in Chicago using machine learning techniques. The goal is to identify key factors influencing property prices and build accurate predictive models to assist real estate decision-making.
________________________________________
🎯 Problem Statement
How do property characteristics such as square footage, number of bedrooms, and age of the property influence listing prices?
________________________________________
📂 Dataset
•	Source: Realtor.com (scraped using Apify API) 
•	Size: ~2000 property listings 
•	Features include: 
o	Numerical: sqft, beds, baths, year_built, lot_sqft, lastSoldPrice 
o	Categorical: property type, status 
o	Target variable: listPrice 
________________________________________
⚙️ Tech Stack
•	Python 
•	Pandas, NumPy 
•	Scikit-learn 
•	XGBoost, Random Forest, CatBoost, LightGBM 
•	Matplotlib, Seaborn 
________________________________________
🔍 Approach
1. Data Preprocessing
•	Handled missing values using median imputation 
•	Encoded categorical variables (property type, status) 
•	Standardized numerical features 
•	Removed outliers using IQR method 
2. Feature Engineering
•	Created property_age from year_built 
•	Extracted year from soldOn 
•	Performed correlation analysis for feature selection 
3. Exploratory Data Analysis (EDA)
•	Visualized relationships between: 
o	Price vs square footage 
o	Price vs year built 
•	Generated correlation heatmaps 
•	Identified key influencing variables 
4. Model Development
•	Baseline: Linear Regression 
•	Advanced Models: 
o	Random Forest Regressor 
o	XGBoost Regressor 
o	CatBoost Regressor 
o	LightGBM Regressor 
o	AdaBoost Regressor 
5. Model Evaluation
•	Metrics used: 
o	Mean Squared Error (MSE) 
o	R-squared (R²) 
•	Applied cross-validation for robust evaluation 
________________________________________
📈 Results
•	Linear Regression achieved R² ≈ 0.96 
•	Ensemble models (Random Forest, XGBoost) improved performance by capturing non-linear relationships 
•	Advanced models demonstrated lower error and better generalization 
________________________________________
💡 Key Insights
•	Square footage is the strongest predictor of property price 
•	Number of bedrooms and bathrooms significantly impact valuation 
•	Property age influences price trends 
•	Ensemble models outperform linear models for complex real estate data 
________________________________________
🤝 Contribution
This was a group project completed as part of the Data Science and Innovation course.
My contributions included:
•	Data preprocessing and cleaning 
•	Feature engineering and EDA 
•	Model training and evaluation 
________________________________________
🚀 Future Improvements
•	Incorporate economic indicators (GDP, CPI, interest rates) 
•	Use SHAP values for better model interpretability 
•	Deploy as a web app (Streamlit) for real-time predictions 
________________________________________
📁 Project Structure
├── data/
├── notebooks/
├── models/
├── visuals/
├── README.md
________________________________________


