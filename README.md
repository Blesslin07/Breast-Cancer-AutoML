# Breast-Cancer-AutoML
Early Breast Cancer Detection using Random Forest, MLJAR AutoML, and SHAP
## Problem Statement
Breast cancer remains one of the deadliest diseases among women globally. Early detection is critical to reduce mortality. Traditional methods like mammograms suffer from:
- High false positive rates (up to 30%)
- Diagnostic delays in rural areas
- Radiologist variability

Our goal is to automate diagnosis using machine learning, ensuring:
- ≥95% accuracy
- ≥30% reduction in false positives
- Clinical explainability (using SHAP)

## Approach

### Models Used
- Random Forest (with GridSearchCV)
- MLJAR AutoML (LightGBM, XGBoost, Decision Tree)

### Features
- Comparative performance metrics
- ROC & Bar chart visualizations
- SHAP explainability
- Interactive diagnosis widget
- Based on WDBC dataset

## Files
- `Assignment3.ipynb` – Main notebook with full pipeline
- `README.md` – You’re reading it!

## Conceptual Enhancement: AGI in Medicine
We explored how **Artificial General Intelligence (AGI)** could reshape cancer diagnosis workflows by integrating vision, language, and logic across clinical systems.

## Run Locally
```bash
git clone https://github.com/Blesslin07/Breast-Cancer-AutoML.git
cd Breast-Cancer-AutoML
jupyter notebook
