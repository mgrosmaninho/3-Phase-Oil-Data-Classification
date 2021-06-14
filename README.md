# 3-Phase-Oil-Data-Classification
Coursework from University of Hertfordshire

## Overview
The data that I have been given is the 3 phase oil dataset. Archive of this dataset can be found at http://inverseprobability.com/3PhaseData.html. This 12-dimensional dataset is from a physics-based simulation of a non-invasive monitoring system, used to determine the quantity of oil in a multi-phase pipeline containing a mixture of oil, water and gas. The whole dataset includes 3 classes, which are homogeneous, annular and laminar (stratified) namely. The configurations of the flow in the pipe are shown in the following figure.

<img width="561" alt="Screenshot 2021-06-14 at 11 23 40" src="https://user-images.githubusercontent.com/50143720/121878057-2e480580-cd03-11eb-92b2-3488f7870fd8.png">

I have been given two data files. One includes the training set, named trndata.csv, and the other one, tstdata.csv, includes the test data. The last column of each file is the class label indicating the configuration of the flow in the pipe: a value of 1 denotes homogeneous, a value of 2 denotes annular, and a value of 3 denotes laminar.

The training set I have been given consists of 1000 instances, 343 labeled as 1, 316 labeled as 2 and 341 labeled as 3. This set can be treated as a balanced dataset. The test set is also balanced, and contains 300 instances. You can assume that the data is of satisfactory quality and requires no preprocessing / data cleansing other than normalisation.

To classify the data I will be using Support Vector Machines (SVMs). The type of SVM I need to use is the C-SVC (Cost-Support Vector Classifier) and the kernel function I should use is the Gaussian radial basis function (RBF).

## Contact me!
For more information about this project, please email me at mgrosmaninho@hotmail.com
