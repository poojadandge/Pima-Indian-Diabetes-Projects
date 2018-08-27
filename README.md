# Pima Indians Diabetes Project

The project was aimed to build a model to predict if a person is diabetic or not based on his medical diagnostics. The experiment was conducted using the pima Indians diabetics data. Numerous issues were present in the data including impossible values and missing values. These issues were handles appropriately by imputing class average in most of the cases. Normalization of the variables were applied on the data. A thorough analysis of the features was conducted and the most important features were selected for building the models. Different models like KNN, decision trees and Random forest were built on the data. Due to the issue of data imbalance, oversampling using SMOTE was also tried on KNN model. But it was later found that the oversampling is actually overfitting the data and the model will not be useful. Important features were identified from the random forest model and the new data set was made using only the important features. Comparison of the models were also done and found that random forest model gave the best results. Parametric tuning was also performed on all the models. Random search grid was applied on the decision tree and the random forest model to tune the parameters. Even though the parametric tuning didn’t have much effect on the random forest model it had a 3.75% improvement on the decision tree model. Cross validation was applied on all the models and Random Forest model was found to be more stable than any other model in the experiment with a 10-fold cross validation accuracy of 87.11%.
#### --- Dataset
This data set has been retrieved from Github.
The original source of the dataset is from the National Institute of Diabetes and Digestive and Kidney Diseases.



## 2> Portuguese Banking Institution - Data Preprocessing and Data Exploration

The aim of this project is to load a data file into memory, clean, process, and analyse it and gives practical experience with the typical first steps of the data science process.
The data is related to direct marketing campaigns of a Portuguese banking institution.
The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be (`yes') or not (`no') subscribed. 
