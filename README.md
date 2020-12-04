# MSBD5012-Kaggle-Competition
 Evaluation This competition is the individual project of MSBD 5001.
 The individual project counts for 20% of the final grade. It's supported by the smart city project of iSingLab (Smart City).  Description The dataset provides the average traffic speed per hour for a major road in Hong Kong from 2017 to 2018. Part of the dataset is provided as the training data, and your task is to predict the rest. 80% of the dataset is provided as the training data and 20% as the testing data, including the timestamp and the corresponding average speed. We sampled the testing data only from the year 2018 to provide you a training dataset that has the complete data spanning the year 2017. However, the speed information is sometimes missing due to device malfunction.  
 You have to submit the predicted results of these testing samples, which are then compared with the ground truth to evaluate the performance of your model.
 
 Requirements:

- python 3
- python libraries
- numpy
- pandas
- matplotlib
- re
- urllib
- bs4
- time
- datatime
- sklearn
- xgboost.sklearn

Files:
- ip5001.ipynb is the code to run to generate my final submission 
- mytest.csv is the final prediction results on testing data
- train.csv is the training data
- test.csv is the testset without speed
- hongkong.csv is the weather information of hong kong between 2017 to 2018

Usage:
- Need to connect to the network because crawler is implemented in the code.
- With required packages set down, put all files into one directory, run the code directly from top to bottom.
- It takes some time to finish the whole process, too much calculation, so not that fast.
- After running all the code, you can get the prediction results on testing data, which is the same as my uploaded one

