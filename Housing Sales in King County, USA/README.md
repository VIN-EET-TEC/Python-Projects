
# House Sales in King County, USA

## Objective

In this project, I had determined the market price of a house, Analyzed & Predicted housing prices using attributes or features such as square footage, number of bedrooms, number of floors, and so on.
 
### Dataset

This dataset contains house sale prices for King County, which includes Seattle. It includes homes sold between May 2014 and May 2015. It was taken from [here](https://www.kaggle.com/harlfoxem/housesalesprediction?utm_medium=Exinfluencer&utm_source=Exinfluencer&utm_content=000026UJ&utm_term=10006555&utm_id=NA-SkillsNetwork-wwwcourseraorg-SkillsNetworkCoursesIBMDeveloperSkillsNetworkDA0101ENSkillsNetwork20235326-2022-01-01). It was also slightly modified for the purposes of this course.

## Table of Content

- Importing Data
- Data Wrangling
- Exploratory Data Analysis
- Model Development
- Model Evaluation and Refinement

## FAQ 

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

## Author
- **Email**: vineetgupta798@gmail.com
- **LinkedIn**: [vineet-gupta-01b317231](https://www.linkedin.com/in/vineet-gupta-01b317231/)

