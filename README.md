The idea of the analysis is to check whether classification algorithms could be useful in FW20 futures price predictions.
Algorithms used in the analysis:
- Logistic Regression
- Support Vector Classifier
- K-Nearest Neighbors
- Random Forest Classifier
- Ada Boost Classifier (with Decision Trees)
- Voting Classifier

Dependent variable:
- Price change in the current day (D) - from open to close (0 for downtrend, 1 for uptrend)

Predictors:
- Rate of return (%) in the previous day (D-1),
- Change in volume (%) in the previous day (D-1),
- Change in open interest (%) in the previous day (D-1).