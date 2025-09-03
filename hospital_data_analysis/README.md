# Hospital Length of Stay Analysis

**Goal:** Predict patient length of stay using patient features.  
**Tools:** Python, pandas, scikit-learn, matplotlib  


---

## Dataset

- File: `LengthOfStay.csv`  
- Features include:  
  - Gender (`gender`)  
  - Dialysis stage (`dialysisrenalendstage`)  
  - Asthma (`asthma`)  
  - Iron deficiency (`irondef`)  
- Target variable: `rcount` (length of stay in days, with "5+" replaced by 5)

---

## Analysis Steps

1. **Load and inspect dataset** – check column types, missing values, and basic statistics.  
2. **Feature preparation** – convert categorical variables to dummy variables; ensure correct data types.  
3. **Train-test split** – split features and target into training and testing sets.  
4. **Train Linear Regression model** – fit on training data.  
5. **Predict and evaluate** – calculate Mean Squared Error on test set.  
6. **Visualize results** – scatter plot of actual vs predicted length of stay.  
7. **Save results** – store predictions and plots in the `results/` folder.

---

## Results

- **Mean Squared Error (MSE):** calculated on test set (see `results/predictions.csv`)  
- **Visualization:** `results/actual_vs_predicted.png` shows predicted vs actual values, with most points near the diagonal line (y = x), indicating reasonable predictions.  

**Interpretation:** The Linear Regression model predicts patient length of stay fairly well. Deviations reflect natural variability in patient features.



## Author

Astrid


