# Optimization and Productization of Marketing Target Models Using MLflow

## Data Source
- https://archive.ics.uci.edu/ml/datasets/Bank+Marketing

## Project Overview

This project focuses on optimizing marketing target models by analyzing bank customer data. Using MLflow, experiments were conducted with XGB and MLP models, and the model with the best performance was deployed on a local host.

---

### Summary of Experiment Results
- **Total Runs:** 5  
- **Metrics of Interest:** F1 Score (Test & Validation), Precision, Recall, ROC AUC (Test & Validation).

### Performance Overview
| Run ID                        | F1 (Test) | F1 (Validation) | Precision (Test) | Recall (Test) | ROC AUC (Validation) |
|-------------------------------|-----------|------------------|------------------|---------------|-----------------------|
| **cd5b41719b29469d98b42dfbfbcd1b09** | **0.7795** | **0.9779**       | 0.7417           | **0.8494**    | **0.9981**           |
| b7fba6c45be84cc2bc3c7d40be5d475d | 0.7618    | 0.9691           | 0.7272           | 0.8251        | 0.9960               |
| e242854578ed46aa867796084d7a4fad | 0.7728    | 0.9364           | **0.7492**       | 0.8051        | 0.9871               |
| 78cc0600c7f04c339014e81b0e984540 | 0.7449    | -                | 0.7139           | 0.8002        | -                    |
| 0bd9db1dfb2044b6a92538b31a679e74 | 0.7763    | 0.9494           | 0.7612           | 0.7944        | 0.9920               |

### Best Performing Models by Metric
1. **F1 Score (Test & Validation):**  
   - Run ID: **cd5b41719b29469d98b42dfbfbcd1b09**  
   - F1 Score (Test): 0.7795, F1 Score (Validation): 0.9779  

2. **Precision (Test):**  
   - Run ID: **e242854578ed46aa867796084d7a4fad**  
   - Precision (Test): 0.7492  

3. **Recall (Test):**  
   - Run ID: **cd5b41719b29469d98b42dfbfbcd1b09**  
   - Recall (Test): 0.8494  
