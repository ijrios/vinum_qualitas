# Partial 2, second delivery - Vinum Qualitas


A wine producing company requires the development of a classifier in order to separate its variants according to a measure of quality. To do this, we have a database with 11 input variables and one output variable that assigns each sample to a quality measure from 3 to 8.

The database is available at the following link:

https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009

The company requires that an analysis be carried out and it is suggested which are the characteristics that are best associated with the quality of the wine and which is the best classification scheme. It is suggested to unite class 8 with 7 and 3 with 4. In this way, only classes 4 (inferior), 5 (medium), 6 (good) and 7 (superior) would be obtained.

To meet the requirements, the following must be done:

· Implement at least 2 classifiers (you can use the scykit-learn package).

· For the performance measures of the classifier, validation must be carried out by k-fold cross validation. Mean and standard deviation must be reported in these measures.

· Verify that there are no missing data and carry out some process of normalization or standardization of the data.

· For each classifier, a hyperparameter optimization process must be carried out.

· For each classifier, implement a feature selection process. The process must contemplate the complete scheme of normalization, selection of hyperparameters and selection of characteristics (it can be implemented in a pipeline).

· Produce a report in which a comparison of the results is described (showing the measures of performance both in the cross-validation and in the test set). Based on the data, select the best model for the classification problem worked. Indicate for which classes there is a better performance (measure F1 score by class and show the confusion matrix of the best model).

Deliver the code and the report (everything can be done in a Notebook).