# Credit-Card-Fraud-Detection
Practical use of classification models for credit card fraud detection.

The performance results were the following:

Model | Accuracy | AUC | False negatives | False positives | Speed
----- | -------- | --- | --------------- | --------------- | -----
Logistic Regression | 99.94% | 0.85 | 26 | 7 | Fast
K-Nearest Neighbor (KNN) | 99.96% | 0.90 | 17 | 3 | Slow
Decision Trees | 99.93% | 0.87 | 21 | 17 | Fast
Support Vector Machines (SVM) | 99.96% | 0.87 | 21 | 4 | Slow

According to the results, KNN offers the best performance, outperforming the other models in AUC, false negatives and false positives. The only problem is the high processing capacity it requires, which implies a longer time to obtain the result.

In terms of performance vs. speed, logistic regression is the most balanced, offering good results almost immediately.
