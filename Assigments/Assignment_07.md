Assignment 7
1. How sci-kit learn module performs feature scaling?

Ans: Things go well when it comes to 1-d array but when having multi-Dimensional array it doesnot gives correct results so its important when performing feature scaling we should specify axis parameter so it performs correctly.

2. If you are performing feature scaling, what you will prefer Standardisation or Normalization?

Ans: Depends what kind of data we are bringing to the scale if its numeric or tabular dataset i would go with Standarization so i quickly reach global minima using GD Algorithm whereas if i m working on images there i need to convert image range from 0 to 255 there i will use normalization.

3. What is the difference between the residual sum of squares and regularization?

Ans: residual is nothing but difference between actual and predicted values and we are squaring it regularization term is generally used to solve overfitting issue where we add slope square with RSS or mod of slope with RSS depends on what we need to perform.

4. Differentiate between L1, L2, and Elastic Net regularization on the basis of the alpha parameter in scikit learn?

Ans: Elastic Net uses the combination of L1 and L2 wherein you give the ratio of alpha parameter if alpha = 0 then its L2 regularization if alpha = 1 then its L1. Elastic net moves from L2 --> L1

5. Suppose overfitting is happening, what kind of regularization you will prefer to perform?

Ans: If the model is too complex in that case i would go for L1 regularization orelse i would use L2 Regularization..it depends would try to test with both and see.
