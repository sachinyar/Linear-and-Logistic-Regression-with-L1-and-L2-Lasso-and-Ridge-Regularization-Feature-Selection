# Linear-and-Logistic-Regression-with-L1-and-L2-Lasso-and-Ridge-Regularization-Feature-Selection
Linear and Logistic Regression with L1 and L2 ( Lasso and Ridge) Regularization for Feature Selection
Download Working Files: https://github.com/laxmimerit/Linear-and-Logistic-Regression-with-L1-and-L2-Lasso-and-Ridge-Regularization-Feature-Selection

Linear regression is a straightforward approach for predicting a quantitative response Y on the basis of a different predictor variable X1, X2, ... Xn. It assumes that there is a linear relationship between X(s) and Y. Mathematically, we can write this linear relationship as Y ≈ β0 + β1X1 + β2X2 + ... + βnXn.

Basic Assumptions
Linear relationship with the target y
Feature space X should have gaussian distribution
Features are not correlated with other
Features are in same scale i.e. have same variance

Lasso (L1) and Ridge (L2) Regularization
Regularization is a technique to discourage the complexity of the model. It does this by penalizing the loss function. This helps to solve the overfitting problem.

Regularization adds a penalty on the different parameters of the model to reduce the freedom of the model. Hence, the model will be less likely to fit the noise of the training data and will improve the generalization abilities of the model

L1 regularization (also called Lasso)
L2 regularization (also called Ridge)
L1/L2 regularization (also called Elastic net)
A regression model that uses L1 regularization technique is called Lasso Regression and model which uses L2 is called Ridge Regression.

The key difference between these techniques is that Lasso shrinks the less important feature’s coefficient to zero thus, removing some feature altogether. So, this works well for feature selection in case we have a huge number of features.

The L1 regularization adds a penalty equal to the sum of the absolute value of the coefficients.

The L1 regularization will shrink some parameters to zero. Hence some variables will not play any role in the model, L1 regression can be seen as a way to select features in a model

What is Ridge Regularisation
The L2 regularization adds a penalty equal to the sum of the squared value of the coefficients.

The L2 regularization will force the parameters to be relatively small, the bigger the penalization, the smaller (and the more robust) the coefficients are.

Difference between L1 and L2 regularization
L1 Regularization
L1 penalizes sum of absolute value of weights.
L1 has a sparse solution
L1 has multiple solutions
L1 has built in feature selection
L1 is robust to outliers
L1 generates model that are simple and interpretable but cannot learn complex patterns

L2 Regularization
L2 regularization penalizes sum of square weights.
L2 has a non sparse solution
L2 has one solution
L2 has no feature selection
L2 is not robust to outliers
L2 gives better prediction when output variable is a function of all input features
L2 regularization is able to learn complex data patterns

Like Facebook Page: https://www.facebook.com/kgptalkie/

Watch Full Playlists: Feature Selection in Machine Learning using Python: https://www.youtube.com/playlist?list=PLc2rvfiptPSQYzmDIFuq2PqN2n28ZjxDH

Machine Learning with Theory and Example https://www.youtube.com/playlist?list=PLc2rvfiptPSTvPFbNlT_TGRupzKKhJSIv

Make Your Own Automated Email Marketing Software in Python: https://www.youtube.com/watch?v=gmYuom6kfoY&list=PLc2rvfiptPSQK9ErKaLqf40iu1A3le9Zr
