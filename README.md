# Credit_Risk_Analysis

## Overview of the analysis
In order to understand credit card risk, we used machine learning to analyze the risk. We employed different techniques to train and evaluate models with unbalanced classes. We oversample the data using the RandomOverSampler and SMOTE algorithms and undersample the data using the ClusterCentroids algorithm. Then, we used a combinatorial approach of over-and undersampling using the SMOTEENN algorithm. Next, we compared two new machine learning models that reduce bias, BalancedRandomForestClassifier, and EasyEnsembleClassifier, to predict credit risk. 

## Results
- RandomOverSampler: the balanced accuracy score is 0.66 (0.6573009382322703), the precision score is 0.99, and the recall score is 0.6 thus results are not giving us a good prediction.    
![RandomOverSampler.png](/Resurcees/RandomOverSampler.png)
- SMOTE: the balanced accuracy score is 0.66 (0.6622479600626106), the precision score is 0.99, and the recall score is 0.69 thus being better than the RandomOverSampler results but still not giving us a good prediction.
![SMOTE.png](/Resurcees/SMOTE.png)  
- ClusterCentroids: the balanced accuracy score is 0.54 (0.5442661782548694), the precision score is 0.99, and the recall score is 0.4 thus is low comper to the RandomOverSampler results and the SMOTE results.
![ClusterCentroids.png](/Resurcees/ClusterCentroids.png)
- SMOTEENN: the balanced accuracy score is 0.64 (0.644711676499736), the precision score is 0.99, and the recall score is 0.57 thus is low comper to the RandomOverSampler results and the SMOTE results but better than the ClusterCentroids results.
![SMOTEENN.png](/Resurcees/SMOTEENN.png)
- BalancedRandomForestClassifier: the balanced accuracy score is 0.95 (0.644711676499736), the precision score is 0.99, and the recall score is 0.91 thus results are high and give us the best results so far.
![BalancedRandomForestClassifier.png](/Resurcees/BalancedRandomForestClassifier.png)  
- EasyEnsembleClassifier: the balanced accuracy score is 0.96 (0.9610313492761811), the precision score is 0.99, and the recall score is 0.95 thus results are high and give us the best results.    
![EasyEnsembleClassifier.png](/Resurcees/EasyEnsembleClassifier.png)

## Summary
We can see that the ensemble algorithms give us better results comper to the oversampling algorithms. 
The model that gives us the best accuracy score is the Balanced Random Forest Classifier but it is still not as high as we accepted so we are not recommending using any of the models above to predict credit risk. 