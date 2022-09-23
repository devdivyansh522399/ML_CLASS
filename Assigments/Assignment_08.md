**1. What are some benefits of feature selection? How do you use the F-test to select
the features?**

Ans. It helps you to build good model, it makes more simpler and interpretable where you drop non-correlated data w.r.t target attribute. F-test is used to compare means of different groups specifically when there are more than 2 groups. The larger the f-score then that feature has highest contribution to target label.

**2. Can we use PCA for feature extraction? If yes, then why?**

Ans. PCA is used for reducing the dimensionality of the dataset(reducing features from the dataset).It doesnot do feature selection.ForExample, If i have 25 features i can convert those 25 features to 5 features to solve underfitting problem. It basically creates a new vector space with the reduced feature number. You can say, It is a Feature Extraction technique.

**3. What’s the difference between forwarding Feature Selection and Backward Feature Selection?**

Ans: <ins>Forwarding Feature Selection</ins>: This is an iterative method wherein we start with the best performing variable against the target. Next, we select another variable that gives the best performance in combination with the first selected variable. This process continues until the preset criterion is achieved.

<ins>Backward feature Selection</ins>: This method works exactly opposite to the Forward Feature Selection method. Here, we start with all the features available and build a model. Next, we take variable from the model which gives the best evaluation measure value. This process is continued until the preset criterion is achieved.

**4. How do you transform a skewed distribution into a Normal Distribution? Name some techniques?**

Ans: I would use LogNormal, SquareRoot Transform, Reciprocal Transformation, Box-Cox Transformation & Yeo-Johnson Transformation

**5. How to perform Feature Engineering on Unknown features?**

Ans. I would be going with boosting techniques like AdaBoost, Gradient Boosting, XG-Boost.
