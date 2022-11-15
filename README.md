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
Developed by: M.Subiksha
RegisterNumber: 212220040162 
## Least squares method:
import numpy as np
import matplotlib.pyplot as plt
X=np.array([8,2,11,6,5,4,12,9,6,1])
Y=np.array([3,10,3,6,8,12,1,4,9,14])
X_mean=np.mean(X)
print(X_mean)
Y_mean=np.mean(Y)
print(Y_mean)
for i in range(len(X)):
  a=i-X_mean
  print(a)
  for j in range(len(y)):
  b=j-Y_mean
  print(b)
  num=denum=0
for i in range(len(X)):
  num+=(X[i]-X_mean)*(Y[i]-Y_mean)
  denum+=(X[i]-X_mean)**2
m=num/denum
bb=Y_mean-m*X_mean
print(m,bb)
Y_pred=m*X+bb
print(Y_pred)
plt.scatter(X,Y,color='red')
plt.scatter(X,Y)
plt.plot(X,Y_pred,color='violet')
plt.show()
*/
```

## Output:
![scatter](output1.png)
![best fit line](output2.png)


## Result:
Thus the univariate Linear Regression was implemented to fit a straight line using least squares using python programming.
