#  Car Price Prediction using Machine Learning  

### This project predicts car selling prices using machine learning. It includes data preprocessing, feature engineering, model training, and performance evaluation.  

## Libraries Used:

- pandas: Data manipulation and analysis.
- numpy: Numerical computing.
- seaborn and matplotlib: Data visualization.
- sklearn: Implementation of machine learning algorithms.

## Data Exploration and Preprocessing:

- Imported the dataset and performed an initial exploration using df.head() and df.info() to understand the data structure.
- Checked for null values and handled them appropriately.
- Dropped irrelevant columns, such as 'Car_Name'.
- Created a new feature, 'No_of_Years', representing the age of the car.
- Converted categorical variables into numerical format using one-hot encoding.
## Feature Importance:

- Determined feature importance using the ExtraTreesRegressor algorithm to identify the most impactful features on selling prices.
- Visualized the top 5 important features through a bar plot.
## Model Training:

- Split the data into training and testing sets using train_test_split.
- Trained two models: Linear Regression and Random Forest Regression.
## Model Evaluation:

- Evaluated models using Mean Squared Error (MSE), Root Mean Squared Error (RMSE), and R-squared (R2) score.
- Visualized predictions with density plots, scatter plots, and line plots.
## Prediction:

- Made predictions using both Linear Regression and Random Forest Regression models.
- Provided a test data point to demonstrate how to predict the selling price of a car.

##  Exploratory Data Analysis  
- Analyzed fuel type, transmission, and price distributions.  
- Compared selling price vs. present price.  
- Visualized key relationships using **Matplotlib** and **Seaborn**.  

  

