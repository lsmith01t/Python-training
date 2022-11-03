The goal of this project was to use ML algorythms to predict 



The data uses both a decision tree and a logistic regresion model to predict outlet sales for individual items (target) based on eleven features. 

From a correlation heat map analysis of the various features we can see that Item MRP is the most correlated with the target. 
![image](https://user-images.githubusercontent.com/111142792/199847340-539e7c76-f494-44da-82ad-7e4bba84d1ae.png)

First thought would be to expect high visibility of the product to have an impact on sales however from plotting the following scatter chart you can see there is not a strong correlation between the two. 

![image](https://user-images.githubusercontent.com/111142792/199847868-38fbb372-b58b-4c28-b935-eac16d9e6567.png)

The models chosen to predict the target were chosen because this is a regression analysis vs a classification exercise. The two models chosen were Linear Regression and Decision tree regression. 

After training and testing both models, without any hyper parameter tuning, the decision tree model perform significantly better than they linear regression model. 

It appears the best model to use woudl be the decision tree model, but additional hyperparameter tuning needs to be performed to improve accuracy and the R2 score. 
