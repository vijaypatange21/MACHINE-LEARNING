# Yearly Amount Spent Prediction

This project predicts the yearly amount spent by e-commerce customers using both Linear Regression and a Neural Network (TensorFlow/Keras). The workflow includes data exploration, visualization, outlier detection, and model evaluation.

## Dataset

- **Source:** `Ecommerce Customers` (CSV file)
- **Features Used:**
  - Avg. Session Length
  - Time on App
  - Time on Website
  - Length of Membership

## Workflow

1. **Exploratory Data Analysis (EDA):**
   - Data inspection (`head`, `info`, `describe`)
   - Visualizations: pairplots, boxplots, heatmaps
   - Outlier detection using IQR

2. **Feature Selection:**
   - Selected numerical features for modeling

3. **Modeling:**
   - **Linear Regression:** Using scikit-learn
   - **Neural Network:** Using TensorFlow/Keras (with feature scaling)

4. **Evaluation Metrics:**
   - Mean Absolute Error (MAE)
   - Mean Squared Error (MSE)
   - Root Mean Squared Error (RMSE)
   - R-squared Score (R², used as "accuracy" for regression)

5. **Visualization:**
   - Scatter plots of predictions vs. actuals
   - Residual analysis

## How to Run

1. Install dependencies:
    ```bash
    pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
    ```

2. Place the `Ecommerce Customers` CSV file in the project directory.

3. Open and run the notebook:  
    `yearly_analysis_prediction.ipynb`

## Results

- Both models are evaluated using R² and error metrics.
- Neural Network R² Score is printed as a measure of regression "accuracy".

## License

This project is for educational
