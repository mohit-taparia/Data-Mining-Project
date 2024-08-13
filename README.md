# Data-Mining-Project
Data Mining Project for INFO-523
# Telecom Customer Churn Analysis Using XGBoost

### Background
XGBoost (eXtreme Gradient Boosting),is a powerful and advanced machine learning algorithm. As part of the ensemble learning technique, XGBoost is recognized for its efficiency and scalability, making it an excellent choice for analyzing large datasets in both regression and classification tasks.

### Relation to INFO 523 Topics
XGBoost is closely related to data mining as it is a powerful tool used within the data mining process. It is frequently used to build predictive models for both classification and regression tasks. Additionally, XGBoost helps identify significant features that impact outcomes by providing feature importance scores. It excels in processing complex datasets by handling missing values and noisy data, and is robust to overfitting, which is crucial for creating reliable models. By employing ensemble techniques, specifically gradient boosting, XGBoost aligns with data mining strategies that combine multiple models to enhance performance and accuracy.

### Real-World Applications
XGBoost has significant real-world applications, particularly in the areas of regression and classification. This algorithm could be used in various industries like Finance - Credit Scoring, Healthcare - prediction of disease, Marketing - customer segmentation, Sale Forecasting, Recommendation Systems. In this case study, XGBoost is applied to a Telecom customer churn dataset to predict the customer churn. The model’s ability to handle large dataset and improved model performance makes it a go-to choice for many industries.

### Case Study
The project includes a detailed implementation of the XGBoost algorithm on the Telecom customer churn dataset. The process involves several key steps:
- **Data Preprocessing:** Handling missing data, performing one-hot encoding, removing collinearity, and scaling features.
- **Model Training:** Using cross-validation to train the model and prevent overfitting.
- **Evaluation:** Model performance is evaluated using Logloss metric. Comparing the XGBoost model’s performance with Logistic Regression algorithms, demonstrates a significant increase in accuracy and F1 score through XgBoost.
- **Feature Importance Analysis:** Utilizing SHAP values to identify the most important features influencing customer churn, such as seconds of use, call failures, and customer complaints.

### Results
The analysis of the Telecom customer churn dataset using XGBoost yielded several key insights:

- **Improvement in Model Performance:** The XGBoost algorithm significantly improved the prediction accuracy for customer churn. Specifically, there was a **7.5% increase in the accuracy score** and a **45% increase in the F1 score** compared to traditional models like Logistic Regression.

- **ROC Curve Analysis:** The ROC curve comparison between Logistic Regression and XGBoost demonstrated a substantial improvement in the Area Under the Curve (AUC), increasing from 0.722 to 0.921. This highlights XGBoost's superior ability to distinguish between churned and non-churned customers.

- **Feature Importance:** The SHAP analysis revealed critical factors contributing to customer churn. Customers with lower usage (seconds of use), those who experienced call failures, and those who lodged complaints were more likely to churn. Additionally, customers with shorter subscription lengths and inactive status showed a higher likelihood of leaving the service.

- **Customer Demographics:** The dataset showed an imbalance across different customer demographics, with middle-aged customers (20-49 years) forming the majority. The churn rate was particularly high among inactive customers and those who had raised complaints.

- **Churn Distribution:** The analysis confirmed that churn is not evenly distributed across all customer segments. Certain groups, such as those with less usage or complaints, are at a higher risk, providing valuable insights for targeted retention strategies.

### Conclusion
The algorithm found various key relationships and patterns in the Case Study. In conclusion, XGBoost proves to be a powerful and versatile machine learning algorithm, particularly suited for complex data analysis tasks. Its ability to efficiently handle large datasets, coupled with features like regularization, sparsity awareness, and parallel processing, makes it an essential tool for data scientists. In the context of the project, XGBoost significantly improves the accuracy and reliability of churn predictions, offering valuable insights that can used to suggest customer retention strategies.
