1. What are the different types of logistic Regression?

Ans: There are 3 types of logistic Regression and those are,
1. Binary logistic regression: There are just two possible outcome answers.
2. Multinomial logistic regression: There are more than two possible outcome answers.
3. Ordinal logistic regression : Ordinal logistic regression is also a model where there are multiple classes that an item can be classified as; however, in this case an ordering of classes is required. Classes do not need to be proportionate.
The distance between each class can vary. Example, Ranking restaurants on a scale of 0 to 5 stars.

2. What is the difference between the outputs of the Logistic Model and the Logistic function?

Ans: Logistic function is used to give probability which ranges from 0 to 1 whereas, Logistic Model tries to give us maximum log likelihood of a particular class

3. How do we handle categorical variables in Logistic Regression?

Ans: We perform one-hot,label encoding, target encoding techniques depending what that feature shows relation.

4. What are the assumptions made in Logistic Regression?

Ans: Multi-collinearity should not be there and the relation between log of odds & theata(i)x(i) should be linear

5. Why can’t we use MSE as a cost function for Logistic Regression?

Ans: If we use this cost function than it won't reach to global minima as already the data is non linear, after applying this cost function the non-linearity would more increase not only that it would get trapped in local minima. So thats the reason we don't go for MSE as a cost function. We go for log loss function when it comes to logistic regression.
