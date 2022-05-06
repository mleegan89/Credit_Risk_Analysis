# Credit_Risk_Analysis

## Overview

The purpose of this analysis was to employ different techniques to train and evaluate models in order to predict credit risk. In order to best determine this, we used 6 different models using the same dataset. 

## Results

The below screenshots depict the performance (accuracy, recall, and precision) of all six machine learning models used. 

RandomOverSampler

<img width="415" alt="image" src="https://user-images.githubusercontent.com/96085210/167131685-5e915a79-3e38-4ff2-b804-96f131fcf6fb.png">

SMOTE

<img width="343" alt="image" src="https://user-images.githubusercontent.com/96085210/167131722-cb4c7f30-e0b9-41a3-b949-4d9e23b9885f.png">


ClusterCentroids

<img width="329" alt="image" src="https://user-images.githubusercontent.com/96085210/167131764-2ba962c7-f1c4-456d-a5e9-84da75b1bd62.png">


SMOTEENN

<img width="344" alt="image" src="https://user-images.githubusercontent.com/96085210/167131813-96e72c03-af2b-4275-8255-9eb50eacdde1.png">


BalancedRandomForestClassifier

<img width="344" alt="image" src="https://user-images.githubusercontent.com/96085210/167131925-dc4da053-5916-4837-ba87-d5557ebec468.png">


EasyEnsembleClassifier

<img width="349" alt="image" src="https://user-images.githubusercontent.com/96085210/167131962-d976400d-9274-4e08-b40d-cfe3e82fcaea.png">

## Summary

Looking at the above results, using the EasyEnsembleClassifier model would prove to yield the best results for this particular analysis. The F1 score is the highest when predicting high risk loans/credit risk. For this use case we want to have the model that does the best job predicting who will be the highest risk, not who will be the lowest risk. 
