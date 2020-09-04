# Project

**This project involves predicting net hourly electrical energy output (EP) of the plant using hourly average ambient variables Temperature (T), Ambient Pressure (AP), Relative Humidity (RH) and Exhaust Vacuum (V)**

### Dataset
- From UCI Machine Learning Repository
- [here](https://archive.ics.uci.edu/ml/datasets/Combined+Cycle+Power+Plant)

### Results
- Each Regression Model was evaluated using the r2_score
- Multiple Linear Regression  ==> 0.93
- Polynomial Linear Regression (degree 4) ==> 0.94
- Support Vector Regression (rbf kernel) ==> 0.948
- Decision Tree Regression (10 estimators) ==> 0.92
- Random Forest Regression ==> 0.96
