# Data Preprocessing

**Dataset-** Data.csv
**columns-** country, age, salary, purchased

**Data Preprocessing** is imp for all ML & DS Algorithms.
### 	Step 1- import lib.
use numpy, matplotlib.pyplot, pandas
### 	Step 2- import dataset (use pandas)
once, we import dataset, we need to differ between matrix of feature and dependent variable vector.
### 	Step 3- Missing Data(use imputer)
idea 1- remove those observations - can be harmful
idea 2- take mean/median of all observations of that column & put replace missing variable with this value
Can be done using **Imputer**
### 	Step 4- encode categorical data
ML works with numeric data and equations. Thus need to encode categories into numerical value.
use **Label Encoder** & **Dummy Encoding** based on case that presents.
### 	Step 5- split dataset into train & test set
Train model on training set & validate its accuracy on test set.
### 	Step 6- feature scaling(using standard scaler)
If variable not in same scale, may cause issue in ML modals as algorithms are based on euclidean distance(many more available).
This would cause Model to be dominated by only 1 feature, also it helps to converge models faster. 
