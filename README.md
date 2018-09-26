## Apts value(price) prediction   
This is used to predict current apts price. 

## how to use it?   
In apts page, add "predicted price". In zillow, called [home value](https://www.zillow.com/homedetails/12-E-69th-St-New-York-NY-10021/31533674_zpid/)

More work in future, predict "LAST 30 DAY CHANGE", "ONE YEAR FORECAST". 



## model analysis
[accuracy R2](http://statisticsbyjim.com/regression/interpret-r-squared-regression/) of linear regression, random forest, graduate boost are presented.     
This is just demo for 451 samples. need more work to improve algorithim. random forest, graduate boost performces much better, either will be selected.


### Gradient Boosting regression
* Advantages     
solve almost all objective function    

* Disadvantages       
1. more sensitive to overfitting if the data is noisy. Training generally takes longer because of the fact that trees are built sequentially.     
2. It is harder to tune than RF. There are typically three parameters: number of trees, depth of trees and learning rate, and the each tree built is generally shallow.   

### Random foerst
* Advantages     

1. make model more simple to interpret.     
2. reduce the variance of the model, and therefore overfitting.    
3. handle missing data.   
4. handle large data with high dimentionality.   
5. reduce the computational cost (and time) of training a model.   
   
* Disadvantages:
good job at classification not as good as regression.   
very little control on what model does.    









