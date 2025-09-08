# Heart Disease Prediction

## Project Overview
This project demonstrates a machine learning workflow for predicting heart disease based on patient clinical data. I trained a Random Forest model to classify whether a patient has heart disease or not using features like age, BMI, genetic risk, and lifestyle factors.

## Dataset
The dataset used is `heart.csv`, containing patient features and the target column `HeartDisease`. Missing values were imputed, and categorical features were converted to numeric format for modeling.

## Goals
- Explore and preprocess clinical data.
- Train and evaluate a Random Forest classifier.
- Visualize feature importance and model predictions.
- Demonstrate the full machine learning workflow for biomedical data.

## Tools & Libraries
- Python (pandas, numpy, matplotlib, seaborn)
- Scikit-learn (RandomForestClassifier, train_test_split, metrics)
- Google Colab (for execution and visualization)

## Workflow
1. Load and inspect the dataset.
2. Handle missing values and encode categorical features.
3. Split data into training and test sets.
4. Train a Random Forest model.
5. Evaluate model performance (accuracy, confusion matrix, classification report).
6. Visualize feature importance and predicted vs actual counts.
7. Save results for further analysis.

## Results
- The Random Forest model achieved reasonable accuracy on the test set.
- Feature importance analysis highlighted key predictors of heart disease.
- Predicted vs actual distributions confirmed the model's predictive ability.

## Notes
This project demonstrates the workflow for a biomedical predictive modeling task. The results are meant for educational purposes and not for clinical use.

## Author
Astrid
