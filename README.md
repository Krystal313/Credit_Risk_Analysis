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

###### Naive Random Oversampling
![Random Oversampling](https://github.com/Krystal313/Credit_Risk_Analysis/blob/22d8d8c4a686d519561275fb3ad99af9393af32e/Results/Random%20Oversampling.png)

- Accuracy Score: 62%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 60%
- Recall Low Risk: 65%

###### SMOTE Oversampling
![SMOTE Oversampling](https://github.com/Krystal313/Credit_Risk_Analysis/blob/22d8d8c4a686d519561275fb3ad99af9393af32e/Results/SMOTE%20Oversampling.png)

- Accuracy Score: 65%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 64%
- Recall Low Risk: 66%

###### Cluster Centroid Undersampling
![Undersampling](https://github.com/Krystal313/Credit_Risk_Analysis/blob/22d8d8c4a686d519561275fb3ad99af9393af32e/Results/Undersampling.png)

- Accuracy Score: 51%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 59%
- Recall Low Risk: 43%

###### SMOTEENN Sampling
![Combo Sampling](https://github.com/Krystal313/Credit_Risk_Analysis/blob/22d8d8c4a686d519561275fb3ad99af9393af32e/Results/Combo%20Sampling.png)

- Accuracy Score: 51%
- Precision High Risk: 1%
- Precision Low Risk: 100%
- Recall High Risk: 59% 
- Recall Low Risk: 43%

###### Balanced Random Forest Classifier
![Balanced%20Classifier](ttps://github.com/Krystal313/Credit_Risk_Analysis/blob/22d8d8c4a686d519561275fb3ad99af9393af32e/Results/Balanced%20Classifier.png)

###### Easy Ensemble AdaBoost Classifier
