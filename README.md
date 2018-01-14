# PredStackOverflowTags
Classification of tags for StackOverflow questions using SVM based machine learning models

#  Classifiers employed
Scikit-Learn library implementation for the following classifiers was used:

• LinearSVC

• SVC with Linear kernel

• Stochastic Gradient Descent (SGD)


# Dataset

All the data used is available in form of a Creative Commons Data dump at Intenet-Archive (https://archive.org/details/stackexchange). 
From this sanitized dump of available data, I have used the Posts and Tags data available for stackoverflow.com. The entire Posts dataset contains a set of 45K tags spread across 37M questions in a 56GB .XML formatted file. 

Posts.xml obtained from the dump is the master-collection of all the questions with the format as illustrated in "sample.xml"
