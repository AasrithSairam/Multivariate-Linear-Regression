# Implementation of Multivariate Linear Regression
## Aim
To write a python program to implement multivariate linear regression and predict the output.
## Equipments required:
1.	Hardware – PCs
2.	Anaconda – Python 3.7 Installation / Moodle-Code Runner
## Algorithm:
### Step1: Import pandas.

### Step2: Import linear model from sklearn.

### Step3: Read the files cars.csv.

### Step4: Assign the values for x and y as requried.

### Step5: Create the LinearRegression model and predict he output.

## Program:
```
#program for Implementation of Multivariate Linear Regression
#developed by: ponguru aasrith sairam
#register number: 23007809
import pandas as pd
from sklearn import linear_model
df=pd.read_csv("cars.csv")
a=df[['Weight','Volume']]
b=df[['CO2']]
regr=linear_model.LinearRegression()
regr.fit(a,b)
print("Coefficient: ",regr.coef_)
print("Intercept:",regr.intercept_)
print("Account",regr.predict([[3300,1300]]))
```
## Output:

### Insert your output

![image](https://github.com/AasrithSairam/Multivariate-Linear-Regression/assets/139331438/6ef768bd-5722-47ae-bd3f-c24d0fb41f7b)


## Result
Thus the multivariate linear regression is implemented and predicted the output using python program.
