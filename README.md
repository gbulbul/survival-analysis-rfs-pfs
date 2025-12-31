# Survival Analysis with Cox Proportional Hazards Model and KM estimator

This project provides a concise, hands-on demonstration of survival analysis in
Python and includes both the Kaplan–Meier estimator and the Cox Proportional
Hazards model. The Kaplan–Meier estimator is used to non-parametrically estimate
and visualize the survival function while accounting for right-censored data,
whereas the Cox model is applied to assess covariate effects through hazard ratio
estimation and coefficient visualization. The analysis is intended for
educational and illustrative purposes, with an emphasis on interpretability and
core survival analysis concepts rather than inferential conclusions.

---

## 📌 Project Objectives

- Perform survival analysis using real or simulated time-to-event data
- Fit a Cox Proportional Hazards (Cox PH) model
- Interpret coefficients and hazard ratios
- Visualize model estimates with confidence intervals
- Provide a fully reproducible Google Colab workflow

---

## Project Overview for Demo Codes
This repository provides a minimal, end-to-end demonstration of survival analysis using Python and Jupyter Notebook. The notebook illustrates core concepts including Kaplan–Meier survival estimation and the Cox proportional hazards model, implemented with commonly used scientific libraries. The dataset is intentionally small and synthetic, containing basic variables such as follow-up time, event indicator, age, and treatment assignment, in order to keep the focus on methodology rather than predictive performance.

---

## Demo Code and Scope
The code walks step by step through data preparation, non-parametric survival curve estimation, and semi-parametric Cox regression modeling. Model outputs such as coefficients, hazard ratios, confidence intervals, and diagnostic warnings are explicitly displayed and interpreted. Due to the extremely limited sample size and number of events, the results are numerically unstable and not intended for inferential conclusions. Instead, this project serves as a hands-on, educational example of survival analysis workflows in Python and as a reproducible template that can be extended to real-world clinical or biomedical datasets.
