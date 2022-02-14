# 
# Predict assessed property value  for the purpose of property tax assessment

### Business Problem

Property tax assessment method is one of the most important issues that has been discussed in the industry for many years.

In most areas, assessments are based on some related data that was acquired through an official survey or real estate market and provided by a public entity.

The data is then analyzed by statistical or mathematical methods to estimate the values and has many problems such as instability, inefficiency and difficulty in using.

The assessment of a property's value is a complicated process that involves a number of elements, including the size and location of the property, what type of improvements have been made to it, and similar properties in the area. Whether you're selling or buying property, understanding how assessments work will help you get the best deal possible on your new home. Some municipalities base their assessments on three different types of values: Going Concern Value (GCV), Replacement Cost New (RCN) and Sales Comparison Value (SCV). 

### Possible solution

The effective method to solve this problem is machine learning method.In the real estate market, the most important thing is price, which is indicative of commodity price, so if you can estimate it well, you can do good business. In this industry, technology has a great impact on how to accurately forecast the assessment of property value, and the use of AI and data mining technology to predict property price will be more practical in the future.Modern technology makes it possible to automate much of this process via machine learning algorithms that take into account many variables including nearby sale prices, lot size, zoning restrictions etc.


**1. How to calculate an accurate property assessment?**

One of the most important issues for every country is how best to determine a property's tax assessment value in order to ensure that property taxes are paid in full and properly assessed amounts are collected. In the United States, property taxes are based on a system of assessments, which will provide you with the property tax amount.

**2. What is the right machine learning model for calculating a property assessment?**

The right machine learning model for calculating an accurate property assessment can be determined through data analysis and evaluation techniques. For example, in order to accurately define property value as "intrinsically accurate", it must be able to capture all of the relevant aspects of the asset and then use this information to calculate its value. During this process, it is also important that all properties in your data set have equal treatment in the algorithm's design and cannot lock any data categories into a particular category that may lead to bias in your results.

**3. How can we use machine learning to estimate a property assessment value?**

In order to accurately estimate a property assessment value, a separate model is required that matches your data set as much as possible. The artificial neural network algorithm has been frequently used for this purpose. This model is designed for any type of input data, regardless of its source, and will connect the attributes of each piece of information and provide insight into the relationship between each variable in the group. For this reason, it is also useful as an analysis method that can be used when determining whether or not a particular algorithm will be effective in your particular case.

**4. Is there any other way to calculate a property's assessment value?**

Although, it may be difficult to accurately estimate the property tax value when using a regular regression model, there are still other ways that you can use to determine this value. For instance, one way to use regression models is to analyze the properties with similar characteristics and data sets and find a mathematical relationship between them. By calculating the coefficients for each tie between similar properties and then comparing these values, you can find out if your assessment is higher or lower than expected. In this case, you should also meet a property value for the best example of your area.

**Tech stack**

- Language - Python

- Libraries - Scikit-learn, pandas, numpy, matplotlib, seaborn, scipy, xgboost, joblib,Autoviml,MLjar
 
**Approach**

- Importing the required libraries and reading the dataset.
- Understanding the dataset
- Exploratory Data Analysis (EDA) 
- Data Visualization
- Feature Engineering
- Duplicate value removal
- Missing value imputation
- Standardization
- Encoding of categorical variables
- Generation of new feature wherever required.
- Dropping of redundant feature columns
- Checking for multi-collinearity and removal of highly correlated features
- Check for the outliners and removal of outliers.
 

**Model Building**

- Performing train test split
- Feature Scaling
- Dropping features if necessary
- Linear Regression Model
- Elastic Net
- Ridge Regression
- Lasso Regressor
- XGBoost Regressor
- Adaboost Regressor
- Gradient Boosting Regressor
- Decision Tree Regressor
- Random Forest Regressor
- Model Validation
   - Mean Absolute Percentage Error(MAPE)
- Hypermeter Tuning (GridSearchCV)
   - For Random Forest Regressor
- Checking for Feature Importance
- Creating the final model and making predictions

**Model Building(AutoML)**

- Feature Engineering on Full Data Set
- Preparing Data for Submission File
- Autoviml(AutoML Library Used for Modelling)
- Mljar(AutoML library used for Modelling ,Compete Mode)
- Submission

### Data sources
- [Building Classes - NYC](https://www.propertyshark.com/mason/text/nyc_building_class.html)
- [Property Tax Calculator](https://smartasset.com/taxes/new-york-property-tax-calculator)

