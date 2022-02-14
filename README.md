# MachineLearningProjects
## About
This repository is a collection of machine learning projects in python from this [tutorial](https://www.techwithtim.net/tutorials/machine-learning-python/introduction/)

### Linear Regression
Predicts student's final grade based on a series of attributes. Linear Regression is essentially just a best fit line. Given a set of data the algorithm will create a best fit line through those data points. In this case, the final grade is calculated from the previous grades. The dataset is from [here.](https://archive.ics.uci.edu/ml/machine-learning-databases/00320/)

### K Nearest Neighbors (KNN)
Classifies cars into 4 seperate categories. KNN is a machine learning algorithm used for classifying data. Rather than coming up with a numerical prediction such as a student's grade it attempts to classify data into certain categories. K-Nearest Neighbors works by looking at the K closest points to the given data point and picking the class that occurs the most to be the predicted value. This is why this algorithm typically works best when we can identify clusters of points. The dataset is from [here.](https://archive.ics.uci.edu/ml/datasets/Car+Evaluation)

### Scalable Vector Machines (SVM)
Classifies tumors as cancerous or benign from a breast cancer dataset from the python library sklearn. SVM's are typically used for classification tasks similar to K Nearest Neighbors. They work very well for high dimensional data and are allow for us to classify data that does not have a linear correspondence (not a line). 

### K Means Clustering
An unsupervised algorithm to classify hand written digits. It uses a digits dataset from sklearn. K Means clustering is an unsupervised learning algorithm that attempts to divide our training data into k unique clusters to classify information. This means this algorithm does not require labels for given test data. It is responsible for learning the differences between our data points and determine what features determining what class.
