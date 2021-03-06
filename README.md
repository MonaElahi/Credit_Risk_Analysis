# Credit_Risk_Analysis

![git-hub](https://github.com/MonaElahi/Credit_Risk_Analysis/blob/397a07df0d83fde31d5a059c77da54cbfa777b2e/CoverImage.jpg)

# Overview

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, it required to employ different techniques to train and evaluate models with unbalanced classes and use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

# Description 

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once done, evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

# Results

Following are the results of 6 predictive models for high risk loans. 

### Balanced Random Forest
![git-hub](https://github.com/MonaElahi/Credit_Risk_Analysis/blob/b3173e4b004157700bb41dab5687a5210650be51/Results/Balanced%20Random%20Forest%20Classifier.PNG)
![git-hub](https://github.com/MonaElahi/Credit_Risk_Analysis/blob/179562c53440c4e460e8204d0829971533609806/Results+/RandonForest.PNG)

### Undersampling
![git-hub](https://github.com/MonaElahi/Credit_Risk_Analysis/blob/b3173e4b004157700bb41dab5687a5210650be51/Results/Undersampling.PNG)
![git-hub](https://github.com/MonaElahi/Credit_Risk_Analysis/blob/e446f53047fc5e7b6fcfeafb8edeb69574bcd6b9/Results+/UnderSampling2.PNG)

### Oversampling
![git-hub](https://github.com/MonaElahi/Credit_Risk_Analysis/blob/b3173e4b004157700bb41dab5687a5210650be51/Results/Oversampling%20Accuracy.PNG)
![git-hub](https://github.com/MonaElahi/Credit_Risk_Analysis/blob/e446f53047fc5e7b6fcfeafb8edeb69574bcd6b9/Results+/OverSampling.PNG)

### Smote Oversampling
![git-hub](https://github.com/MonaElahi/Credit_Risk_Analysis/blob/b3173e4b004157700bb41dab5687a5210650be51/Results/Smote%20Oversampling.PNG)
![git-hub](https://github.com/MonaElahi/Credit_Risk_Analysis/blob/e446f53047fc5e7b6fcfeafb8edeb69574bcd6b9/Results+/Smote.PNG)

### Smoteenn
![git-hub](https://github.com/MonaElahi/Credit_Risk_Analysis/blob/b3173e4b004157700bb41dab5687a5210650be51/Results/Smoteenn.PNG)
![git-hub](https://github.com/MonaElahi/Credit_Risk_Analysis/blob/e446f53047fc5e7b6fcfeafb8edeb69574bcd6b9/Results+/SMOTEENN2.PNG)

### Easy Ensemble Adaboost
![git-hub](https://github.com/MonaElahi/Credit_Risk_Analysis/blob/b3173e4b004157700bb41dab5687a5210650be51/Results/Easy%20Ensemble%20Adaboost%20Classifier.PNG)
![git-hub](https://github.com/MonaElahi/Credit_Risk_Analysis/blob/e446f53047fc5e7b6fcfeafb8edeb69574bcd6b9/Results+/EnsembleAdaBoost.PNG)


# Summary

It is optimal requirement of credit lending company to predict credit risk, for that matter six models have been employed to access High-Risk applications.
From results above, accuracy score for four models Undersampling, Oversampling, Smote Oversampling and Smoteenn is approx. 65% and other Balanced Random Forest at approx. 72%
Finally Easy Ensemble Adaboost yielded 92% with high recall percentage. 

To recommend best model is depends on which gives model maximum accuracy and in this case _Easy Ensemble AdaBoost_ would be best technique to employ. 
