# KNN-CLASSIFIER


# As a simplified example of character recognition, we will investigate the potential forusing the very simple K Nearest Neighbour (KNN) classifier to predict whether an input image represents the handwritten digit 9 (nine) or 8 (eight). These digits were selected as they are quite similar to each other, both with a rounded upper part of the digit, but with very similar yet different bottom parts (the nine is like an almost complete eight, with a small gap missing on the left side). Note the data downloaded is already divided into training and testing datasets. It also includes data samples for all handwritten digits 0 to 9, but we will be using only 8 and 9 for this task. 

Python

import matplotlib.pyplot as plt
import numpy as np
import seaborn as sbn # better plotting and aesthetics
from pathlib import Path # just a utility for better cross-platform file-loading
from scipy.io import loadmat
from sklearn.neighbors import KNeighborsClassifier
specific functions of interest:
loading a .mat data file: loadmat
reshape to reshape a 3D matrix of 2D images into a decomposed 2D matrix
KNeighborsClassifier for training
predict for prediction
auc = sklearn.metrics.roc_auc_score(y_true=y1, y_pred=y2) for ROC area (AUC)


# 1: Build 20 KNN models with varying K=1,2,3,…..,20 in a loop. Provide a plot of testing error rate (as a percentage on the y axis) vs. K (x axis). Provide your python code. Provide the resultant plot. Answer the following questions:
## a. Why does testing error rise at high values of K?
## b. What is the error rate at the lowest K? Do you expect this to be a reliable performance estimate? Why? 

# 2: Describe the dataset you have collected: total number of samples, total number of measurements, brief description of the measurements included, nature of the group of interest and what differentiates it from the other samples, sample counts for your group of interest and sample count for the group not of interest. Write a program that analyzes each measurement individually. For each measurement, compute the area under the receiver operating characteristic curve (AUC). Provide an output of the 10 leading measurements (highest AUC), making it clear what those measurements represent in your dataset (these are the measurements with the most obvious potential to inform prediction in any given machine learning algorithm), and what their corresponding AUC values are. Provide this code.

# 3: Adapt your code from 1 to be applied to the dataset that you’ve organized for yourself. You will need to first randomize your samples into training and testing subsets, so that you can train your machine learning model as you did in 1 – this only needs to be done once for this task (no repeat validation is required at this time, just a single randomization of your samples into training and testing groups). Provide the resultant plot and your code. Answer the following question: is the profile of K vs. test error rate similar or quite different to the digit recognition example of 1? Elaborate on those similarities/differences – what about your dataset may have contributed to what you observe in this plot? 