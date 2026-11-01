### Environment and Run Steps

This project was developed in **Google Colab using Python 3**. The main libraries used were:

```text
pandas
numpy
matplotlib
scikit-learn
```

To reproduce the analysis:

1. Open the notebooks in Google Colab or a compatible Python environment.
2. Install the required libraries if they are not already available:
   ```bash
   pip install pandas numpy matplotlib scikit-learn
   ```
3. Place the cleaned dataset in:
   ```text
   data/processed/ontario_school_boards_clean.csv
   ```
4. Run the notebooks 
5. Execute all cells from top to bottom to reproduce the descriptive statistics, visualizations, correlation analysis, classification target, cross-validation results, and model comparisons.
6. Confirm that the final modelling dataset contains 70 school-board observations and that the analytical variables contain no missing values.
7. Review the generated outputs in the `reports/` and `figures/` folders.

A fixed `random_state=42` is used during stratified cross-validation to support reproducibility. The same predictor variables, target definition, folds, and evaluation metrics are used when comparing the majority baseline, logistic regression, and decision-tree models.# Initial_Results_and_Coding
