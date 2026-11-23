# Marathon Finish Time Predictor

**Question:** Given a runner's age, gender and half-marathon split, how accurately can we predict their Boston Marathon finish time?

This is a prediction project, not a causal one: the goal is accurate forecasts, not estimating the effect of any single variable.

## Data
Boston Marathon finishers, 2015–2017 (~75,000 runners), from Kaggle:
https://www.kaggle.com/rojour/boston-results

## Planned approach
- Baseline: linear regression
- Flexible model: random forest / gradient boosting
- Metric: RMSE (minutes), with cross-validation
- Deliverable: Streamlit dashboard with a predicted finish time and an uncertainty interval

## Status
🚧 Proposal stage (ECON 3916 final project, Northeastern University)
