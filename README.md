# Linear-Regression-Based-Happiness-Prediction
This Python script utilizes linear regression to predict happiness based on income data. The linear regression model is trained on sample income and happiness data, and then used to make predictions for new income values.

Features:

1-Sample Data:

Includes sample income and happiness data for demonstration purposes.

2-Linear Regression Modeling:

Utilizes the LinearRegression model from sklearn to create a linear regression model.
Fits the model to the provided income and happiness data.

3-Prediction and Visualization:

Predicts happiness values based on the trained linear regression model.
Plots the original data points and the regression line for visual representation.

4-Regression Output:

Prints the coefficients (slope and intercept) of the linear regression model.
Displays the R-squared value, indicating the goodness of fit.

5-Example Prediction:

Includes an example of predicting happiness for a specified income value.
Example Usage:
![visuals](https://github.com/DaliaRefaat/Linear-Regression-Based-Happiness-Prediction/assets/125277143/602c931b-96e3-4acd-804a-16649491c48b)

# Example Prediction
new_income = np.array([[30]])  # Replace with your income value
predicted_happiness = regressor.predict(new_income)
print(f"Predicted Happiness for $30,000 income: {predicted_happiness[0]}")

Dependencies:
numpy
matplotlib
scikit-learn

How to Run:
Ensure dependencies are installed (pip install numpy matplotlib scikit-learn).
Replace the sample income and happiness data with your own.
Run the script to visualize the regression line and make predictions.

Note:
This script provides a simple demonstration of using linear regression for predicting happiness based on income. Users can adapt and extend the code for more complex modeling, feature engineering, and analysis of the relationship between income and happiness. Feel free to explore, modify, and contribute to enhance the functionality and usability of this linear regression-based happiness prediction tool!
