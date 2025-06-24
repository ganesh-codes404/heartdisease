### Predicting Heart Disease Risk Using Probabilistic Graphical Models

This project uses a Bayesian Network, built with the pgmpy library, to predict heart disease risk based on simulated patient data. 
The dataset -> [Dataset](https://bit.ly/3T1A7Rs)


## Project Overview

This project uses a **Bayesian Network**, built with the `pgmpy` library, to predict heart disease risk based on simulated patient data. The dataset includes features like:

- `age`: Patient age  
- `fbs`: Fasting blood sugar  
- `chol`: Cholesterol level  
- `thalach`: Maximum heart rate achieved  
- `target`: Presence of heart disease (1 = Yes, 0 = No)  

A predefined Bayesian structure is applied: age → fbs → target → chol, thalach

The model estimates probabilities of heart disease and related health metrics through **Maximum Likelihood Estimation (MLE)**.

## Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/your-username/heart-disease-bayesian.git
cd heart-disease-bayesian
```
2. Open the notebook and when prompeted manually upload the file 

## Sample Output

### 2. Inference: Heart Disease Probability by Age

Example bar chart output:

| Normalized Age | Probability of Heart Disease |
|----------------|------------------------------|
| 0.0            | 0.12                         |
| 0.25           | 0.28                         |
| 0.5            | 0.45                         |
| 0.75           | 0.62                         |
| 1.0            | 0.79                         |




