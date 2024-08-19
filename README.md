# CODTECH-Task2

Name:LEKSHMI SARMA

Company:CODTECH IT SOLUTIONS

ID:CT08DS5397

Domain:Data Analytics

Duration:July to August 2024

Mentor:Muzammil Ahmed

# Overview of the Project

## Project:SuperMart Sales Prediction with Linear Regression

### Objective
The objective of this project is to implement linear regression model on a dataset containing the sales data of supermart. The aim is to split the data into training and testing sets, train the model on the training data, evaluate its performance using metrics like mean squared error or R-squared and make predictions on the test set. Also to visualize the regression line and actual vs predicted values to access the model's accuracy.

### Key Activities

- Collect and Prepare data:Historical Sales Data collection and Identify potential predictor variables that could influence sales.
- Data Cleaning:Ensuring the dataset is free from inconsistencies and missing values.
* Data Visualization:Creating visualizations to understand data distributions, trends and relationships.
+ Correlation Analysis:Identifying correlations to understand how predictor variables relate to sales.
+ Create Features:Convert categorical variables into numerical format
+ Build the Linear Regression Model:Dividing the data into training and testing sets and use the training data to train the linear regression model.
+ Model Evaluation:Evaluate the model's performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), or R-squared.
+ Make Predictions:Use the trained model to make future sales predictions based on new input data.

### Technologies Used

- Python: The primary programming language for data analytics.
- Pandas: Used for data manipulation and analysis.
- Numpy: Used for data manipulation and analysis.
- scikit-learn: For linear regression, data splitting, and model evaluation.
- Matplotlib: Used for data viualizations.
- Seaborn: Used for statistical data viualizations.
- Google Collab: For interactive coding and visualization in Python


### Analysis 

1. Mean Squared Error (MSE) is 1577094.25 suggests that the squared differences between predictions and actual values are relatively large.
2. Root Mean Squared Error (RMSE) is 1255.82 means that, on average, the predictions deviate from the actual values by about 1,255.82 units.
3. Mean Absolute Error (MAE) is 944.87 indicates that, on average, the predictions are off by 944.87 units.
4. R-squared (R²) is 0.4891 means that approximately 48.91% of the variance in the target variable (sales) is explained by the model.
5. The points in the Scatter plots are closely scattered around the red dashed line, indicates that the model's predictions are close to the actual sales values.
6. Residuals are randomly scattered around the horizontal axis (residual = 0).
7. The histogram of Residuals is a normal distribution, indicates a well-performing model.
8. Item_Visibility and Outlet_Type have strong effects.

### Conclusion

The linear regression model has an R-squared value of 0.4891, indicating moderate explanatory power. RMSE gives a more interpretable error measure compared to MSE because it is in the same units as the target variable. MAE is less sensitive to outliers than MSE and RMSE and provides a straightforward measure of prediction accuracy.The RMSE and MAE suggest that while the model provides predictions with a certain level of accuracy, there is room for improvement. By refining features, experimenting with different models, and addressing potential issues, the model’s predictive performance can be enhanced. The points in the plot indicate that the model's predictions are close to the actual sales values, which suggests good model performance.



