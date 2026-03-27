# Dollar Spot Prediction — ML Benchmarking Study

Dissertation code for:
**"Extending the Smith-Kerns Dollar Spot Prediction Model: 
A Comparative Machine Learning Approach for Cross-Regional 
Turfgrass Disease Forecasting"**

Risheeraj Singh Sanjeev Samyal  
Gisma University of Applied Sciences, 2026  
Supervisor: Prof. Dr. Mohammad Mahdavi

---

## Overview

This repository contains the complete experimental pipeline 
for benchmarking logistic regression, random forest, and 
XGBoost against the Smith-Kerns dollar spot prediction 
baseline across 18 experimental conditions using 
GroupKFold cross-validation.

---

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/YOUR_USERNAME/dollar-spot-prediction.git
cd dollar-spot-prediction
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Download the dataset
The dataset is publicly available from the Dryad Digital 
Repository:

**Smith, D.L. et al. (2018)**  
*Data from: Development and validation of a weather-based 
warning system to advise fungicide applications to control 
dollar spot on turfgrass*  
DOI: https://doi.org/10.5061/dryad.9m771

Download the file:  
`2008+to+2010+5+day+MoveAve+datasets.xls`

Place it in the `data/` folder.

### 4. Update the data path
Open `dollar_spot_dissertation.ipynb` and update Cell 2:
```python
DATA_PATH = r"data/2008+to+2010+5+day+MoveAve+datasets.xls"
```
