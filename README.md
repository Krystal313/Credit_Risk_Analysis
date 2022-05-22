# Credit_Risk_Analysis

## Project Overview
In this project, we will use supervised machine learning model to analysze the credit risk prediction. After spliting the data into two sets: training and testing, we use the following methods to get the accuracy score, confusion matries and classification report for prediction and determine which model(s) to use:

1. Naive Random Oversampling
2. SMOTE Oversampling
3. Cluster Centroid Undersampling
4. SMOTEENN Sampling
5. Balanced Random Forest Classifier
6. Easy Ensemble AdaBoost Classifier

## Results
Below are the results of accuracy score, low risks and high risks of precision and recall for each model:

###### 1. Naive Random Oversampling
![Random Oversampling](https://github.com/Krystal313/Credit_Risk_Analysis/blob/22d8d8c4a686d519561275fb3ad99af9393af32e/Results/Random%20Oversampling.png)

- Accuracy Score: 62%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 60%
- Recall Low Risk: 65%

###### 2. SMOTE Oversampling
![SMOTE Oversampling](https://github.com/Krystal313/Credit_Risk_Analysis/blob/22d8d8c4a686d519561275fb3ad99af9393af32e/Results/SMOTE%20Oversampling.png)

- Accuracy Score: 65%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 64%
- Recall Low Risk: 66%

###### 3. Cluster Centroid Undersampling
![Undersampling](https://github.com/Krystal313/Credit_Risk_Analysis/blob/22d8d8c4a686d519561275fb3ad99af9393af32e/Results/Undersampling.png)

- Accuracy Score: 51%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 59%
- Recall Low Risk: 43%

###### 4. SMOTEENN Sampling
![Combo Sampling](https://github.com/Krystal313/Credit_Risk_Analysis/blob/22d8d8c4a686d519561275fb3ad99af9393af32e/Results/Combo%20Sampling.png)

- Accuracy Score: 51%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 59% 
- Recall Low Risk: 43%

###### 5. Balanced Random Forest Classifier
![Balanced Classifier](https://github.com/Krystal313/Credit_Risk_Analysis/blob/22d8d8c4a686d519561275fb3ad99af9393af32e/Results/Balanced%20Classifier.png)

- Accuracy Score: 78%
- Precision High Risk: 4%
- Precision Low Risk: 100%
- Recall High Risk: 67% 
- Recall Low Risk: 91%

###### 6. Easy Ensemble AdaBoost Classifier
![Ensemble Classifier](https://github.com/Krystal313/Credit_Risk_Analysis/blob/0fd83a6d60debd677d71d601e3d751b5b63bd74b/Results/Ensemble%20Classifier.png)

- Accuracy Score: 93%
- Precision High Risk: 7%
- Precision Low Risk: 100%
- Recall High Risk: 91% 
- Recall Low Risk: 94%

