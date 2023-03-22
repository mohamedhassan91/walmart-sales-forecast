# walmart-sales-forecast
***The objective to predict the future sales of walmart supermarket by implemnting different regression models*** 
### EDA

***corelation between target and features***
![image](https://user-images.githubusercontent.com/60258264/226952380-aab7d52a-a819-4133-8031-df679647055c.png)

***weekly sales with fuel price distrbution***

![image](https://user-images.githubusercontent.com/60258264/226952574-b15fe79a-9d47-4d27-8538-732e5a3c7336.png)

***outliers Distbution***

![image](https://user-images.githubusercontent.com/60258264/226953010-c6fce303-dd68-4de3-95be-df3654540255.png)

### Models and Evalution 

We tested different regression models after selecting features and goal

***LinearRegression***

```
Test set evaluation:
_____________________________________
MAE: 87271.28314659592
MSE: 19653895261.796368
RMSE: 140192.35093897372
R2 Square 0.9367171766235523
__________________________________
Train set evaluation:
_____________________________________
MAE: 81566.25494693119
MSE: 15292049420.168428
RMSE: 123661.02627816262
R2 Square 0.9493312151487244
```
***Ridge Regression***
```
Test set evaluation:
_____________________________________
MAE: 87525.97003087513
MSE: 19972238364.495617
RMSE: 141323.16994921822
R2 Square 0.9356921558796804
__________________________________
====================================
Train set evaluation:
_____________________________________
MAE: 81413.28016176337
MSE: 15438721136.279015
RMSE: 124252.65041953437
R2 Square 0.9488452320457943
```
***Lasso Regression***
```
Test set evaluation:
_____________________________________
MAE: 87350.40972013283
MSE: 20422398623.284584
RMSE: 142906.95792467415
R2 Square 0.9342427021317807
__________________________________
====================================
Train set evaluation:
_____________________________________
MAE: 81602.27570761013
MSE: 15910117466.280811
RMSE: 126135.31411258629
R2 Square 0.9472833041074081
```
***SGDRegressor***
```
Test set evaluation:
_____________________________________
MAE: 87599.8628090775
MSE: 20154205309.62161
RMSE: 141965.50746438943
R2 Square 0.9351062474938173
__________________________________
====================================
Train set evaluation:
_____________________________________
MAE: 81419.71048669098
MSE: 15589024051.750093
RMSE: 124856.01327829626
R2 Square 0.9483472173011859
```
