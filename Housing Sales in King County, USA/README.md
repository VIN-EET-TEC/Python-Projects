# House Sales in King County, USA

## Overview

This repository contains a Jupyter Notebook that analyzes housing sales data in King County, USA. The dataset includes various attributes of houses sold in the region, such as price, number of bedrooms, number of bathrooms, square footage, and more. The analysis provides insights into housing trends and factors affecting property prices.
 
## Objective

- Importing Data
- Data Wrangling
- Exploratory Data Analysis
- Model Development
- Model Evaluation and Refinement

## Tools & Techniques

- **Pandas :** Data manipulation and analysis
- **NumPy :** Numerical computations
- **Matplotlib :** Data visualization
- **Seaborn :** Advanced statistical visualization
- **Scikit-learn :** Machine learning for predictive modeling
- **Jupyter Notebook :** Interactive code execution

## Q&A 

**Question1 :** Display the data types of each column using the function dtypes.

**Question2 :** Drop the columns *"id"* & *"Unnamed: 0"* from axis 1 using the method **drop()**, then use the method **describe()** to obtain a statistical summary of the data. Make sure the *"inplace"* parameter is set to *True*. 

**Question3 :** Use the method **value_counts** to count the number of houses with unique floor values, use the method **.to_frame()** to convert it to a data frame. 

**Question4 :** Use the function **boxplot** in the seaborn library to determine whether houses with a waterfront view or without a waterfront view have more price outliers. 

**Question5 :** Use the function **regplot** in the seaborn library to determine if the feature *"sqft_above"* is negatively or positively correlated with price.

**Question6 :** Fit a linear regression model to predict the *"price"* using the feature *"sqft_living"* then calculate the R^2.

**Question7 :** Fit a linear regression model to predict the *"price"* using the list of features:

**Question 8 :** Use the list to create a pipeline object to predict the *"price"*, fit the object using the features in the list *"features"*, and calculate the R^2.

**Question 9 :** Create and fit a Ridge regression object using the training data, set the regularization parameter to 0.1, and calculate the R^2 using the test data.

**Question 10 :** Perform a second order polynomial transform on both the training data and testing data. Create and fit a Ridge regression object using the training data, set the regularisation parameter to 0.1, and calculate the R^2 utilising the test data provided.

## Result & Impact

- **Data Cleaning :** Improved dataset quality for accurate analysis
- **EDA :** Identification of trends and patterns in housing sales
- **Visualization :** Clear and insightful charts for better understanding
- **Predictive Modeling :** Potential for price prediction based on features

### Dataset

The dataset used in this project is Housing_Sales_in_King_Count_USA.csv, which contains:

- House ID
- Date of sale
- Price
- Number of bedrooms and bathrooms
- Square footage of living area and lot
- Location details (zipcode, latitude, longitude)
- Condition and grade of the house

## Author
- **Email**: vineetgupta798@gmail.com
- **LinkedIn**: [vineet-gupta-01b317231](https://www.linkedin.com/in/vineet-gupta-01b317231/)
