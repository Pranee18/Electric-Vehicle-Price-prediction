# Electric Vehicle Price Prediction

This project evaluates and compares several machine learning models for predicting electric vehicle prices using a dataset from Kaggle.

## Model Performance Comparison

| Model                     | Accuracy (R) | Accuracy (Python) | R² (R) | R² (Python) |
|--------------------------|--------------|--------------------|--------|-------------|
| Linear Regression         | 64.64%       | 77.36%             | 0.624  | 0.73        |
| Gradient Boosting         | 84.91%       | 91.84%             | 0.913  | 0.94        |
| Random Forest             | 83.62%       | 86.94%             | 0.779  | 0.86        |
| K-Nearest Neighbors (KNN) | 52.72%       | 83.76%             | 0.108  | 0.67        |
| XGBoost                   | -            | 90.61%             | -      | 0.92        |
| **Ensemble Model**        | -            | **97.84%**         | -      | **0.97**    |

## Summary

- **Linear Regression**: Prone to overfitting; weaker generalization.
- **Gradient Boosting & Random Forest**: Strong performance and stable predictions.
- **KNN**: Lower accuracy due to data complexity.
- **XGBoost**: Efficient and accurate.
- **Ensemble Model**: Best overall performance.

## Technologies Used

- Python: scikit-learn, XGBoost, pandas, numpy
- R: caret, randomForest, gbm
- IDEs: Google colab Notebook, RStudio
