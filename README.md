# Expedia-hotel-recommedation
Expedia provided us the logs of customer behavior. These include what customers searched for, how they interacted with search results (click/book), whether or not the search result was a travel package. The data in this competition is a random selection from Expedia and is not representative of the overall statistics.

Expedia is interested in predicting which hotel group a user is going to book. Expedia has in-house algorithms to form hotel clusters, where similar hotels for a search (based on historical price, customer star ratings, geographical locations relative to city center, etc) are grouped together. These hotel clusters serve as good identifiers to which types of hotels people are going to book, while avoiding outliers such as new hotels that don't have historical data. Our goal of this competition was to predict the booking outcome (hotel cluster) for a user event, based on their search and other attributes associated with that user event. The train and test datasets are split based on time: training data from 2013 and 2014, while test data are from 2015. Training data includes all the users in the logs, including both click events and booking events. Test data only includes booking events. 

Execution Steps for decision tree algo:
1. Download and extract the train dataset. It will be extracted as train.csv
2. Run python expedia_decision_tree.py to run the algorithm
3. If you have to run on a dataset with smaller rows. Please changed line #164 to reflect the proper file name and run the algorithm using command given in 2.

Execution steps for SVM Algorithm

1. Download and extract the train dataset.
2. Move inside the directory where you downloaded "train.csv"
3. run python Multiclass-Svm.py

Execution steps for Softmax Algorithm

1. Download and extract the train dataset.
2. Move inside the directory where you downloaded "train.csv"
3. run python Softmax.py

Execution steps for Random Forest Algorithm
1. Download and extract the train dataset.
2. Move inside the directory where you downloaded "train.csv"
3. run python Random_forest_algorithm.py
4. Currently it is running for 5 clusters, if you need to run for 2 or entire clusters, comment code line # 290.


Execution steps for Naive Bayes Algorithm

1. Download and extract the train dataset.
2. Move inside the directory where you downloaded "train.csv"
3. Open the Ipython notebook - Naive Bayes Implementation.ipynb in Anaconda or use the NaiveBayes.py file to run the code. Ipthon notebook is preferred as the code was developed on it.
4. Run all the cells.
