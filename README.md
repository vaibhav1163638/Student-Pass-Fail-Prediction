# Student-Pass-Fail-Prediction

## Conclusion

In this project, we built a classification pipeline to predict student pass status using Logistic Regression.

We compared seven different techniques for handling missing values:

1. Mean Imputation
2. Median Imputation
3. Most Frequent Imputation
4. K-Nearest Neighbors (KNN) Imputation
5. MICE (Multiple Imputation by Chained Equations)
6. Row Removal
7. Random Imputation

All models used the same train-test split, preprocessing structure, feature scaling, and Logistic Regression algorithm. The main difference between the models was the missing-value handling technique.

After evaluating the models on the test dataset, the results were compared using accuracy. For this particular dataset and model configuration, the different missing-value handling techniques produced similar classification results.

This project demonstrates how different missing-value handling techniques can be integrated into a machine learning workflow and evaluated using a consistent classification model.
