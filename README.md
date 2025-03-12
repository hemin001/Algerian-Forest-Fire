🔥 Algerian Forest Fires Analysis & Prediction 🌲
Project Overview
This project explores the Algerian Forest Fires Dataset, which contains weather and fire data from two regions in Algeria (Bejaia and Sidi Bel-abbes) during the summer of 2012. The goal is to understand fire patterns, visualize key features, and build regression models to predict the Fire Weather Index (FWI).

📂 Dataset Details
Instances: 244 (122 per region)
Time Period: June to September 2012
Attributes: 11 features + 1 class label (Fire/Not Fire)
Key Features:
Weather Observations: Temperature, Humidity, Wind Speed, Rainfall
FWI Components: FFMC, DMC, DC, ISI, BUI, FWI
Class Label: Fire or Not Fire
🛠️ What I Did
1. Data Preprocessing & Cleaning
Handled missing values and corrected data types
Added a Region column (0 for Sidi Bel-abbes, 1 for Bejaia)
Split the combined CSV into separate regional data
2. Exploratory Data Analysis (EDA)
Visualizations: Density plots, pie charts, and bar graphs
Correlation Analysis: Heatmaps to identify feature relationships
Outlier Detection: Boxplots to spot anomalies
3. Monthly Fire Analysis
Examined fire occurrence trends across months for each region
4. Feature Scaling
Applied Standard Scaling to normalize features
5. Regression Modeling
Built models to predict Fire Weather Index (FWI) using:
Linear Regression
Ridge Regression
Lasso Regression
ElasticNet Regression
6. Model Evaluation
Compared models using:
Mean Absolute Error (MAE)
R² Score
Performed Cross-Validation for Ridge, Lasso, and ElasticNet
🚀 Results & Insights
Weather conditions like temperature and wind speed significantly influence fire risk
Ridge and ElasticNet regression models performed best for FWI prediction
Standard scaling improved model accuracy and reduced error
📊 Technologies Used
Python
Pandas, NumPy for data manipulation
Matplotlib, Seaborn for data visualization
Scikit-learn for machine learning models
🧠 Key Learnings
Importance of EDA and visual analysis in understanding data
How feature scaling affects regression models
Practical experience with model evaluation metrics and cross-validation
