# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipment’s required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1
<br>

### Step2
<br>

### Step3
<br>

### Step4
<br>

### Step5
<br>

## Program:
```
# Python program to implement multivariate linear regression
# Developed by:Bhuvanesh.S.R
# Register Number:212223240017
import pandas as pd
from sklearn import linear_model
data=pd.read_csv("cars.csv")
x=data[['Weight','Volume']]
y=data[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(x,y)
print('Coefficients:',regr.coef_)
print('Intercept:',regr.intercept_)
predictCO2=regr.predict([[3300,1300]])
print('Predicted CO2 for the corresponding weight and volume',predictCO2)
```
## Output:
![exp 10 maths (2)](https://github.com/Bhuvanesh-Suresh/Multivariate-Linear-Regression/assets/145742661/1e931e20-0ccc-45dc-8c75-0004e858eb66)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
