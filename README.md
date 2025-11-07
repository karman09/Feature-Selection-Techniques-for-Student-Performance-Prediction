#  A Comparative Study of Feature Selection Techniques for Student Performance Prediction

## ⚙️ Run in Google Colab
Open directly in Colab 👉  
[🔗(https://colab.research.google.com/drive/1H3mt3gUt_Hqm_A7vs5nIy11dIVnIW5tC#scrollTo=FUAc_4tILn0v))])

### 🎯 Research Aim and Scope

The project compares six FS strategies — **Varimax, LASSO, RFE, Tree Importance, Union, and Intersection** — across multiple setups (**A_All, B_NoG2, C_NoG1G2**) and tasks (binary classification, five-level classification, and regression).

Five **machine learning models** were used to evaluate FS effects on predictive performance: *Multi-Layer Perceptron (MLP), Support Vector Machine (SVM), Decision Tree (DT), Random Forest (RF),* and *XGBoost (XGB)*.  
A rule-based **Naive Predictor (NVref)** served as a baseline for statistical comparison.

By applying **Friedman χ²** and **Wilcoxon–Holm** tests, the study provides statistically validated, reproducible, and interpretable model comparisons — offering a modernized methodological extension of the reference study.

---
### ⚙️ Cross-Validation & Significance Testing

- **Nested Evaluation:**  
  - `RepeatedStratifiedKFold` *(10×20)* for classification  
  - `RepeatedKFold` *(10×20)* for regression  
- **Significance Tests:**  
  - *Friedman χ²* for overall FS comparison  
  - *Wilcoxon (Holm-corrected)* for pairwise significance  
- **Result Markers:**  
  - ▲ (best mean), † (statistically superior), * (better than baseline)


## 🧾 Citation
Arman Tunçer, K., 2025. A Comparative Study of Feature Selection Techniques for Student Performance Prediction. GitHub repository.
URL: https://github.com/karman09/Feature-Selection-Techniques-for-Student-Performance-Prediction

---
### References
Cortez, P., & Silva, A. (2008). *Using Data Mining to Predict Secondary School Student Performance.*  

This project is licensed under the **MIT License** - see the [LICENSE](LICENSE) file for details.
