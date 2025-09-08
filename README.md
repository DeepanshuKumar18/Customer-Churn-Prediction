# Customer-Churn-Prediction
## Objective
Predict which customers are likely to churn so the company can take proactive retention actions.

##  1. Data Collection

Begin by gathering relevant data, which may include:

* **Customer Demographics**: Age, gender, location, etc.
* **Account Information**: Tenure, plan type, payment method.
* **Usage Patterns**: Call duration, data usage, SMS count.
* **Customer Support Interactions**: Number of support tickets, resolution time.
* **Device Information**: Model, OS version, etc.

---

##  2. Data Preprocessing

Prepare the data for modeling:

* **Handle Missing Values**: Use imputation techniques or remove records with missing critical information.
* **Encode Categorical Variables**: Apply techniques like One-Hot Encoding or Label Encoding.
* **Feature Scaling**: Normalize or standardize numerical features to bring them to a common scale.
* **Feature Engineering**: Create new features that might help in prediction, such as 'Average Monthly Spend'.

---

##  3. Model Selection

Choose appropriate machine learning models:
* **Random Forest**: Handles non-linear relationships and provides feature importance.
---

##  4. Model Training & Evaluation

* **Split the Data**: Use a training set (e.g., 80%) and a test set (e.g., 20%).
* **Evaluation Metrics**:

  * **Accuracy**: Percentage of correctly classified instances.
  * **Precision & Recall**: Especially important in imbalanced datasets.
  * **F1-Score**: Harmonic mean of precision and recall.
  * **ROC-AUC**: Measures the trade-off between true positive rate and false positive rate.

---

##  5. Model Interpretation

* **Feature Importance**: Identify which features are most influential in predicting churn.
* **Partial Dependence Plots**: Visualize the relationship between a feature and the predicted outcome.
* **SHAP Values**: Provide insights into how each feature value contributes to the prediction.

---
## Tools & Technologies
- **Python**: `pandas`, `numpy`, `scikit-learn`, `Random Forest`, `matplotlib`, `seaborn`, `joblib`  
- **Dashboard **: **Power BI** (interactive visualization of predictions and key metrics)  
- **IDE**: Jupyter Notebook  

