# Fraud Detection with XGBoost

## Data Cleaning

- **Missing Values:** The dataset had no missing values to clean.
- **Multicollinearity:** Not explicitly addressed but could be a factor in the model's stability.

## Fraud Detection Model

- **Model Used:** XGBoost, a gradient boosting algorithm.
- **Performance:** XGBoost achieved the highest F1-score of **0.32** for the fraud class (Class 1).
- **Comparison:** Custom ANN model had an F1-score of **0.17** for the fraud class.

## Data Summary

- **Not Fraud (Class 0):** 6,354,407 samples
- **Fraud (Class 1):** 8,213 samples

## Variable Selection

- **Based on:** Domain knowledge and available features.
- **Techniques Used:** Feature engineering, including dummy variables for categorical features and scaling for numerical features.

## Performance Evaluation

- **Tools Used:** Confusion matrix and classification report.
- **Key Insight:** The model effectively identifies fraudulent transactions with a higher recall for Class 1.

## Prevention Measures

- **Recommended Actions:**
  - Implement advanced anomaly detection algorithms.
  - Enhance real-time monitoring.
  - Use two-factor authentication for high-value transactions.
  - Establish rules for high-risk transactions.

## Evaluation of Implemented Actions

- **Monitoring:** Track key metrics like precision, recall, F1-score, and accuracy regularly.
- **Audits:** Regular reviews to assess the effectiveness of fraud prevention measures.

---
