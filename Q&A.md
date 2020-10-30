# How to explain p-value to a non-technical person?

In a sampling theory, we estimate the parameters about the population from a subset of the population called sample. The statistics calculated from the sample are a good indication of the corresponding parameter about the population. The null hypothesis can be that the sample statistics are just good for estimating the population parameters and the alternative hypothesis is that it is not. Now the p-value is the measure of how good is the sample statistics to the population parameter. The smaller that value of p, greater the chance that the alternative hypothesis is ture. 


# What is the difference between bagging and boosting?

In bagging we randomly take the subset of the features and take the boostrap sampling of the data and make a model out of that. And we do this many times taking different randomly choosen subset of the features and separate bootstrap sampling each time and take the average of the prediction of the each individial models. This averaging process of great way to remove the variance of a model especially in tree based model. 

On the other hand in the boosting, we take the average of the many weak learners and thake their average. Especially in the case of tree based boosting model the weak learner can just be a stump but not the fully grown tree. In each subsequent iteration of the boosting the model gives more weights to the previously misclassified samples and make the model out of that thus improving the accuracy in successive steps. 

# Expalin SVM and c parameter. 


# How would you explain Hypothesis testing for a newbie?

Hyoothesis testing is related to the sampling theory. If we want to know something about the population and it is too learge to deal with the way to go in treditional statistics is to take a samll sample of it, calculate the things on the smaple and estimate the corresponding parameters about the population based on the information we got in the sample.  Although we can with high confidence predict the population from the sample, we can not be 100% sure about the population from the sample. Here comes the hypothesis testing. So usually we set the null hypothesis conservatively that whatever we see in the sample is true behavior of the population as well. And the alternative hypothesis is that it is not. And a statistician can tell which hypothsis is correct with what probability. 


# What is overfitting and underfitting?

If a model is performing very well on the training data and poorly on the testing data then it is called the overfitting. Overfitting means the model has low bias and high variance. 

On the other hand underfitting means the model is not performing well in both training and testing data, or at least there is some room of imrpovement in both cases. Underfitting means high bias and low variance. 


# How to prevent overfitting?

There are basically two ways to prevent overfitting: get more data and reduce the model complexity. They are not mutually exclusive and can be done together. However, in many cases it is not easier to get more data and we need to relay on the second option. One of the systematic way to reduce the model complexity is to use the regualrization to the model. It automatically selects the parameters from the model giving more weight to a more important parameter and less weight to the less important one. This also solves the problem of multicollinearity. 


# What are the assumptions of the linear regression?

# How to deal with the problem of multicollinearity in the linear model?

# What is supervised and unsupervised model?



