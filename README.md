# Titanic-Survival-Challenge
A model based on data collected to predict whether a given passenger will survive or not.

Dataset Consist of two files "Train.csv" and "Test.csv" train the model on 'Train.csv' and predict the output on 'Tets.csv'.

Various Columns in the dataset are:

survival-      Survival           0 = No, 1 = Yes

pclass-        Ticket class   1 = 1st, 2 = 2nd, 3 = 3rd

sex-                  Sex   

Age-                Age in years   

sibsp-        # of siblings / spouses aboard the Titanic  

parch-       # of parents / children aboard the Titanic  

ticket-        Ticket number   

fare-         Passenger fare  

cabin-         Cabin number   

embarked-    Port of Embarkation    C = Cherbourg, Q = Queenstown, S = Southampton

This problem has been solved by the comcept of Random Forest.

Various approaches are used for its solution:

1. A single Decision Tree (Max Acc Achieved : 81.71)
2. A single Decision Tree from Sklearn Library (Max Acc Achieved : 82.83)
3. A random forest with optimal number of Decision Trees (Max Acc Achieved : 83.95)
