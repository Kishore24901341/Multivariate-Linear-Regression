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
# Developed by: Kishore.V
# Reg no: 24901341

import pandas as pd

from sklearn import linear_model

df = pd.read_csv("C:\\Users\\admin\\Downloads\\car (1).csv")

X = df[['Weight', 'Volume']]

y = df['CO2']

regr = linear_model.LinearRegression()

regr.fit(X, y)

print('Coefficients:', regr.coef_)

print('Intercept:',regr.intercept_)

predictedCO2 = regr.predict([[3300, 1300]])

print('Predicted CO2 for the corresponding weight and volume',predictedCO2)



```
## Output:

### Insert your output
![image](https://github.com/user-attachments/assets/7a17af54-f012-496a-889e-626ba3d1ec29)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
