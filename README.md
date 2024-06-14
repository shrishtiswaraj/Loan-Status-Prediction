# Loan-Status-Prediction
**California Housing Prices Prediction with XGBoost**

This project explores the use of XGBoost regressor to predict median house prices in California districts based on publicly available data. The data is retrieved from scikit-learn's `fetch_california_housing` function.

**Dependencies**

* pandas
* numpy
* matplotlib.pyplot
* seaborn
* scikit-learn (including XGBRegressor, train_test_split, metrics)

**Running the Script**

1. Install the required libraries using pip:

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
   ```

2. Clone or download this repository.

3. Open a terminal or command prompt and navigate to the project directory.

4. Run the script using:

   ```bash
   python california_housing_prices.py  # Replace with your script name
   ```

**Understanding the Script**

1. **Imports:** Imports necessary libraries for data manipulation, model building, and evaluation.

2. **Data Loading and Exploration:**
   - Loads the California Housing dataset using `fetch_california_housing` from scikit-learn.
   - Explores the data by printing basic statistics and creating a pandas DataFrame.

3. **Data Cleaning and Preprocessing:**
   - Checks for missing values and handles them if necessary (not shown in this example).

4. **Feature Selection:**
   - Selects relevant features from the DataFrame (not shown in this example).

5. **Train-Test Split:**
   - Splits the data into training and testing sets using `train_test_split` from scikit-learn.

6. **Model Training:**
   - Creates an XGBoost regressor object.
   - Trains the model on the training data.

7. **Model Evaluation:**
   - Evaluates the model's performance on both training and testing data using R-squared and Mean Absolute Error (MAE).
   - Visualizes the predicted prices vs actual prices using a scatter plot.

**Results**

The script reports the R-squared and Mean Absolute Error for both the training and testing data. Lower values of MAE indicate a better model fit.

**Additional Notes**

- The script includes comments and explanations throughout the code for better understanding.
- This example focuses on XGBoost regression, but other algorithms can be explored for comparison.
- Fine-tuning hyperparameters of the XGBoost model can potentially improve performance.

I hope this README file provides a clear overview of the project!
