# Anomaly-Detection

In the code i have run the following methods for anomaly detection:

#### 1 Angle-based Outlier Detector (ABOD)
#### 2 Histogram-base Outlier Detection (HBOS)
#### 3 K Nearest Neighbors (KNN)
#### 4 Average KNN
#### 5 Median KNN
#### 6 Local Outlier Factor (LOF)
#### 7 Minimum Covariance Determinant (MCD)
#### 8 One-class SVM (OCSVM)
#### 9 Principal Component Analysis (PCA)


I have run the outliers on all possible pairs of axes of data i.e., (1,2), (2,3) and (1,3)
and outliers are confirmed if for each label more than 4 methods have predicted it as an outlier.
finally if 2 or more than 2 pairs have predicted a data as outlier, then it is included in answer.



AKNOWLEDGEMENT :   I have used pyod library to get the things done
intallation :  pip install pyod
