# Adaboost
Forest Type Classification Using Adaboost


This Project was made following assignment for the course from Prof. Nicolò Cesa-Bianchi, Statistical Methods for Machine Learning, at University of Milan. 
For the forest type cover datasets, I created a classifier that uses decision stumps with AdaBoost metaalgorithm using to train several classifiers on the Forest Cover Type Dataset with a one vs all approach. A total of seven different binaty classifiers are trained, based on each of the categories of Forest Type Cover that are available on the database, then the classification performance for different values of the number of rounds in AdaBoost was studied using external cross-validation to evaluate its accuracy. It is found
in general, that the accura is better, using a large number iterations of AdaBoost,
usually, 10. Beyond that the accuracy usually gets worse
