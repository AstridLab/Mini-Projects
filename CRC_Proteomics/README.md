## CRC Proteomics Project
## Overview

This project analyzes colorectal cancer (CRC) proteomics data to identify proteins that distinguish tumor tissue from normal tissue. Using protein expression data, the project explores patterns with PCA and builds a logistic regression model to classify tumor vs normal samples. The analysis highlights the top proteins most associated with tumor classification.
## Goals

Clean and align CRC proteomics datasets.

Visualize tumor vs normal samples using PCA.

Train a logistic regression model for classification.

Identify the top 20 proteins most predictive of tumor status.

Save all results in a structured results/ folder.

## Tools

Python 3

pandas, numpy

scikit-learn (StandardScaler, PCA, LogisticRegression, train_test_split, metrics)

matplotlib, seaborn

## Mini Conclusion

Dataset was successfully cleaned and aligned, keeping 143 Tumor and 131 Non-tumor samples.

PCA shows partial separation between tumor and normal samples.

Logistic regression achieved reasonable classification performance (accuracy and ROC AUC).

Top 20 proteins identified may serve as candidate biomarkers for CRC.

## How to Run

Open the notebook(s) in the code/ folder.

Ensure datasets in data/ are present.

Run all scripts to reproduce results in results/.

## Author

Astrid
