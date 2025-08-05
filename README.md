# Student-Score-Prediction-Regression-Model-
# Student Exam Score Prediction

## Project Overview
This project predicts student exam scores based on study habits and environmental factors using regression techniques. The best-performing model achieved 73% accuracy (R²=0.73) using simple linear regression with study hours as the sole predictor.

## Key Findings
- **Study hours** showed the strongest correlation with exam performance
- Simple models outperformed complex ones (polynomial/feature combinations)
- Other factors like attendance and previous scores showed moderate predictive power
- Non-academic factors (sleep, motivation) had less impact than expected

## Models Tested
| Model Type                     | MSE  | R² Score |
|--------------------------------|------|----------|
| Simple Linear Regression       | 4.15 | 0.73     |
| Polynomial Regression (deg=2)  | 4.39 | 0.72     |
| Feature Combo 1 (3 features)   | 6.48 | 0.58     |
| Feature Combo 2 (4 features)   | 12.17| 0.22     |

