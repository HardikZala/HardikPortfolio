# HardikPortfolio

remote_theme: pages-themes/leap-day@v0.2.0
plugins:
- jekyll-remote-theme

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
      
![Marketing_Campaign_images](https://user-images.githubusercontent.com/97468134/200138621-0a837fc5-16ae-44f9-966c-19a2e01d4b30.jpg)

[Seattle House Prices Prediction](https://github.com/HardikZala/Data-Analysis/blob/main/Model_Testing_and_Refinement.ipynb)
* Predict Housing prices using a linear regression model, polynomial regression model
* Evaluate the model's parameters using Ridge regression 
Methods used: 
* Data Cleaning: Remove, and replace missing and null values
* Exploratory Data Analysis: 
      * identifying outliers and correlations between data
* Developing the model based on selected features
      * number of floors, waterfront location, latitude, bedrooms etc.
      * was accurately able to predict house prices with 64.7% accuracy


![house_data_images](https://user-images.githubusercontent.com/97468134/200138649-1c1d2305-6104-43b8-8f93-56915640d2ef.png)

[Securities Portfolio Risk Calculator](https://github.com/HardikZala/Data-Analysis/blob/main/Portfolio_Risk_Calculator.ipynb)
* Streamlined access to key financial metrics for financial investors for portfolio optimization through presented metrics for portfolio beta, Capital Asset Pricing Model, Jensen’s Alpha, Portfolio Standard Deviation etc.  
* Ensured consistent data through real time trading data by web scraping (Beautiful Soup) and APIs calls (yahoo finance)
* Allow for user input securities to create a portfolio with stocks, and weights

![portfolio_risk_calculator_images](https://user-images.githubusercontent.com/97468134/200138678-faf7b0eb-d64f-4b48-af29-e905c9ea493a.jpg)
