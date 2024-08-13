# Data-Mining-Project
Data Mining Project for INFO-523
# Telecom Customer Churn Analysis Using XGBoost

### Background
This presentation explores the application of the XGBoost algorithm in the context of Telecom customer churn analysis. XGBoost, or eXtreme Gradient Boosting, is an advanced machine learning algorithm that falls under ensemble learning. It is known for its efficiency and scalability, making it an ideal choice for analyzing large datasets in both regression and classification tasks.

### Relation to INFO 523 Topics
The project closely relates to topics covered in INFO 523, such as supervised learning, ensemble learning techniques, and data preprocessing. XGBoost exemplifies the practical application of these concepts, particularly in handling real-world datasets with missing values, feature scaling, and cross-validation methods. The use of XGBoost in this project builds on the principles of data mining, demonstrating the effectiveness of gradient boosting in improving model performance.

### Real-World Applications
XGBoost has significant real-world applications, particularly in industries where large datasets are common. In this case study, XGBoost is applied to a Telecom customer churn dataset to predict which customers are likely to leave the service. The model’s ability to handle missing data, perform feature importance analysis, and improve prediction accuracy makes it a valuable tool in customer retention strategies and decision-making processes.

### Worked Example
The project includes a detailed implementation of the XGBoost algorithm on the Telecom customer churn dataset. The process involves several key steps:
- **Data Preprocessing:** Handling missing data, performing one-hot encoding, removing collinearity, and scaling features.
- **Model Training:** Using cross-validation to train the model and prevent overfitting.
- **Evaluation:** Comparing the XGBoost model’s performance with other algorithms, demonstrating a significant increase in accuracy and F1 score.
- **Feature Importance Analysis:** Utilizing SHAP values to identify the most important features influencing customer churn, such as seconds of use, call failures, and customer complaints.

### Results
The analysis of the Telecom customer churn dataset using XGBoost yielded several key insights:

- **Improvement in Model Performance:** The XGBoost algorithm significantly improved the prediction accuracy for customer churn. Specifically, there was a **7.5% increase in the accuracy score** and a **45% increase in the F1 score** compared to traditional models like Logistic Regression.

- **ROC Curve Analysis:** The ROC curve comparison between Logistic Regression and XGBoost demonstrated a substantial improvement in the Area Under the Curve (AUC), increasing from 0.722 to 0.921. This highlights XGBoost's superior ability to distinguish between churned and non-churned customers.

- **Feature Importance:** The SHAP analysis revealed critical factors contributing to customer churn. Customers with lower usage (seconds of use), those who experienced call failures, and those who lodged complaints were more likely to churn. Additionally, customers with shorter subscription lengths and inactive status showed a higher likelihood of leaving the service.

- **Customer Demographics:** The dataset showed an imbalance across different customer demographics, with middle-aged customers (20-49 years) forming the majority. The churn rate was particularly high among inactive customers and those who had raised complaints.

- **Churn Distribution:** The analysis confirmed that churn is not evenly distributed across all customer segments. Certain groups, such as those with less usage or complaints, are at a higher risk, providing valuable insights for targeted retention strategies.

### Conclusions
XGBoost proves to be a powerful and versatile machine learning algorithm, particularly suited for complex data analysis tasks. Its ability to efficiently handle large datasets, coupled with features like regularization, sparsity awareness, and parallel processing, makes it an essential tool for data scientists. In the context of this project, XGBoost significantly improves the accuracy and reliability of churn predictions, offering valuable insights that can inform customer retention strategies.
