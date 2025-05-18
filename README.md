# Causal Inference on Advertisement Engagement

This project investigates the causal effect of advertisement placement (`banner_pos`) on user engagement using a synthetic dataset. It applies causal inference techniques such as Average Treatment Effect (ATE), Heterogeneous Treatment Effect (HTE), and OLS regression, providing both code and visual analysis to support the findings. The analysis treats `banner_pos = 0` as the treatment group and `banner_pos = 1` as the control group.

## Project Files
- `FADS (1).ipynb`: Jupyter notebook containing code and analysis
- `train.csv`: Training data used for simulation

## Methods Used
- Data Cleaning and Feature Engineering
- Exploratory Data Analysis (EDA)
- Linear Regression and OLS
- Simulation of Treatment and Potential Outcomes
- Estimation of ATE and HTE

## Libraries
```python
pandas, numpy, matplotlib, seaborn, sklearn, statsmodels,grf,causalforests
