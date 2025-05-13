# House Sales Analysis and Prediction

This project involves analyzing and predicting housing prices using real estate data from King County, Washington — which includes Seattle. As a data analyst for a Real Estate Investment Trust, your objective is to assess how key housing features affect market value and develop a predictive model to support investment decisions.

### Project Overview
The primary goal is to determine the market price of a house based on features such as:

Square footage
Number of bedrooms
Number of bathrooms
Number of floors
Waterfront view, and more
Using a combination of data preprocessing, exploratory data analysis, and regression modeling, this project delivers a solution for estimating housing prices with reasonable accuracy.

📁 Dataset
Source: King County Housing Sales Dataset
Timeframe: May 2014 – May 2015
Region: King County, Washington (including Seattle)
Each row in the dataset represents a house sale and includes features such as location, size, condition, and sale price.

🧰 Tools and Libraries
Python
JupyterLab
Pandas, NumPy
Matplotlib, Seaborn
Scikit-learn
🧹 Data Cleaning & Preprocessing
Checked for and handled missing values in key features
Replaced missing data with mean imputation
Ensured data types and ranges were appropriate for modeling
📊 Exploratory Data Analysis (EDA)
Used visual and statistical tools to understand feature relationships with the target variable (price):

Box plots and regression plots to inspect key variables
Correlation matrix to identify strong predictors of price
Observed patterns such as higher prices for waterfront properties, larger homes, and newer constructions

<img width="591" alt="Screenshot 2024-08-26 at 10 33 36" src="https://github.com/user-attachments/assets/dcd5f92a-90f5-496b-8e1a-d2ea7f36c2db">
<img width="580" alt="Screenshot 2024-08-26 at 10 43 36" src="https://github.com/user-attachments/assets/3a2136aa-1d11-4383-9c24-e0d0d2767723">

🧠 Model Development
Trained a Linear Regression model using train/test split
Applied scikit-learn for model building and evaluation
Evaluated model performance using R² score and residual analysis
🔧 Model Refinement
Implemented Ridge Regression to reduce overfitting
Compared model scores before and after regularization
Selected features contributing most to prediction accuracy
✅ Key Takeaways
Strong correlation between living area (sqft) and price
Waterfront view, grade, and condition were key drivers of price
Ridge regression improved generalization without compromising accuracy
The model serves as a starting point for automated real estate valuation

### Model Evaluation and Refinement
The model was refined using ridge regression and score.
