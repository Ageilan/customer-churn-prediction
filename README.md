**Customer Churn Prediction using XGBoost & SHAP**
This project focuses on predicting customer churn for a telecom-based dataset using machine learning.
The model is built using XGBoost, and explainability is achieved through SHAP (SHapley Additive Explanations), making the predictions transparent and interpretable.

**Project Overview**
Customer churn prediction helps businesses identify customers who are likely to leave.

**This project:**
-->Generates/uses a synthetic telecom dataset
-->Trains an XGBoost Classifier
-->Evaluates model performance
-->Explains predictions using SHAP
-->Visualizes key metrics and feature importance

**Model Performance**
| Metric                | Score |
| --------------------- | ----- |
| **Accuracy**          | 0.96  |
| **AUC Score**         | 0.985 |
| **Precision (Churn)** | 0.95  |
| **Recall (Churn)**    | 0.93  |

**Top Factors Influencing Churn**
Based on SHAP values, the following features most strongly influence churn behavior:
1. ContractLength
2. PaymentDelay
3. DeviceProtection
4. DownloadSpeed
5. Tenure
6. InternetUsage
7. UploadSpeed
8. NumServices
9. InternationalCalls
10. StreamingUsage

**Technologies Used**
i. Python
ii. Pandas, NumPy
iii. Scikit-Learn
iv. XGBoost
v. Matplotlib
vi. SHAP

**Conclusion**
This project demonstrates how machine learning can be used to predict customer churn and interpret model decisions using SHAP.
It is ideal for:
1. Academic projects
2. Portfolio building
3. ML explainability showcase
4. Telecom churn analysis
