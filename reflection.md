# Reflection of AI Model Optimization

## Data scaling

In the document you can see that I have scaled the data the data with three different methods. The Robust scaling, the Standard Scaling and the Min-Max Scaling. Before the scaling the data did not has any touchpoints in the diagram. Aftet the scaling the curves for the datapoints align with each other more or less.

You can clearly see to what kind of value all three scaling methods transform the data too.

# Hyperparameters

For the hyperparameters I read online that it would be a better idea to use the RandomSearchCV which will optimize the parameters by testing combinations and returning the best possible solution.

Doing the optimization does not lead to better results. Doing the RandomForest model creates without optimizing the parameters a accuracy of 0.523. After running the optimizations and creating a model with it the accuracy is by 0.528 which is not that much better and shows that running the randomForest model with the default parameters is already as good as it potentially could get.

# 10 K-Cross Validation

I did the 10 K-Cross Validation for every model I have created (linear regession and Random forest). If we look more closely at the boxplot which was made for the linear regession model, we can see that it got better by doing more splits. That means that when we do more splits the performance of the model gets better.

But in general the scores doe not get better a lot. The mean value differs from 0.8449 to 0.8445. In general we should then think about if the extra work for this specific case is usefull.
