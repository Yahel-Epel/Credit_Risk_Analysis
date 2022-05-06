# Credit_Risk_Analysis

## Overview of the analysis
In order to understand credit card risk, we used machine learning to analyze the risk. We employed different techniques to train and evaluate models with unbalanced classes. We oversample the data using the RandomOverSampler and SMOTE algorithms and undersample the data using the ClusterCentroids algorithm. Then, we used a combinatorial approach of over-and undersampling using the SMOTEENN algorithm. Next, we compared two new machine learning models that reduce bias, BalancedRandomForestClassifier, and EasyEnsembleClassifier, to predict credit risk. 

## Results
- RandomOverSampler: the balanced accuracy score is 0.66 (0.6573009382322703), the precision scores is 1.0 and recall scores is 0.6 thos results are not giving us a good predicct.  
![RandomOverSampler.png](/Resurcees/RandomOverSampler.png)
- SMOTE: the balanced accuracy score is 0.66 (0.6622479600626106), the precision scores is 1.0 and recall scores is 0.69 thos are better from the RandomOverSampler results but still not giving us a good predicct.  
- ClusterCentroids:  the balanced accuracy score is 0.54 (0.5442661782548694), the precision scores is 1.0 and recall scores is 0.4 thos are low comper to the RandomOverSampler resultsand the SMOTE results.
- SMOTEENN: the balanced accuracy score is 0.64 (0.644711676499736), the precision scores is 1.0 and recall scores is 0.57 thos are low comper to to the RandomOverSampler resultsand the SMOTE results but better then the ClusterCentroids results.
- BalancedRandomForestClassifier: the balanced accuracy score is 0.95 (0.644711676499736), the precision scores is 1.0 and recall scores is 0.91 thos results are high and give us the best results so far.  
- EasyEnsembleClassifier: he balanced accuracy score is 0.96 (0.9610313492761811), the precision scores is 1.0 and recall scores is 0.95 thos results are high and give us the best results.  


## Summary
