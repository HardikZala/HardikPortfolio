# HardikPortfolio

[Bank Marketing Data](https://github.com/HardikZala/Data-Analysis/blob/main/Bank_conversion_predictive_model.ipynb) 
* Created a Regression Model to identify customers that are likely to convert
Methods used:
* Performing Exploratory Data Analysis to identify null values, data redundancies, outliers
    * Identify use cases of machine learning models
* Preprocessing of features to align with Logistic Regression Guidelines
  * normalization of continuous features, through log transformation
  * feature standardization
  * creating binary features
  * creating one-hot encoded features
* Creating a Logistic Regression to achieve a 89.4% accuracy
  * Visualizing results using a confusion matrix 

Findings: 
  * highest predictors of customers likely to convert were:
      * Having previously been contacted
      * Retained/returning customers
      * Retired individuals

[Seattle House Prices Prediction]('https://github.com/HardikZala/Data-Analysis/blob/main/Model_Testing_and_Refinement.ipynb')
* Predict Housing prices using a linear regression model, polynomial regression model
* Evaluate the model's parameters using Ridge regression 
Methods used: 
* Data Cleaning: Remove, and replace missing and null values
* Exploratory Data Analysis: 
      * identifying outliers and correlations between data
* Developing the model based on selected features
      * number of floors, waterfront location, latitude, bedrooms etc.
      * was accurately able to predict house prices with 64.7% accuracy
