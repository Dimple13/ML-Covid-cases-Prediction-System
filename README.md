# ML-Covid-cases-Prediction-System
By Dimple Nachnani-45, Tina Rajpal-50, Shreya Shah-59 of D12C, VESIT(2020-2021).
# Description of our project
The Coronavirus Disease-2019 (COVID-19) pandemic persists to have a mortifying impact on the health and well-being of the global population. A continued rise in the number of patients testing positive for COVID-19 has created a lot of stress on governing bodies across the globe and they are finding it difficult to tackle the situation. We have developed an outbreak prediction system for COVID-19 which will predict the cases of a particular region given the data of past days.We have implemented a total of 6 machine learning algorithms for prediction of various aspects.These predictions will also help the hospitals in management of the cases in an efficient way.The data can also be used by normal people to see the risk of covid disease by prediction.Thus, these models can be of great help to all aspects of the society.
# Algorithms
## 1.Decision Tree Classifier <br>
The goal of using a Decision Tree Classifier is to create a training model that can use to predict the class or value of the target variable by learning simple decision rules inferred from prior data.We have used this as a classification algorithm for predicting if a person has covid given their age, their medical history and their area population and cases.Thus, we have taken age-group,medical history and area population and cases as the input parameters in the dataset and we are determining the covid positivity of a person as the output.<br>
## 2.KNN<br>
K-nearest neighbors (KNN) algorithm uses ‘feature similarity’ to predict the values of new datapoints which further means that the new data point will be assigned a value based on how closely it matches the points in the training set.We have used this supervised learning algorithm for finding clusters of a particular age and area having covid.Here, we have considered the age and cases in the area as the input parameter and we are determining the covid positivity of a person as the output.<br>
## 3.KMeans<br>
Kmeans algorithm is an iterative algorithm that tries to partition the dataset into K pre-defined distinct clusters where each data point belongs to only one group. It tries to make the intra-cluster data points as similar as possible while also keeping the clusters as different as possible.We have used this unsupervised learning algorithm for finding clusters of population having similar number of covid cases.Here, we have considered the population and cases as the input parameter and we get the clusters as the output.<br>
## 4.Naive Bayes<br>
Naive Bayes algorithm is the algorithm that learns the probability of an object with certain features belonging to a particular group/class. It is basically a probabilistic classifier.We have used this as a classification algorithm for predicting if a person has covid given their age-group, their medical history and their area populationa nd cases.Thus, we have taken age-group,medical history and area population and cases as the input parameters in the dataset and we are determining the covid positivity of a person as the output.<br>
## 5.Regression<br>
Polynomial regression is a form of regression analysis in which the relationship between the independent variable x and the dependent variable y is modelled as an nth degree polynomial in x.This algorithm has been used for predicting the number of cases that will be recorded in the next few days after monitoring the cases of a region for 50 consecutive days.We have considered the days as the input and using that we are predicting the number of cases in the next few days as the output.<br>
## 6.SVM<br>
A support vector machine (SVM) is a supervised machine learning model that uses classification algorithms for two-group classification problems.We have used this supervised learning algorithm for finding clusters of a particular age and area having covid.Here, we have considered the age and cases in the area as the input parameter and we are determining the covid positivity of a person as the output.<br>
# Datasets<br>
Kindly refer the Github csv files in the repository for complete dataset.<br>
# Implementation<br>
Kindly refer the Github files in the repository for complete implementation details of all the algorithms.<br>
# Results and accuracy<br>
For the individual results and accuracy kindly refer individual notebook files.<br>
Comparing the accuracy of KNN and SVM we see that for our dataset, SVM performed better with an accuracy of 92.3% and KNN had an accuracy of about 80%.<br>
Comparing the accuracy of Naive Bayes and Decision Tree Classifier, We observe that for the same dataset, Naive bayes performed better with an accuracy of almost 88.89% whereas the decision tree classifier had an accuracy of 77.79%.<br>
# Conclusion<br>
Thus our system,when extended on real data, will help in prediction of covid cases location wise like zone,district,state,country which will help the hospitals and government to predict the cases.Also,the predictions made with the help of various algorithms will be useful for the management authorities and doctors to recognize the steps to be taken in future to handle the patient influx.Thus, this system can be useful to people and doctors in managing the current vicious spread of covid cases.
