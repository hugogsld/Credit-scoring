# Final Report: Credit Scoring - Customer Churn Prediction

## Authors
Corve, Gesland, Sibieude

## Business Case & Problem
Société Générale faces a rising customer churn rate, threatening its revenue and market position, especially against competitors like BNP Paribas and Crédit Agricole. By identifying at-risk customers, the bank can implement proactive retention strategies, such as offering personalized services, to reduce churn and optimize resource allocation.

## Objectives
- **Anticipate churn**: Predict customers likely to leave.
- **Optimize retention**: Focus resources on retaining high-value customers.
- **Enhance customer experience**: Design data-driven strategies to improve satisfaction and loyalty.

## Exploratory Data Analysis (EDA)
The dataset underwent detailed analysis:
- **One-Hot Encoding** of categorical variables.
- **Correlation Analysis** to identify key relationships between features and the target variable.
- Insights show factors like inactivity and balance are highly correlated with churn.

## Data Preprocessing & Feature Engineering
- **Missing values** were handled using imputation (mean for numerical, most frequent for categorical).
- **Outliers** were removed using domain knowledge and Z-score filtering.
- **Feature scaling** applied to numerical features (StandardScaler).

## Model Strategy
Several models were tested to predict churn:
1. Logistic Regression
2. Decision Tree Classifier
3. Random Forest Classifier
4. Gradient Boosting Classifier
5. Support Vector Machine (SVM)
6. k-Nearest Neighbors (k-NN)

## Model Evaluation
Models were evaluated using metrics such as:
- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**
- **AUC (Area Under the Curve)**

## Best Model Selection: Gradient Boosting
Gradient Boosting was chosen as the best model due to its superior performance:
- **Accuracy**: 95.34%
- **F1-Score**: 97.10%
- **AUC**: 0.878

The model showed the best balance of precision and recall, making it ideal for churn prediction. Hyperparameter optimization (learning_rate=0.2, max_depth=4, n_estimators=200) enhanced its performance further.

## Conclusion
This predictive model allows Société Générale to anticipate churn, optimize retention strategies, and improve customer experience, ultimately ensuring a competitive edge in the banking sector.

## Appendix: Retention Strategy Plan
A comprehensive retention strategy focusing on personalized services, exclusive benefits, and proactive interventions based on churn risk predictions will be essential for reducing customer attrition.
