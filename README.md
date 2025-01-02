## Machine-Learning-Assignment-3---Regression
An assignment in Jupyter Notebook covering Regression.

**1. Dataset Selection and Preprocessing**

I worked with the California Housing Dataset from Scikit-learn.

  **Preprocessing steps included:**

  Converting the dataset into a pandas DataFrame for easier handling.

  Scaling the features using StandardScaler to standardize the input values.

  Splitting the dataset into training and testing sets.

**2. Regression Algorithm Implementation**

I implemented the following regression algorithms:

Linear Regression

Decision Tree Regressor

Random Forest Regressor

Gradient Boosting Regressor

Support Vector Regressor (SVR)

  **For each model:**

  Trained it on the training data.

  Predicted the target values on the testing data.

**3. Model Evaluation**

I evaluated the performance of each algorithm using:

**Mean Squared Error (MSE):** Measures the average squared difference between predicted and actual values.

**Mean Absolute Error (MAE):** Measures the average absolute difference between predicted and actual values.

**R² Score:** Measures the proportion of variance explained by the model.

**4. Results and Comparison**

**Best Performing Model: Random Forest Regressor**

Justification: It achieved the highest R² score (0.805) and the lowest MSE (0.2555) and MAE (0.3276), demonstrating its superior ability to predict housing prices.

**Worst Performing Model: Linear Regression**

Justification: It had the lowest R² score (0.576) and the highest error metrics (MSE: 0.5559, MAE: 0.5332), showing its poor fit and prediction accuracy.

**5. Insights and Conclusion**

Non-linear models like Random Forest and Gradient Boosting performed significantly better than Linear Regression, likely because the dataset contains complex relationships that linear models cannot capture.
Feature scaling was crucial for models like SVR, which are sensitive to data magnitude.
