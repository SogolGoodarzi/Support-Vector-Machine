# Support-Vector-Machine

### Introduction to SVM
In machine learning, support vector machines (SVMs, also support vector networks) are supervised learning models with associated learning algorithms that analyze data for classification and regression analysis. In addition to performing linear classification, SVMs can efficiently perform a non-linear classification using what is called the kernel trick, implicitly mapping their inputs into high-dimensional feature spaces.

When data are unlabelled, supervised learning is not possible, and an unsupervised learning approach is required, which attempts to find natural clustering of the data to groups, and then map new data to these formed groups. The support vector clustering algorithm, applies the statistics of support vectors, developed in the support vector machines algorithm, to categorize unlabeled data.

A support vector machine constructs a hyperplane or set of hyperplanes in a high or infinite-dimensional space, which can be used for classification, regression, or other tasks like outliers detection. Intuitively, a good separation is achieved by the hyperplane that has the largest distance to the nearest training-data point of any class (so-called functional margin), since in general the larger the margin, the lower the generalization error of the classifier. 

### SVM Algorithm
![image](https://user-images.githubusercontent.com/125180530/219161875-d5e277d4-65cb-4352-9990-a9564d37c4e9.png)

### Maximize the margin
![image](https://user-images.githubusercontent.com/125180530/219165182-309046c6-f23f-4ca2-a520-6b43c889b42a.png)

![image](https://user-images.githubusercontent.com/125180530/219165280-e7ba4009-fca7-4e72-a1f7-9668a26a4b0c.png)

![image](https://user-images.githubusercontent.com/125180530/219165371-37fdafd4-ae4e-4093-a3b0-cca905989527.png)

### Cross Validation
![image](https://user-images.githubusercontent.com/125180530/219165598-9c993ca4-ba5b-4fa1-a2c7-a8ee13ff1286.png)

![image](https://user-images.githubusercontent.com/125180530/219165698-760e48e5-dddd-41d2-b33b-cd69cf78ac7c.png)

###  Implementation of the algorithm for the Iris dataset
First of all, we loaded the Iris dataset. Then, we implemented SVM and used the One vs Rest method to plot and show areas of each class. In addition to showing the class's areas, we have reported train data accuracy, confusion matrix, and confidence matrix. 
