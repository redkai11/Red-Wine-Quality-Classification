# Red-Wine-Quality-Classification

# Objective
The main objective of this project is to predict the quality of red wine using classification machine learning algorithms. 

# Description 
* Explore for outliers in the dataset
* Visualize the distribution of each feature and perform appropriate transformation to fix the skewness
* Use SMOTH oversampling technique to fix the imbalanced dataset
* Compare the performance of base models of Random Forest Classifier and Support Vector Machine
* Hyperparameter tune the Random Forest Classifier

I also tried to reduce the dimension of the features both in linear way and non-linear way using PCA, KernelPCA, and T-SNE.
It turns out that it was best to keep all the given features instead of performing dimension reduction.

The dataset was obtained from https://www.kaggle.com/uciml/red-wine-quality-cortez-et-al-2009
The dataset includes 

Input variables (based on physicochemical tests):

1 - fixed acidity

2 - volatile acidity

3 - citric acid

4 - residual sugar

5 - chlorides

6 - free sulfur dioxide

7 - total sulfur dioxide

8 - density

9 - pH

10 - sulphates

11 - alcohol

Output variable (based on sensory data):

12 - quality (score between 0 and 10)


# Credits 
Credits to the author of https://github.com/DTrimarchi10/confusion_matrix/blob/master/cf_matrix.py for the implementation of make_confusion_matrix function used in the project.
