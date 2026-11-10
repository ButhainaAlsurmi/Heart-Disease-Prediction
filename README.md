
# Supervised Machine Learning: Heart Disease Prediction – Analyzing and Addressing Overfitting

## Project Overview

This project applies Supervised Machine Learning using a Random Forest Classifier to predict the presence of heart disease based on patient health data.

The main goal is not only to build a predictive model, but also to investigate overfitting and understand how hyperparameter tuning can improve model generalization.

The project compares a baseline model with a tuned model using GridSearchCV and 5-fold cross-validation..

## Dataset

The dataset contains 303 patient records with 13 features related to heart health and a target variable indicating the presence or absence of heart disease.

- 0: No heart disease
- 1: Heart disease

## Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Steps

1. Data loading and exploration
2. Exploratory Data Analysis (EDA)
3. Splitting the data into training and testing sets
4. Building a baseline Random Forest model
5. Evaluating baseline model performance
6. Hyperparameter tuning using GridSearchCV
7. Comparing models using 5-fold cross-validation
8. Evaluating Recall for heart disease detection
9. Comparing baseline and tuned model performance

## Model Results

| Metric | Baseline Model | Tuned Model |
|---|---:|---:|
| Training Accuracy | 100% | 88.8% |
| Testing Accuracy | 83.6% | 80.3% |
| Accuracy Gap | 16.4% | 8.5% |
| Mean CV Accuracy | 83.1% | 84.3% |
| Recall | 0.97 | 0.97 |

## Hyperparameter Tuning

GridSearchCV was used to find the best hyperparameters for the Random Forest model.

The search was performed using 5-fold cross-validation on the training set only, while the test set was kept for final evaluation.

## Key Findings

- The baseline model achieved 100% training accuracy, indicating overfitting.
- GridSearchCV reduced the accuracy gap from 16.4% to 8.5%.
- The tuned model achieved a mean cross-validation accuracy of 84.3%, compared to 83.1% for the baseline model.
- Testing accuracy decreased slightly from 83.6% to 80.3%, a difference of only 2 patients out of 61.
- Both models achieved a Recall of 0.97, correctly identifying 32 out of 33 patients with heart disease.
- Reducing overfitting does not necessarily mean achieving higher testing accuracy.

## Conclusion

This project helped me understand how overfitting affects machine learning models and how hyperparameter tuning can help reduce it.

By using GridSearchCV and 5-fold cross-validation, I was able to compare model performance more reliably.

The tuned model reduced overfitting while maintaining the same Recall as the baseline model.

Overall, the results demonstrated the importance of evaluating machine learning models using multiple metrics rather than relying on accuracy alone.

## Author

Buthaina Alsurmi
