# House Sales Analysis and Prediction

## Project Overview
You are a Data Analyst working at a Real Estate Investment Trust. The Trust would like to start investing in Residential real estate. You are tasked with determining the market price of a house given a set of features. You will analyze and predict housing prices using attributes or features such as square footage, number of bedrooms, number of floors, and so on.

### Data Sources
The dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015.
[Housing dataset](https://www.kaggle.com/datasets/harlfoxem/housesalesprediction)

### Tools
* JupyterLab notebook

### Data cleaning/preprocessing
- Check for missing values in key features.
- Replace missing values with feature mean.

### Exploratory Data Analysis
- Examine feature correlation with target feature (price).
- Use boxplot and regplot to explore various features against target.

<img width="591" alt="Screenshot 2024-08-26 at 10 33 36" src="https://github.com/user-attachments/assets/dcd5f92a-90f5-496b-8e1a-d2ea7f36c2db">

### Model Development
The model was built using Python's scikit-learn linear regression model. The model was training using train-test-split method on housing dataset.

### Model Evaluation and Refinement
The model was refined using ridge regression and score.
