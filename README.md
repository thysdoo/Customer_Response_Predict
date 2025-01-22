# Customer_Response_Predict


**Objective**: Predict customer responses to marketing calls based on the provided "Marketing-Customer-Value-Analysis" dataset.

**Contributions**:
- Exploratory Data Analysis (EDA):
Utilized the following libraries for EDA: Pandas, NumPy, Matplotlib, Seaborn, and Scikit-learn.
Explored the relationships between continuous variables (Income, Customer Lifetime Value, Total Claim Amount) and the target variable (Response) using visualizations such as box plots, scatter plots, and pair plots.
Leveraged Scikit-learn for statistical tests and feature selection techniques to identify significant predictors.
Analyzed categorical variables (Education, Policy Type, Renew Offer Type) with respect to the target variable using bar plots and count plots.
Examined correlations between numerical features using a heatmap to guide feature selection.
- Data Preprocessing:
Cleaned and transformed the dataset by:
Handling missing values.
Encoding categorical variables using one-hot and label encoding.
Addressed class imbalance in the Response variable using resampling techniques.
Selected relevant features based on EDA findings and statistical significance.
- Model Building and Comparison:

Implemented and trained three classification models: Logistic Regression, Boosted Tree, and Random Forest.
Compared the models based on evaluation metrics such as accuracy, precision, recall, F1-score, and AUC-ROC.
Determined that Boosted Tree achieved the best performance with an AUC score of 0.88, followed by Random Forest (AUC 0.85) and Logistic Regression (AUC 0.80).
- Evaluation and Insights:

Highlighted key factors influencing customer responses, such as Income, Renew Offer Type, and Policy Type.
Provided actionable recommendations to optimize marketing strategies by targeting specific customer segments.
- Visualization and Reporting:

Developed detailed visualizations in Jupyter Notebook to showcase model performance, feature importance, and customer response trends.
Presented findings in a comprehensive report with actionable insights for stakeholders.
**Tools Used**:

Python (Jupyter Notebook),
Machine Learning (Logistic regression, Boosted Tree, Random Forest)



