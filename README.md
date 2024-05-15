# Estimating obesity levels using machine learning

In the project, the classification problem of obesity level prediction is investigated using the dataset which contains eating habits and physical conditions in individuals from Colombia, Peru, and Mexico.

The dataset 

The dataset contains 7 classes:
1 – Insufficient_Weight,
2 – Normal_Weight,
3 – Obesity_Type_I,
4 – Obesity_Type_II,
5 – Obesity_Type_III,
6 – Overweight_Level_I,
7 – Overweight_Level_II

The first part of the project is the data visualization using histograms, scatter plots, and boxplots. In the second part, fore classification models were developed: Linear Regression, KNN, Decision Tree, and Support Vector Classifier.
For hyperparameter optimization, the Python grid search function was used. For the feature shrinkage, there were developed functions of the backward stepwise feature selection and visualization of a performance metric surface in the space of two hyperparameters: feature number and the most important hyperparameter. For performance analysis, accuracy, F1 score, and confusion matrix were used.
The first model obtained for each classifier assists in a better understanding of hyperparameter selection. Some of the hyperparameters do not significantly influence the performance. In the project, two algorithms of hyperparameter selection were used. The first algorithm was used for the logistic regression: error and F1 score vs the number of features were investigated. Using the obtained feature set, the other hyperparameter tuning was done. For the other three classifiers, the second approach was used. The first classifier was constructed for all the features, and using the grid the most significant hyperparameter was determined. The feature selection was provided in the space of the number of features and the hyperparameter.
KNN, Decision Tree, and Support Vector Classifiers have approximately the same performance, but Decision Tree’s performance is slightly higher. The analysis of confusion matrices shows that the Decision Tree classifier is the most efficient because it predicts all the classes well. For all the classifiers, the misclassifications belong to the neighbor classes, and all the classes are arranged in the weight ascending order and most likely can be neglected.

REFERENCES

[1] F. M. Palechor and A. de la Hoz Manotas,  “Dataset for estimation of obesity levels based on eating habits and physical condition in individuals from Colombia, Peru and Mexico,” Data in brief, 2019, Vol. 25, 2019, p.104344, doi: https://doi.org/10.1016/j.dib.2019.104344.
[2] N.V. Chawla, K.W. Bowyer, L.O. Hall, and W.P. Kegelmeyer, “SMOTE: synthetic minority over-sampling technique,” Journal of artificial intelligence research, 2002, Vol. 16, 321-357,
doi: https://doi.org/10.1613/jair.953.
[3] H. G. G. Bag, F. H.  Yagin, Y. Gormez, P. P. González, C. Colak, M. Gülü, G. Badicu, and L.P. Ardigò, “Estimation of obesity levels through the proposed predictive approach based on physical activity and nutritional habits,” Diagnostics, 2023, Vol. 13, no. 18, p. 2949,
doi: https://doi.org/10.3390/diagnostics13182949.
[4] R. Kaur, R. Kumar, and M. Gupta, “Predicting risk of obesity and meal planning to reduce the obese in adulthood using artificial intelligence,” Endocrine, 2022, Vol. 78, no. 3, p. 458-69,
doi: https://doi.org/10.1007/s12020-022-03215-4
[5] D. D. Solomon, S. Khan, S. Garg, G. Gupta, A. Almjally, B. I. Alabduallah, H. S. Alsagri, M. M. Ibrahim, and A. M. Abdallah, “Hybrid Majority Voting: Prediction and Classification Model for Obesity,” Diagnostics, 2023, Vol. 13, no. 15, p. 2610,
doi: https://doi.org/10.3390/diagnostics13152610.
[6] A. Geron, “Hands-on Machine Learning with Scikit-Learn, Keras and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems,” O’Reilly, 2022, 3rd ed.
