# CWRUBootcamp_M17_12082022_Credit_Risk_Analysi_Hoynacke

# Project Overview

Jill commends you for all your hard work. Piece by piece, you’ve been building up your skills in data preparation, statistical reasoning, and machine learning. You are now ready to apply machine learning to solve a real-world challenge: credit card risk.

Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. Therefore, you’ll need to employ different techniques to train and evaluate models with unbalanced classes. Jill asks you to use imbalanced-learn and scikit-learn libraries to build and evaluate models using resampling.

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, you’ll oversample the data using the RandomOverSampler and SMOTE algorithms, and undersample the data using the ClusterCentroids algorithm. Then, you’ll use a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. Next, you’ll compare two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk. Once you’re done, you’ll evaluate the performance of these models and make a written recommendation on whether they should be used to predict credit risk.

# Project Requirements 

This new assignment consists of three technical analysis deliverables and a written report. You will submit the following:

- Deliverable 1: Use Resampling Models to Predict Credit Risk.
- Deliverable 2: Use the SMOTEENN Algorithm to Predict Credit Risk.
- Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk.
- Deliverable 4: A Written Report on the Credit Risk Analysis (README.md).

# Deliverable 1: Use Resampling Models to Predict Credit Risk 

For all three algorithms, the following have been completed:
An accuracy score for the model is calculated
A confusion matrix has been generated
An imbalanced classification report has been generated 

## Oversampling

<img width="552" alt="Screenshot 2022-12-08 at 6 27 33 PM" src="https://user-images.githubusercontent.com/111096384/206588480-96c86fc9-5005-406b-bd96-bd68d9252fa5.png">

<img width="564" alt="Screenshot 2022-12-08 at 6 27 49 PM" src="https://user-images.githubusercontent.com/111096384/206588492-1fde5250-f033-4147-a964-341fdcb4491b.png">

## Undersampling

<img width="554" alt="Screenshot 2022-12-08 at 6 27 56 PM" src="https://user-images.githubusercontent.com/111096384/206588543-9d34f79c-5466-46ae-a580-a58763daf259.png">

## Combination (Over and Under) Sampling

<img width="562" alt="Screenshot 2022-12-08 at 6 28 02 PM" src="https://user-images.githubusercontent.com/111096384/206588557-714952d2-fec8-4550-8879-ccaf81f2c637.png">

# Deliverable 2: Use the SMOTEENN algorithm to Predict Credit Risk 

The combinatorial SMOTEENN algorithm does the following:
- An accuracy score for the model is calculated 
- A confusion matrix has been generated 
- An imbalanced classification report has been generated

<img width="552" alt="Screenshot 2022-12-08 at 6 27 33 PM" src="https://user-images.githubusercontent.com/111096384/206588741-38d3c7c8-5365-49e0-a6c7-16e1d7e4c061.png">

# Deliverable 3: Use Ensemble Classifiers to Predict Credit Risk 

The BalancedRandomForestClassifier algorithm does the following:
- An accuracy score for the model is calculated 
- A confusion matrix has been generated 
- An imbalanced classification report has been generated 
- The features are sorted in descending order by feature importance

<img width="963" alt="Screenshot 2022-12-08 at 7 07 30 PM" src="https://user-images.githubusercontent.com/111096384/206592927-c9608267-1f58-4ecb-9800-cbd140713780.png">

<img width="665" alt="Screenshot 2022-12-08 at 7 07 41 PM" src="https://user-images.githubusercontent.com/111096384/206592950-9b476fb2-3f2d-4d91-b01e-3f0e2b7e3f99.png">

The EasyEnsembleClassifier algorithm does the following:
- An accuracy score of the model is calculated 
- A confusion matrix has been generated 
- An imbalanced classification report has been generated

<img width="824" alt="Screenshot 2022-12-08 at 7 08 27 PM" src="https://user-images.githubusercontent.com/111096384/206593131-1cdd6957-9065-4b3d-87d4-9bbe18d51ce4.png">

<img width="824" alt="Screenshot 2022-12-08 at 7 08 27 PM" src="https://user-images.githubusercontent.com/111096384/206593156-163ce115-8a20-4a00-95cc-2f9b0675dccf.png">

# Deliverable 4: Analysis

Results:

Summary:

Recommendation:



  
