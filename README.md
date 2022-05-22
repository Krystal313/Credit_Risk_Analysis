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
- Precision Score(High Risk): 1%
- Precision Score(Low Risk): 100%
- Recall Score(High Risk): 60%
- Recall Score(Low Risk): 65%

###### 2. SMOTE Oversampling
![SMOTE Oversampling](https://github.com/Krystal313/Credit_Risk_Analysis/blob/22d8d8c4a686d519561275fb3ad99af9393af32e/Results/SMOTE%20Oversampling.png)

- Accuracy Score: 65%
- Precision Score(High Risk): 1%
- Precision Score(Low Risk): 100%
- Recall Score(High Risk): 64%
- Recall Score(Low Risk): 66%

###### 3. Cluster Centroid Undersampling
![Undersampling](https://github.com/Krystal313/Credit_Risk_Analysis/blob/22d8d8c4a686d519561275fb3ad99af9393af32e/Results/Undersampling.png)

- Accuracy Score: 51%
- Precision Score(High Risk): 1%
- Precision Score(Low Risk): 100%
- Recall Score(High Risk): 59%
- Recall Score(Low Risk): 43%

###### 4. SMOTEENN Sampling
![Combo Sampling](https://github.com/Krystal313/Credit_Risk_Analysis/blob/22d8d8c4a686d519561275fb3ad99af9393af32e/Results/Combo%20Sampling.png)

- Accuracy Score: 51%
- Precision Score(High Risk): 1%
- Precision Score(Low Risk): 100%
- Recall Score(High Risk): 59% 
- Recall Score(Low Risk): 43%

###### 5. Balanced Random Forest Classifier
![Balanced Classifier](https://github.com/Krystal313/Credit_Risk_Analysis/blob/22d8d8c4a686d519561275fb3ad99af9393af32e/Results/Balanced%20Classifier.png)

- Accuracy Score: 78%
- Precision Score(High Risk): 4%
- Precision Score(Low Risk): 100%
- Recall Score(High Risk): 67% 
- Recall Score(Low Risk): 91%

###### 6. Easy Ensemble AdaBoost Classifier
![Ensemble Classifier](https://github.com/Krystal313/Credit_Risk_Analysis/blob/0fd83a6d60debd677d71d601e3d751b5b63bd74b/Results/Ensemble%20Classifier.png)

- Accuracy Score: 93%
- Precision Score(High Risk): 7%
- Precision Score(Low Risk): 100%
- Recall Score(High Risk): 91% 
- Recall Score(Low Risk): 94%

## Summary 
Based on the analysis, we can see the all six model have close score for precision high risk between 1 - 7% and low risk at 100%. However, as we compare the accuracy scores of all models, we can say that Easy Ensemble AdaBoost Classifier would be the best model to use in this case given the high accuracy score of 93% with the other  five models are all below 80%. In addition, it also has the highest recall percentage of 91% for high risk and 94% for low risks. 
