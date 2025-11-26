## 📌 Credit Risk Modelling – PD & Expected Loss Framework (Python, ML, Risk Analytics)

This project delivers a complete end-to-end credit risk pipeline, from data exploration to model validation, following real practices used in Model Risk and Credit Analytics teams. It includes full data preparation, PD modelling, LGD/EAD estimation, and Expected Loss (EL) evaluation, together with comprehensive model quality assessment.

## 🔍 Exploratory Data Analysis (EDA)

I performed an in-depth analysis of the credit portfolio, generating insightful visualisations and engineering new features—such as ROI, which helped identify loans with underpriced installments. I removed duplicates, outliers, and missing values, and dropped variables violating logistic regression assumptions.
The dataset was split using a time-series approach (train ≤ 2014, test ≥ 2015), consistent with best practices in credit risk modelling.

## 🧩 Feature Preparation & PD Modelling

I constructed a robust feature set through VIF analysis and multicollinearity reduction. I built and trained a logistic regression model to estimate the Probability of Default (PD) and used these predictions to compute Expected Loss (EL) on the test set, together with my own LGD mapping and EAD estimation.

## 📈 Model Validation & Performance Assessment

Model calibration was evaluated using calibration plots, comparing predicted PD against observed default rates, following Model Risk Management (MRM) standards.

Additional model performance components (WIP):

- Feature importance analysis (WIP)

- ROC-AUC, KS, Brier Score evaluation (WIP)

- XGBoost benchmark for nonlinear modelling (WIP)

- Extended EL portfolio-level diagnostics (WIP)

These components are partially implemented and actively being expanded in the repository.
