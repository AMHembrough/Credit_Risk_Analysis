

# Overview of the analysis: 

The purpose of this analysis was to predict high risk loans using a credit card credit dataset from LendingClub, a peer-to-peer lending service company.

To do this, we employed 6 machine learning models.  
- First, we oversampled the credit card credit dataset using two algorithms, the RandomOverSampler and SMOTE.
- Next, we undersampled the same credit card credit dataset using the ClusterCentroids algorithm.  
- We then used a combinational approach of over- and undersampling using the SMOTEENN algorithm.  
- Lastly, we employed two machine learning models, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk.  

# Results

## RandomOverSampler

-	balanced accuracy score : 
0.6620175698580149

-	precision & recall
The high-risk precision is 1% which sensitivity of 72%.  The low risk precision is 100% with a sensitivity of 60%.  
![Figure 1: RandomOverSampler]( https://github.com/AMHembrough/Credit_Risk_Analysis/blob/main/Fig1.PNG)

## SMOTE
-	balanced accuracy score : 
0.6568196079430206

-	precision & recall
The high-risk precision is 1% which sensitivity of 61%.  The low risk precision is 100% with a sensitivity of 70%.  
![Figure 2: SMOTE]( https://github.com/AMHembrough/Credit_Risk_Analysis/blob/main/Fig2.PNG)

## ClusterCentroids
-	balanced accuracy score : 
0.6027679241263696

-	precision & recall
The high-risk precision is 1% which sensitivity of 61%.  The low risk precision is 100% with a sensitivity of 59%.  
![Figure 3: ClusterCentroids]( https://github.com/AMHembrough/Credit_Risk_Analysis/blob/main/Fig3.PNG)

## SMOTEENN
-	balanced accuracy score : 
0.6461148570422992

-	precision & recall
The high-risk precision is 1% which sensitivity of 72%.  The low risk precision is 100% with a sensitivity of 57%.  
![Figure 4: SMOTEENN]( https://github.com/AMHembrough/Credit_Risk_Analysis/blob/main/Fig4.PNG)

## BalancedRandomForestClassifier
-	balanced accuracy score : 
0.7885466545953005

-	precision & recall
The high-risk precision is 3% which sensitivity of 70%.  The low risk precision is 100% with a sensitivity of 87%.  
![Figure 5: BalancedRandomForestClassifier]( https://github.com/AMHembrough/Credit_Risk_Analysis/blob/main/Fig5.PNG)

## EasyEnsembleClassifier
-	balanced accuracy score : 
0.9316600714093861

-	precision & recall
The high-risk precision is 9% which sensitivity of 92%.  The low risk precision is 100% with a sensitivity of 94%.  
![Figure 6: EasyEnsembleClassifier]( https://github.com/AMHembrough/Credit_Risk_Analysis/blob/main/Fig6.PNG)

# Summary
Based on my analysis, I recommend using the EasyEnsembleClassifier machine learning model to predict high risk loans because it has the best combination of accuracy, precision and recall.  This particular learning model has an accuracy score of 93% which is far superior than the other 5 models.  

