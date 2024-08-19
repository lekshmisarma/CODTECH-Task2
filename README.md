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
+ Model Improvement:Refine the model by adding more features, adjusting hyperparameters, or using more advanced techniques like polynomial regression if linear regression isn't sufficient.

### Technologies Used

- Python: The primary programming language for data analytics.
- Pandas: Used for data manipulation and analysis.
- Numpy: Used for data manipulation and analysis.
- scikit-learn: For creating new features and preprocessing data.
- Feature-engine: For feature engineering and transformation.
- Matplotlib: Used for data viualizations.
- Seaborn: Used for statistical data viualizations.
- XGBoost Regressor: to build robust predictive models.
- Google Collab: For interactive coding and visualization in Python


### Analysis andConclusion

The R-squared values of train data is 0.636 and that of test data is 0.587. The drop in R-squared from training to test data indicates a reduction in predictive performance when applied to new data.The R-squared values of 0.636 and 0.587 on training and test data, respectively, suggest that while the model explains a decent proportion of the variance in the data, there is a notable drop in performance on new data. This can be an indication of overfitting or other issues in model generalization. To address this, consider using cross-validation, applying regularization techniques, and performing thorough model diagnostics to improve and validate your model's performance.
