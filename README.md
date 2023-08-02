This assignment deals with prediction of if the project will get the funding on the Donor's choose dataset.
The size of the Dataset is 100,000 datapoints
Donors choose dataset is regarding if the school project will get the funding in the different schools of USA.
This dataset is binary classification with 10 different features. The class label is either project got approved or not.

Naive Bayes algorithm is used for the prediction on this dataset. First, preprocessing and data cleaning is done. The textual data is converted through tfidf and BOW. Numerical data was normalised.

Metric used was AUC score. After hyperparameter tuning, AUC on BOW vectorised data is 0.6975 and on tfidf data is 0.6258
