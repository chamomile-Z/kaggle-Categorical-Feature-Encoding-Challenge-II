#### What is Boosting?
The term ‘Boosting’ refers to a family of algorithms which converts weak learner to 
strong learners. Boosting is an ensemble method for improving the model predictions 
of any given learning algorithm. The idea of boosting is to train weak learners sequentially, 
each trying to correct its predecessor.
![](https://miro.medium.com/max/1600/0*qCcM7uCOqIw6npnJ.png)  


#### Gradient Boosting
Gradient Boosting works by sequentially adding predictors to an ensemble, each one correcting its predecessor. However, instead of changing the weights for every incorrect classified observation at every iteration like AdaBoost, Gradient Boosting method tries to fit the new predictor to the residual errors made by the previous predictor. 
GBM uses Gradient Descent to find the shortcomings in the previous learner's predictions. GBM algorithm can be given by following steps.
* Fit a model to the data, F1(x) = y
* Create a new model, F2(x) = F1(x) + h1(x)
* By combining weak learner after weak learner, our final model is able to account for a lot of the error from the original model and reduces this error over time.


#### XGBoost
XGBoost stands for eXtreme Gradient Boosting. XGBoost is an implementation of gradient boosted decision trees designed for speed and performance. Gradient boosting machines are generally very slow in implementation because of sequential model training. Hence, they are not very scalable. Thus, XGBoost is focused on computational speed and model performance. XGBoost provides:
* Parallelization
* Distributed Computing
* Out-of-Core Computing
* Cache Optimization

#### Reference
<https://medium.com/greyatom/a-quick-guide-to-boosting-in-ml-acf7c1585cb5>
