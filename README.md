# K-Nearest Neighbours
__K Nearest Neighbour (KNN)__ is a non parametric and lazy learning algorithm method used for classification and regression. Non parametric means that the dataset is distribution-free or having a specified distribution but with the distribution's parameters unspecified.

__Lazy algorithm__ mean sit does not need any training data points for model generation. All training data is used in the testing phase. This makes training faster and testing phase slower and costlier since it consumes more resources of your PC as the dataset increases.

KNN performs better with a lower number of features than a large number of features!

### How does the KNN algorithm work?
In KNN, K is the number of nearest neighbours. It is the core deciding factor. It is generally an odd number when the number of classes are 2. 

Simplest case of the algorithm: K = 1.

KNN has the following basic steps:
1. Calculate distance using eucledan distance.
2. Find closest neighbour.
3. Vote for labels.

### How do you decide the number of neighbours in KNN?
Using  Elbow method.

### Files in the repository
* __KNN_heart_disease.ipynb__ - In this file, I've analysed the dataset, then made the KNN model.
* __KNN_heart_improved.ipynb__ - In this file, I showed how to improve the accuracy of the KNN model.
* __Heart Disease folder__ - In this folder, the '.csv' extension file of the Heart disease dataset is present.
* __Breast Cancer folder__ - In this folder, the '.csv' extension file of the Breast cancer dataset is present.
