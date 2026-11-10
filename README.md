
# Heart Disease Prediction: Analyzing and Addressing Overfitting

## Project Overview
This project uses a Random Forest Classifier to predict heart disease based on patient health data.

The main goal is to build a machine learning model and explore the concept of overfitting by comparing a baseline model with a tuned model.

## Dataset
The dataset contains patient health information and a target variable indicating the presence or absence of heart disease.

## Tools & Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Jupyter Notebook

## Project Steps
1. Data loading and exploration
2. Data visualization
3. Splitting the data into training and testing sets
4. Building a baseline Random Forest model
5. Evaluating model performance
6. Adjusting hyperparameters to reduce overfitting
7. Comparing the baseline and tuned models

## Model Results

| Metric | Baseline Model | Tuned Model |
|---|---:|---:|
| Training Accuracy | 100% | 90.5% |
| Testing Accuracy | 83.6% | 80.3% |
| Accuracy Gap | 16.4% | 10.2% |

## Key Findings
- The baseline model achieved 100% training accuracy, indicating signs of overfitting.
- Hyperparameter tuning reduced the accuracy gap from 16.4% to 10.2%.
- However, testing accuracy decreased slightly from 83.6% to 80.3%.
- Reducing overfitting does not always mean improving testing accuracy.

## Conclusion
This project helped me understand how overfitting affects machine learning models and how hyperparameter tuning can help reduce it.

It also showed me that evaluating a model requires looking beyond training accuracy and considering its performance on unseen data.

## Author
Buthaina Alsurmi
