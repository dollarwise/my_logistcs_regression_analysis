# Logistic Regression – Airline Customer Satisfaction Prediction

## Dataset
Invistico Airline Customer Satisfaction Dataset

## Objective
Predict whether a passenger is satisfied or dissatisfied using airline service and customer attributes.

## Modeling Approach
1. Data inspection and cleaning
2. Missing-value imputation
3. One-hot encoding of categorical variables
4. Standardization of numeric variables
5. Train/Test split (80/20)
6. Logistic Regression classification model

## Performance Metrics

Confusion Matrix

[[9544, 2215],
 [2233, 11984]]

Accuracy: 82.88%
Precision: 84.40%
Recall: 84.29%

## Key Drivers of Satisfaction

Positive:
- Inflight entertainment
- Seat comfort
- On-board service
- Check-in service
- Ease of online booking
- Loyal customer status

Negative:
- Disloyal customer status
- Personal travel
- Economy-class travel

## Business Recommendations

- Improve inflight entertainment and Wi‑Fi quality.
- Enhance economy-class experience.
- Strengthen loyalty programs.
- Improve online booking and support channels.
- Focus on retaining high-value business travelers.

## Limitations

- Logistic Regression linearity assumptions.
- Possible omitted variables.
- Additional models should be benchmarked for production deployment.
