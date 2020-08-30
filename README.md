# PREDICTING_TITANIC_SURVIVAL_RATE

RESULTS:

1) Logistic Regression Model is the most popular and the simplest Logistic
Regression. For the Logistic Regression, the following assumptions includes
features which are independent from each other and residuals are not
autocorrelated. We Fit the Logistic Regression to the Training set as well as
Choosing the best model by AIC in a Stepwise Algorithm. According to the best
model, the features Pclass, Age, Title and FamilySize significantly contribute to
the model in predicting survived to see how well the model predicts on new data
in the validation set.

For the Logistic Regression Model, the Accuracy is 85.5%.

2) The Random Forests Model has the ability to improve the predictive accuracy
by generating a large number of bootstrapped trees (based on random samples of variance. Random Forest is a powerful machine learning algorithm which
holds a relatively high classification accuracy. Here we Fit the Random Forest
Classification to the Training set.
The green, black and red lines represent error rate for death, overall and survival,
respectively. The overall error rate converges to ar Interestingly, our model predicts
death better than survival. Since the overall error rate converges to a constant and does
not seem to decrease, our choice of default 500 trees in the randomForest function is a
good choice.

For Random Forests Model, the Accuracy is 84.2%.

To improve the Random Forests Model, a cross validation could have improved our
model for both the Decision Tree classification and the random Forest classification
suffers in terms of interpretability.

Conclusions.
There are other predictive modeling methods such as Naive Bayes and Receiver
Operating Characteristics (ROC) curve which is a graphical representation of the
performance of the classifier and it shows how the model rises well above the diagonal
line. This indicates that our logistic regression model performs better. We could also
have performed a linear regression model for our prediction apart from the logistic
model.



