# 📊 Firm Credit Rating — 12-Week ML Project Plan

## Week 1 — Project Scoping & Setup
- Define objective (predict firm credit ratings)
- Define target variable and evaluation metrics
- Explore repository structure and data files
- Set up environment (Python, venv, dependencies)
- Draft initial README and roadmap

## Week 2 — Data Understanding & EDA
- Load datasets and inspect schema
- Identify missing values and outliers
- Analyze class distribution (rating imbalance)
- Correlation analysis between features
- Save EDA plots and notes

## Week 3 — Data Cleaning
- Handle missing values (drop / impute)
- Fix inconsistent formats
- Remove or cap extreme outliers
- Validate cleaned dataset

## Week 4 — Preprocessing Pipeline
- Encode categorical variables
- Scale / normalize numerical features
- Build reproducible preprocessing pipeline
- Persist pipeline for reuse

## Week 5 — Feature Engineering
- Create financial ratios (liquidity, leverage, profitability)
- Generate interaction features if useful
- Drop redundant or low-signal features
- Feature selection (filter methods)

## Week 6 — Baseline Models
- Train baseline models:
  - Logistic Regression
  - Decision Tree
- Establish baseline performance
- Confusion matrix and class-wise metrics

## Week 7 — Advanced Models
- Train ensemble / nonlinear models:
  - Random Forest
  - Gradient Boosting / XGBoost
  - SVM (if feasible)
- Cross-validation
- Model comparison table

## Week 8 — Hyperparameter Tuning
- Grid search / random search on top models
- Optimize for chosen metric (e.g. weighted F1)
- Save best-performing model

## Week 9 — Model Explainability
- Feature importance analysis
- SHAP / permutation importance
- Sanity check results with financial intuition
- Document insights

## Week 10 — Error Analysis & Validation
- Analyze misclassifications by rating class
- Check bias / instability across subsets
- Refine features or thresholds if needed
- Final model selection

## Week 11 — Deployment Prototype
- Package model + preprocessing
- Build simple inference interface (script or Streamlit)
- Test on unseen samples
- Ensure reproducibility

## Week 12 — Finalization & Delivery
- Clean codebase
- Finalize README and documentation
- Prepare slides / report
- Publish final results and repo

---

**TL;DR**
- Weeks 1–3: data understanding & cleaning  
- Weeks 4–7: features + models  
- Weeks 8–10: tuning, explainability, validation  
- Weeks 11–12: deployment & delivery
