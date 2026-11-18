# Hi, I'm Kolawole Fashina (kolistic4u) 👋
### Data Scientist & Machine Learning Engineer

I build end-to-end, explainable machine learning solutions that turn complex tabular, behavioral, and spatial datasets into actionable business and public-health decisions.

---

### Core Technical Stack
* **Languages & Data Manipulation:** Python, SQL, Pandas, NumPy
* **Machine Learning & Modeling:** Scikit-Learn, LightGBM, Random Forest, Logistic Regression, Imbalanced Learning
* **Validation & Explainability:** Leak-Free Pipelines, Spatial/Group Cross-Validation (`StratifiedGroupKFold`), Hyperparameter Tuning (`RandomizedSearchCV`), SHAP
* **Visualization & Reporting:** Matplotlib, Seaborn, Jupyter Notebooks, Interactive HTML Reports

---

### Featured Machine Learning Projects

#### 1. Predicting 30-Day Customer Liquidity Stress (FinTech & Credit Risk)
* **Problem:** Forecast short-term financial distress across 40,000 mobile money customers using 6-month behavioral and balance histories (`85%` vs. `15%` class imbalance).
* **Solution:** Engineered 20 temporal cash-burn and balance-depletion features (`202` total predictors) and trained a tuned **LightGBM Classifier** (`ROC-AUC: 0.8842`, `PR-AUC: 0.6376`—over 4.2x baseline).
* **Impact:** SHAP explainability revealed that sharp `M4`-to-`M3` balance cliffs (`bal_drop_m3_m4`) and recent balance ratios (`bal_ratio_m1_m6`) are the strongest early-warning signals for proactive micro-liquidity offers.
* **Repository:** https:github.com/kolistic4u/uganda-climate-mortality-ml


#### 2. Climate-Sensitive Mortality Prediction in Uganda (Public Health & Climate Risk)
* **Problem:** Identify climate-driven mortality patterns across 3,146 records and generalize predictions to 1,030 records in unseen geographic locations.
* **Solution:** Built a leak-free spatial validation pipeline (`StratifiedGroupKFold` grouped by `location`) with 22 cyclical seasonality, diurnal temperature range, and pediatric vulnerability features.
* **Repository:** https:github.com/kolistic4u/uganda-climate-mortality-ml

### Connect With Me
* **GitHub:** https://github.com/kolistic4u
* **LinkedIn:** https://linkedin.com/in/yusuf-kolawole-fashina-7a74593b1/
* **Email:** kolistic4u@gmail.com
