## CO2 Emission Prediction with Multiple Linear Regression

This repository explores the use of multiple linear regression to predict CO2 emissions of vehicles based on engine size, cylinders, and fuel consumption. 

### Project Goals

* Analyze a dataset of vehicle characteristics and CO2 emissions.
* Build a multiple linear regression model to predict CO2 emissions based on the chosen features.
* Evaluate the model's performance using relevant metrics.

### Technologies Used

* Python (libraries: pandas, nympy, scikit-learn, matplotlib)

### Data Analysis (EDA)

* Visualize the relationships between CO2 emissions and the chosen features (engine size, cylinders, fuel consumption) using scatter plots or other techniques.
* Perform descriptive statistics to summarize the data (mean, median, standard deviation, etc.).

### Model Building

1. **Model Training:** Train a multiple linear regression model on the prepared data.
2. **Model Evaluation:** Evaluate the model's performance using metrics like R-squared, Mean Absolute Error (MAE), or others relevant to your goals.

### Results

Root Mean Square of Error (RMSE): 23.87
Variance Score (R²): 0.87
The results indicate that the model is good at predicting with low RMSE and high R2 Score. But still, there's a room for improvement on this model by using feature engineering, or maybe hyperparameter tuning.

### Conclusion

The Multiple Linear Regression model provides a basic approach to predicting CO2 emissions based on engine size, number of cylinders, and fuel consumption. Overall model is good, however there's still a room for improvement

### Future Work

Feature Engineering: Explore additional features that might better explain the variance in CO2 emissions.
Model Complexity: Experiment with more complex models, such as decision trees or ensemble methods.
Hyperparameter Tuning: Optimize the model's hyperparameters to improve performance.
Cross-Validation: Use cross-validation to get a more reliable estimate of the model's performance.
Contributing
Contributions are welcome! Please fork the repository and submit a pull request with your improvements.

License
This project is licensed under the MIT License. See the LICENSE file for details.
