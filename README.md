# Credit_Risk_Analysis

# Overview #
The use of machine learning models to help predict analysis of credit card risk. Various techniques were used to train and test models. Algorithms and libraries used are listed below:

•	SciKit-Learn

•	Imbalanced-learn

•	RandomOverSampler

•	SMOTE algorithm

•	SMOTTEENN algorithm

•	BalancedRandomForestClassifier

•	EasyEnsembleClassifier


# Purpose #


Applying machine learning to help solve credit card risk challenge. With the help of using various algorithms and models to help predict credit risk. Logistic regression, decision tree, random forest, and support vector machine algorithms were implemented. After implementation, one must interpret those results from the listed list above. Evaluate pros and cons of each supervised learning algorithm. Define which supervised learning algorithm are best suited for given datasets. Once the baseline has been established use ensemble and resampling techniques to help improve the performance of the model. 


# Results #
See below six machine learning models indicating balanced accuracy, precision, and recall: 

Naive Random Oversampling

![Naive Random Oversampling](https://user-images.githubusercontent.com/111043588/212661629-5d5764a5-d8c8-436d-af20-ead49a35d009.png)

      ‒	Balanced Accuracy: 69%

      ‒	Precision: The precision is low for High-risk loans and is high for Low-risk loans.

      ‒	Recall: High/Low risk = .59 & .69


SMOTE Oversampling

![SMOTE Oversampling](https://user-images.githubusercontent.com/111043588/212661815-94d4bb90-939c-4250-b9ab-5bea9db1d9af.png)

      ‒	Balanced Accuracy: 63%

      ‒	Precision: The precision is low for High-risk loans and is high for Low-risk loans.

      ‒	Recall: High/Low risk = .64 & .63


Undersampling
![Undersampling](https://user-images.githubusercontent.com/111043588/212661858-56e4b776-5a52-4885-9d29-284fc262f215.png)
 
    ‒	Balanced Accuracy: 43%

    ‒	Precision: The precision is low for High-risk loans and is high for Low-risk loans.

    ‒	Recall: High/Low risk = .59 & .44


Combination Under-Over Sampling

![Combination Under-Over Sampling](https://user-images.githubusercontent.com/111043588/212661891-2ee8dfd4-8695-4737-bf38-272555df4a06.png)

     ‒	Balanced Accuracy: 55%

      ‒	Precision: The precision is low for High-risk loans and is high for Low-risk loans.

      ‒	Recall: High/Low risk = .68 & .55


Balanced Random Forest Classifier

![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/111043588/212661935-876fd072-ab28-4b0d-b5e0-7a2f9b2cf6d6.png)

      ‒	Balanced Accuracy: 78%

      ‒	Precision: The precision is low for High-risk loans and is high for Low-risk loans.

      ‒	Recall: High/Low risk = .67 & .91


Easy Ensemble AdaBoost Classifier

![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/111043588/212661978-7cd8c93f-ade4-40f3-b293-2bb15d1576b3.png)

 
      ‒	Balanced Accuracy: 92%

      ‒	Precision: The precision is low for High-risk loans and is high for Low-risk loans.

      ‒	Recall: High/Low risk = .91 & .94


# Summary #

The best results occurred from Easy Ensemble Classifier. This model generated the best results with a accuracy rate of 93% and a 7% precision rate for High Risk candidates.  The other models were less than 80% regarding the balanced accuracy. In terms of precision all of the models delivered similar results and were within the and within an applicable range. For the recall score, it should fall within 0 and 1 range, numbers closer to 1 indicate being the better model. In closing the EasyEnsemble AdaBoost Classifier shows the superior results making it the best machine learning model to use to continued additional credit card evaluation
