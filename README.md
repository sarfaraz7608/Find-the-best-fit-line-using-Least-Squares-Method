# Implementation of Univariate Linear Regression
## AIM:
To implement univariate Linear Regression to fit a straight line using least squares.

## Equipments Required:
1. Hardware – PCs
2. Anaconda – Python 3.7 Installation / Jupyter notebook

## Algorithm
1. Get the independent variable X and dependent variable Y.
2. Calculate the mean of the X -values and the mean of the Y -values.
3. Find the slope m of the line of best fit using the formula. 
<img width="231" alt="image" src="https://user-images.githubusercontent.com/93026020/192078527-b3b5ee3e-992f-46c4-865b-3b7ce4ac54ad.png">
4. Compute the y -intercept of the line by using the formula:
<img width="148" alt="image" src="https://user-images.githubusercontent.com/93026020/192078545-79d70b90-7e9d-4b85-9f8b-9d7548a4c5a4.png">
5. Use the slope m and the y -intercept to form the equation of the line.
6. Obtain the straight line equation Y=mX+b and plot the scatterplot.

## Program:
```
/*
Program to implement univariate Linear Regression to fit a straight line using least squares.
Developed by:SARFARAZ I 
RegisterNumber: 212225230252
import numpy as np
import matplotlib.pyplot as plt
X=np.array([1,2,3,4,5])
Y=np.array([2,4,5,4,5])
x_mean=np.mean(X)
y_mean=np.mean(Y)
m=num/den
c=y_mean-m*x_mean
num=np.sum((X-x_mean)*(Y-y_mean))
den=np.sum((X-x_mean)**2)
print("slope(m):",m)
print("Intercept(c):",c)
Y_pred=m*X+c
x=int(input("Enter the value"))
y=m*float(x)+c
print("Value:",y)
plt.scatter(X,Y,label="Datapoints")
plt.plot(X,Y_pred,label="Best fit line")
plt.xlabel("X")
plt.ylabel("Y")
plt.legend()
plt.title("Univariate linear regression")
plt.show() 
*/
```

## Output:
<img width="707" height="532" alt="image" src="https://github.com/user-attachments/assets/35cd64af-be4c-4cf1-9e19-0099b4284a13" />




## Result:
Thus the univariate Linear Regression was implemented to fit a straight line using least squares using python programming.
