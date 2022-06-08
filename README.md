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
  
  ![This is an image]()
  
  
  - Confusion Matrix
  ![This is an image]()
  
  
  - Imbalanced Classification Report
  - Precision: 0.99
  - Recall: 0.62
  - F1: 0.76
  
  ![This is an image]()
  
  
- SMOTE Oversampling Model

  - Balanced Accuracy Score: 65.14%
  ![This is an image]()
  
  - Confusion Matrix
  ![This is an image]()
  
  
  - Imbalanced Classification Report
  - Precision: 0.99
  - Recall: 0.69
  - F1: 0.81

  ![This is an image]()
  
  
### Undersampling
- Cluster Centroids Model

 - Balanced Accuracy Score: 54.47%
 ![This is an image]()
 
 
 - Confusion Matrix
 ![This is an image]()
 
 
 - Imbalanced Classification Report
 - Precision: 0.99
 - Recall: 0.40
 - F1: 0.56

 ![This is an image]()
 
 
### Combination (Over and Under) Sampling
- SMOTEENN Model

- Balanced Accuracy Score: 65.50%
 ![This is an image]()
 
 
 - Confusion Matrix
 ![This is an image]()
 
 
 - Imbalanced Classification Report
 - Precision: 0.99
 - Recall: 0.56
 - F1: 0.71

 ![This is an image]()
 
 ### Ensemble
 In this approach, I compared two ensemble algorithms to determine which algorithm results in the best performance. This entailed training a Balanced Random Forest Classifier and an Easy Ensemble AdaBoost classifier.
 
- Balanced Random Forest Classifier
 
 - Balanced Accuracy Score: 78.85%
 ![This is an image]()
 
 
 - Confusion Matrix
 ![This is an image]()
 
 
 - Imbalanced Classification Report
 - Precision: 0.99
 - Recall: 0.87
 - F1: 0.93

 ![This is an image]()
 
- Easy Ensemble AdaBoost Classifier
 
 - Balanced Accuracy Score: 78.85%
 ![This is an image]()
 
 
 - Confusion Matrix
 ![This is an image]()
 
 
 - Imbalanced Classification Report
 - Precision: 0.99
 - Recall: 0.87
 - F1: 0.93

 ![This is an image]()
 
 ## Summary
 



