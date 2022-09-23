1. What are the different validation techniques in Machine Learning?

Ans: Train/test split, k-Fold Cross-Validation, Leave-one-out Cross-Validation, Leave-one-group-out Cross-Validation, Nested Cross-Validation

2. What are the different ways of improving the accuracy of a Machine Learning Model?

Ans: Add more data samples, Look at the problem differently, Add some context to your data, Finetune your hyperparameter, Train your model using cross-validation ,Experiment with a different algorithm

3. What is stratified cross-validation and when should we use it?

Ans: In the case of class imbalances in particular, to use stratified 10-fold cross-validation, which ensures that the proportion of positive to negative examples found in the original distribution is respected in all the folds

4. What is the difference between the validation set and the holdout test set?

Ans: Validation sent is used multiple times whereas holdout dataset will be used to final evaluate the model

5. How to solve a multi-class classification problem vs multi-label classification available?

Ans: To solve this kind of problem i will use softmax activation function at the last layer for multi-class classification and if i m doing multi-label classification i would go multiple sigmoids on the last layer and thus learn a separate distribution for each class
