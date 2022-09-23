*1. Explain One-Hot Encoding and Label Encoding. Does the dimensionality of the dataset increase or decrease after encoding, if yes then how?*

Ans: <ins>One Hot Encoding</ins> : Here,for each category of a feature, we create a new column (sometimes called a dummy variable) with binary encoding (0 or 1) to denote whether a particular row belongs to this category. This encoding technique we also call as Dummy Variable Trap. It increases the dimensionality of the dataset.

<ins>Label Encoding</ins> : we replace the categorical value with a numeric value between 0 and the number of classes minus 1. If the categorical variable value contains 4 distinct classes, we use (0, 1, 2, 3). This Label encoding is done in ascending order of alphabets of a class. Its disadvantage is that it tries to bring relationship in the dataset whereas there was no relationship with th different classes. It doesnot increase dimensionality ofthe dataset

*2. What is Target Encoding and how it is different from one hot encoding?*

Ans: features are replaced with a blend of posterior probability of the target given particular categorical value and the prior probability of the target over all the training data. It doesnot increases dimensionality of the dataset where one-hot encoding does Moreover, Target Encoding is a good fit when you have many classes in a feature.

*3. If you have a date column in our dataset, then how will you perform Feature Engineering in pandas?*

Ans: Depends what kind of feature engineering you are performing. firstly will convert it into pandas datetime format..then would start accessing by its day of the month, month, hour, dayname etc.

*4. How do you perform feature selection with Categorical Data?*

Ans: I would go for Chi-Square test or IG(mutual information) to perform feature selection when i have categorical data.

*5. When would you remove Correlated Variables?*

Ans: when in a dataset 2 or more independent variables show correlation in that case you should remove correlated variables this concept is called Multi-collinearity.
