# Customer_Retention_System
Overview:
The Integrated Customer Retention System is a comprehensive machine learning-powered solution aimed at improving customer loyalty and reducing churn by combining Customer Segmentation, Churn Prediction, and Recommendation Systems into a unified framework. 

 Features:
 
- Customer Segmentation using clustering algorithms (KMeans, Hierarchical, KPrototypes)
- Churn Prediction using machine learning models (Random Forest, XGBoost, LightGBM)
- Recommendation System using collaborative filtering and KNN for high-risk customers
- Visualizations for cluster insights, ROC curves, and feature importance
- Explainability using SHAP for churn predictions
- End-to-end interactive UI built with Streamlit

 Modules:
 
1. Customer Segmentation:

- Upload customer dataset via a Streamlit UI
- Handle missing values with flexible options
- Auto-select clustering algorithm (KMeans, KModes, KPrototypes)
- Visualize clusters in 2D/3D
- Export results for further use

2. Churn Prediction
- Train models with SMOTE to handle class imbalance
- Choose from top ML classifiers (RF, XGBoost, LightGBM)
- Analyze prediction metrics: Accuracy, ROC-AUC, Confusion Matrix
- Export model and churn-labeled dataset
- Explain model predictions using SHAP

3. Recommendation System
- Identify high-churn-risk customers via threshold
- Generate personalized recommendations using KNN
- Reference similar loyal customers for retention insights
- Export actionable strategies for marketing or CRM integration

| Component         | Technology                      |
| ----------------- | ------------------------------- |
| Data Manipulation | Pandas, NumPy                   |
| ML Modeling       | Scikit-learn, XGBoost, LightGBM |
| Visualization     | Matplotlib, Seaborn, Plotly     |
| UI Framework      | Streamlit                       |
| Explainability    | SHAP                            |
| Clustering        | KMeans, KModes, KPrototypes     |
| Deployment        | Local/Streamlit App             |

 Results:
- 93% accuracy and 0.97 ROC-AUC in churn prediction
-  Clear cluster formation for customer segments
-  Personalized, behavior-based product recommendations for high-risk customers

 Use Cases:
- E-commerce (cart abandonment, product recommendations)
- Telecom (predicting customer drop-offs)
- SaaS platforms (subscription retention)
- Banking (account closure prediction)
