# UCI-Adult-Income-prediction

An individual’s annual income results from various factors. Intuitively, it is influenced by the individual’s education level, age, gender, occupation, and etc.

***Number of Instances:*** 32561<br>
***Number of attributes:*** 15<br>
***Target filed:*** Income (The income is divide into two classes: <=50K and >50K)<br>
***Problem definition:*** Predicting income level based on the individual’s personal information.<br>
<br>
***Acknowledgements***<br>
This dataset named “adult” is found in the UCI machine learning repository<br>
http://www.cs.toronto.edu/~delve/data/adult/desc.html<br>
<br>
The detailed description on the dataset can be found in the original UCI documentation<br>
http://www.cs.toronto.edu/~delve/data/adult/adultDetail.html<br>
<br>
***Solution***<br>
<br>
***1. UCI_Adult_Income_Classification.ipynb***<br>
 - Implemented a tree model using scikit learns DecisionTreeClassifier API (which uses CART algorithm).<br>
 - Used K-Fold cross validation with Grid search to find the optimal hyper-parameters for the decision tree.<br>
 - Resulting model had a AUC-ROC of 0.90 with the train and test accuracny of 0.8

