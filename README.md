Naive Bayes Classification with Laplacian Correction
Overview
This project evaluates the performance of the Naive Bayes algorithm on the Pima Diabetes dataset using Weka. It specifically compares standard classification against results using Laplacian Correction to handle probability estimation.
+2

Dataset Summary

Relation: pima_diabetes 
+1


Instances: 768 
+1


Attributes: 9 (8 numeric features + 1 nominal class) 
+1


Class Distribution: 500 tested_negative, 268 tested_positive 

Classification Results
1. Standard Naive Bayes
Accuracy: 76.30% (586 correctly classified instances)

Mean Absolute Error (MAE): 0.2841

ROC Area: 0.819

2. Naive Bayes with Laplacian Correction
Accuracy: 75.39% (579 correctly classified instances)

Mean Absolute Error (MAE): 0.2811

ROC Area: 0.818

Key Findings
Probability Refinement: While overall accuracy slightly dipped, the Mean Absolute Error (MAE) improved (decreased) with Laplacian correction.

Stability: The ROC Area remained consistently high (~0.82), indicating strong model discriminative power regardless of the correction.
