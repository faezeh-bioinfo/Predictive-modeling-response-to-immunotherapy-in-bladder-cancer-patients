# Bladder Cancer TF Signature - LASSO & Logistic Regression

Part of my Master's thesis project at CANTHER (Inserm, Lille), looking at a transcription factor (TF) signature linked to immunotherapy response in bladder cancer (IMvigor cohort).

## Scripts

1. **bootstrap_lasso_stability.R** — bootstrap LASSO to find stable TFs (>80% selection frequency)
2. **logistic_regression_roc.R** — logistic regression on the final 6 TFs, with odds ratios and ROC/AUC
3. **monte_carlo_cv.R** — repeated train/test splits to check model stability

## Data
Public IMvigor210 cohort. Not included here, code only.

Faezeh Rahi
