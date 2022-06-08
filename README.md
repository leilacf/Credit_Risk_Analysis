# Credit_Risk_Analysis
## Overview
To analyze the statistical risk associated with credit loans, I worked with various supervised machine learning systems. In doing so, I evaluted the performance of these machine learning models that reduce bias, on whether they could predict credit risk. This was done hand-in-hand with LendingClub, a lending service that requested an analysis and assessment on credit card risk. 

As credit risk at its core is an unbalanced classification problem, varying techniques that will be outlined below, were used to train and evaluate the models, to determine which algorithm performed best. 

## Results
Below you will find an analysis on the 6 machine learning models used.

### Resampling
In this section I compated two oversampling algorithms to determine which algorithm results in the best performance. This entailed oversampling the data using the naive random oversampling algorithm and the SMOTE algorithm.

### Oversampling
- Naive Random Oversampling

  - Naive Random Oversamping Balanced Score: 64.03%
  
  ![This is an image](https://github.com/leilacf/Credit_Risk_Analysis/blob/main/Images/1random%20oversampling%20score.png)
  
  
  - Confusion Matrix
  
  ![This is an image](https://github.com/leilacf/Credit_Risk_Analysis/blob/main/Images/2confusion%20matrix.png)
  
  
  - Imbalanced Classification Report
  - Precision: 0.99
  - Recall: 0.62
  - F1: 0.76
  
  ![This is an image](https://github.com/leilacf/Credit_Risk_Analysis/blob/main/Images/3Imbalanced%20classification%20report.png)
  
  
- SMOTE Oversampling Model

  - Balanced Accuracy Score: 65.14%
  
  ![This is an image](https://github.com/leilacf/Credit_Risk_Analysis/blob/main/Images/4SMOTE%20balanaced%20accuracy%20score.png)
  
  - Confusion Matrix
  
  ![This is an image](https://github.com/leilacf/Credit_Risk_Analysis/blob/main/Images/5SMOTE%20confusion%20matrix.png)
  
  
  - Imbalanced Classification Report
  - Precision: 0.99
  - Recall: 0.69
  - F1: 0.81

  ![This is an image](https://github.com/leilacf/Credit_Risk_Analysis/blob/main/Images/6SMOTE%20report.png)
  
  
### Undersampling
- Cluster Centroids Model

 - Balanced Accuracy Score: 54.47%
 
 ![This is an image](https://github.com/leilacf/Credit_Risk_Analysis/blob/main/Images/7Cluster%20centroids%20score.png)
 
 
 - Confusion Matrix
 
 ![This is an image](https://github.com/leilacf/Credit_Risk_Analysis/blob/main/Images/8Cluster%20centroids%20confusion%20matrix.png)
 
 
 - Imbalanced Classification Report
 - Precision: 0.99
 - Recall: 0.40
 - F1: 0.56

 ![This is an image](https://github.com/leilacf/Credit_Risk_Analysis/blob/main/Images/9Cluster%20centroids%20report.png)
 
 
### Combination (Over and Under) Sampling
- SMOTEENN Model

  - Balanced Accuracy Score: 65.50%

  ![This is an image](https://github.com/leilacf/Credit_Risk_Analysis/blob/main/Images/10SMOTEENN%20balanced%20accurace%20score.png)
 
 
  - Confusion Matrix
 
  ![This is an image](https://github.com/leilacf/Credit_Risk_Analysis/blob/main/Images/11SMOTEEN%20confusion%20matrix.png)
 
 
   - Imbalanced Classification Report
   - Precision: 0.99
   - Recall: 0.56
   - F1: 0.71

   ![This is an image](https://github.com/leilacf/Credit_Risk_Analysis/blob/main/Images/12SMOTEENN%20report.png)
 
 ### Ensemble
 In this approach, I compared two ensemble algorithms to determine which algorithm results in the best performance. This entailed training a Balanced Random Forest Classifier and an Easy Ensemble AdaBoost classifier.
 
- Balanced Random Forest Classifier
 
 - Balanced Accuracy Score: 78.85%
 
 ![This is an image](https://github.com/leilacf/Credit_Risk_Analysis/blob/main/Images/13Random%20forest%20accuracy%20score.png)
 
 
 - Confusion Matrix
 
 ![This is an image](https://github.com/leilacf/Credit_Risk_Analysis/blob/main/Images/14Random%20forest%20confusion%20matrix.png)
 
 
 - Imbalanced Classification Report
 - Precision: 0.99
 - Recall: 0.87
 - F1: 0.93

 ![This is an image](https://github.com/leilacf/Credit_Risk_Analysis/blob/main/Images/15Random%20forest%20report.png)
 
- Easy Ensemble AdaBoost Classifier
 
 - Balanced Accuracy Score: 78.85%
 
 ![This is an image](https://github.com/leilacf/Credit_Risk_Analysis/blob/main/Images/16ADA%20boost%20accuracy%20score.png)
 
 
 - Confusion Matrix
 
 ![This is an image](https://github.com/leilacf/Credit_Risk_Analysis/blob/main/Images/17ADA%20confusion%20matrix.png)
 
 
 - Imbalanced Classification Report
 - Precision: 0.99
 - Recall: 0.87
 - F1: 0.93

 ![This is an image](https://github.com/leilacf/Credit_Risk_Analysis/blob/main/Images/18ADA%20report.png)
 
 ## Summary
 



