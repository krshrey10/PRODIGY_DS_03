# PRODIGY_DS_03
Building a Decision Tree Classifier for Customer Purchase Prediction.

# Key Findings and Recommendations
## Important Features:

Duration of last contact (most important)
1. Number of contacts performed.
2. Employment variation rate.
3. Consumer price index.
4. Euribor 3 month rate.

## Decision Patterns:

1. Customers with longer call durations (>5 minutes) are more likely to subscribe.
2. Campaigns perform better when fewer contacts have been made in this campaign.
3. Certain months (like March, September, October) show higher conversion rates.

## Business Recommendations:

1. Focus on quality interactions (longer duration calls convert better).
2. Limit number of contacts per campaign to avoid customer fatigue.
3. Time marketing campaigns for months with historically better performance.
4. Pay attention to macroeconomic indicators (euribor rates, employment).

# How to Improve the Model

## Handling Class Imbalance:

1. The dataset has about 11:1 ratio of no:yes.
2. Consider using SMOTE or other oversampling techniques.

## Feature Engineering:

1. Create interaction terms between important features.
2. Bin continuous variables where appropriate.

## Hyperparameter Tuning:

1.Use GridSearchCV to find optimal tree parameters.
2.Experiment with different max_depth and min_samples_split values.

## Alternative Models:

1.Try Random Forest or Gradient Boosting for comparison
2.Consider neural networks if data is sufficient

This implementation provides a complete pipeline from data loading to model interpretation, with a focus on business-relevant insights from the decision tree model.
