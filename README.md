# Predictive Maintenance with Machine Learning

Most industrial machines such as milling and CNC equipment have certain lifespans before breaking down. The reasons for the breakdown can range from various problems such as heat and mechanical stress/overload. A predictive maintenance model will help determine when a machine is nearing its lifespan or is prone to damage based on specific performance metrics and can be called in early for maintenance. This avoids machine break downs to reduce repair costs and cuts down on downtimes to maximise asset utilisation.

# Dataset
Source: [AI4I 2020 Predictive Maintenance Dataset](https://archive.ics.uci.edu/dataset/601/ai4i+2020+predictive+maintenance+dataset) (UCI Machine Learning Repository)

# Approach
1. Exploratory data analysis and outlier detection
2. Feature engineering (temperature differential, mechancial power)
3. Class imbalance handling with SMOTE
4. Model comparison: Logistic Regression, Random Forest, Historgram Gradient Boosting
5. Evaluate using precision, recall, F1-score, and ROC-AUC
6. Feature importance analysis with SHAP
