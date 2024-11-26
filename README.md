# Linear Regression Analysis: Predicting Crop Yields

This project explores the use of linear regression to model and predict crop yields based on environmental factors like pollution and temperature. The dataset, derived from agricultural surveys, includes features such as pollution level, average temperature, and soil characteristics. Through this analysis, we evaluate the effectiveness of linear regression, perform residual diagnostics, and assess the model's predictive power.

## **Project Overview**

### **Key Objectives**
- Investigate relationships between environmental factors and standardized crop yield (`Standard_yield`).
- Evaluate the linear regression model using metrics such as R-squared, MAE, MSE, and RMSE.
- Conduct residual diagnostics to assess assumptions like normality, linearity, and homoscedasticity.
- Discuss implications for model reliability and areas for improvement.

### **Key Insights**
1. **Model Fit**:
   - Pollution level (`Pollution_level`) showed a moderate negative relationship with `Standard_yield` (R-squared ≈ 0.081).
   - Residual analysis revealed potential issues with heteroscedasticity and outliers, suggesting the need for more complex models.

2. **Evaluation Metrics**:
   - R-squared: ~8.1% of the variance in `Standard_yield` is explained by pollution level.
   - Mean Absolute Error (MAE): ~0.0879.
   - Root Mean Squared Error (RMSE): ~0.1107.

3. **Residual Analysis**:
   - The residuals were approximately normally distributed, centered around zero.
   - A scatter plot of residuals vs. predictions highlighted heteroscedasticity, suggesting a non-constant variance of errors.

## **Getting Started**

### **Requirements**
Ensure you have Python installed with the following packages:
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

Install all dependencies with:
```bash
pip install -r requirements.txt
