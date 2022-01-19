# Credit_Risk_Analysis

# Overview of the analysis
* The purpose of this analysis was to run different algorithms to predict different outcomes for our credit risk data. Each algorithm was evaluated with the balanced accuracy scores, to determine the best analysis algorithm.

# Results
* The algorithms used were broken down into two different categories: sampling and ensemble algorithms. Both .ipynb files containing the models and cleaning steps are attached to this repository. 


* The Balanced Accuracy Scores are as follows:

* Naive Random Oversampling
* Balanced Accuracy Score - 0.6463970560994359

* SMOTE Oversampling
* Balanced Accuracy Score - 0.6586230769943224

* Undersampling with ClusterCentroids
* Balanced Accuracy Score - 0.5442369453268994

* Combination (Over and Under) sampling
* Balanced Accuracy Score - 0.6664711051320287

* Balanced Random Forest Classifier
* Balanced Accuracy Score - 0.7885466545953005

* Easy Ensemble Classifier
* Balanced Accuracy Score - 0.9316600714093861


* The Classification Reports are as follows:

* Naive Random Oversampling
![naive_random](https://github.com/dwest85/Credit_Risk_Analysis/blob/main/markdownpics/naive_random.PNG)

* SMOTE Oversampling
![SMOTE](https://github.com/dwest85/Credit_Risk_Analysis/blob/main/markdownpics/SMOTE.PNG)

* Undersampling with ClusterCentroids
![centroids](https://github.com/dwest85/Credit_Risk_Analysis/blob/main/markdownpics/centroids.PNG)

* Combination (Over and Under) sampling
![overunder](https://github.com/dwest85/Credit_Risk_Analysis/blob/main/markdownpics/overunder.PNG)

* Balanced Random Forest Classifier
![random_forest](https://github.com/dwest85/Credit_Risk_Analysis/blob/main/markdownpics/random_forest.PNG)

* Easy Ensemble Classifier
![easy_ensemble](https://github.com/dwest85/Credit_Risk_Analysis/blob/main/markdownpics/easy_ensemble.PNG)

# Summary

* Based on the results of the Accuracy Scores and Classification Reports, I feel that both classifiers would be recommended for use, as the f1 scores were very high for the low-risk accuracy. I feel the ensemble algorithms would be best used for the credit risk assessment over the resampling algorithms.