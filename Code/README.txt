***  K-Nearest Neighbor  ***
1. Specify the value for 'K' on line 144
2. Specify the value for K-Fold Cross Validation on line 145
3. Specify the file_name on which you want to run KNN on line 141 
4. Now run 'knn_classification.py' python code and you can see the classification accuracy, precision, recall and f_measure


*** Naive Bayes Classifier ***
1. Specify the value for K-Fold Cross Validation on line 261
2. Specify the file_name on which you want to run Naive Bayes Classification Algorithm on line 258 
3. Now run 'naive_bayes_classification.py' python code and you can see the classification accuracy, precision, recall and f_measure


*** Executing the DecisionTreeApi, RandomDecisionForest, Boosting files:  *** 

a) In each of these files, the main method calls two helper functions viz. withCrossValidation(); and withoutCrossValidation();
b) Comment out the corresponding helper function if you do not wish to execute it
c) Provide the file path using the static class variables defined in the files. Each of the helper functions uses these statc variables to access the input data file. So, modify the same as well accordingly in the helper functions. 

e.g. The withCrossValidation() method in RandomDecisionForest class uses the DATA_2_PATH class variable. Rename it to DATA_1_PATH for using the "project3_dataset1.txt" file.