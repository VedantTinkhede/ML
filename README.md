# ML
## 🧠 Definition
**Linear Regression** is a **supervised learning** algorithm used for predicting **continuous values** by modeling the relationship between a **dependent variable** and one or more **independent variables** using a **linear equation**.



## 🔢 Types

### 📈 Simple Linear Regression
\[
y = w_0 + w_1x + \epsilon
\]

### 📊 Multiple Linear Regression
\[
y = w_0 + w_1x_1 + w_2x_2 + \dots + w_nx_n + \epsilon
\]



## 📌 Assumptions
- Linearity
- Independence of observations
- Homoscedasticity (constant variance of errors)
- Normally distributed residuals
- No multicollinearity among features



## 🎯 Objective

Minimize the **Mean Squared Error (MSE)**:
\[
\text{MSE} = \frac{1}{n} \sum_{i=1}^{n} (y_i - \hat{y}_i)^2
\]



## ⚙️ Optimization – Gradient Descent

**Update rule**:
\[
w_j := w_j - \alpha \cdot \frac{\partial J(w)}{\partial w_j}
\]

Where:
- \( \alpha \) = Learning Rate

**Variants**:
- Batch Gradient Descent
- Stochastic Gradient Descent (SGD)
- Mini-batch Gradient Descent



## 📏 Evaluation Metrics

| Metric | Description                |
|--|-|
| MSE    | Mean Squared Error         |
| RMSE   | Root Mean Squared Error    |
| MAE    | Mean Absolute Error        |
| \( R^2 \) Score | Coefficient of determination (max = 1) |



## ✅ Advantages
- Easy to implement & interpret
- Fast & efficient for small-to-medium datasets
- Works well when the relationship is linear





## ⚠️ Limitations
- Not suitable for non-linear relationships
- Sensitive to outliers
- Poor performance with multicollinearity
