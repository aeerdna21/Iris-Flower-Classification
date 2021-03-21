# Iris-Flower-Classification



In this mini-project I tried to follow the workflow with neural networks for classify iris flowers, having at my disposal a predefined model offered by the Scikit-Learn library. It will be used an easy multiclass classification dataset. This data set consists of 3 classes (**Setosa**,  **Versicolor** and **Virginica**) and for each class, there are 150 samples. The set is described by 4 types of features: *sepal length (cm)*,	*sepal width (cm)*,	*petal length (cm)*,	*petal width (cm)*. First, the k-Nearest Neighbors algorithm will be used, and then other algorithms will be tested to compare the performance.

![alt text](https://miro.medium.com/max/1400/1*uo6VfVH87jRjMZWVdwq3Vw.png)

## CONTENT
  1. [ Data Import](#1) <br>
  2. [ Data Preparation](#2)<br>  
  3. [ Data Splitting](#3)<br>    
  4. [ Choosing the Model -KNN](#4)<br>
  5. [ Fitting the Model](#5)<br>
  6. [ Model Evaluation](#6)<br>
  7. [ Saving the Model ](#7)<br>
  8. [ Other Algorithms](#8)<br>
     8.1 [ Logistic Regression](#8.1)<br>
     8.2 [ Decision Tree](#8.2)<br>
     8.3 [ Random Forest](#8.3)<br>
     8.4 [ Linear SVM(Suport Vector Machines)](#8.4)<br>
     8.5 [ Kernel SVM(Suport Vector Machines)](#8.5)<br>
  9. [ Comparison Between Algorithms](#9)<br>
<br>
<br>
## Brief description of the used algorithms 
### K - NEAREST NEIGHBORS
:cherry_blossom: the simplest algorithm used to classify images <br>
:cherry_blossom: is considered a *lazy learner* because it does not learn a discriminatory function from the training data, it only memorizes the whole training data set <br>
:cherry_blossom: from a technical point of view, it does not train a model <br>
:cherry_blossom: the algorithm classifies each data point according to the closest examples found in the most common classes

<img src="https://www.kdnuggets.com/wp-content/uploads/rapidminer-knn-image1.jpg" width="400" height="300">
<br>
<br>
<br>

### LOGISTIC REGRESSION
:cherry_blossom: a statistical model that in its basic form uses a logistic function (sigmoid function) <br>
:cherry_blossom: logistic regression can be binomial (the outcome can have 2 states: 0 or 1), ordinal( multiple variables that are ordered) or multinomial (unordered variables) <br>
:cherry_blossom: uses relationship between the dependent variable and independent variables by estimating the best probabilities or chances of occurrence <br>

<img src="https://www.equiskill.com/wp-content/uploads/2018/07/WhatsApp-Image-2020-02-11-at-8.30.11-PM.jpeg" width="500" height="300">
<br>
<br>
<br>

### DECISION TREE
:cherry_blossom: the algorithm asks a series of questions about the data set until a conclusion is formed <br>
:cherry_blossom: the set of possible questions and answers is organized in the form of a decision tree which is a hierarchical structure consisting of nodes and directional edges <br>
<img src="https://static.javatpoint.com/tutorial/machine-learning/images/decision-tree-classification-algorithm.png" width="500" height="300">
<br>
<br>
<br>

### RANDOM FOREST
:cherry_blossom: the algorithm consists of a set of decision trees <br>
:cherry_blossom: each individual tree in the random forest provides a class prediction, and the class with the most votes becomes the prediction of the entire model <br>
:cherry_blossom: the higher the number of trees, the better prediction <br>
:cherry_blossom: if the correlation between the trees is small, the predictions will be more accurate  <br>
<img src="https://miro.medium.com/max/1184/0*KhIFjUN6V8p8WqL1.png" width="500" height="300">
<br>
<br>
<br>

### LINEAR SVM
:cherry_blossom: finds a hyperplane between data between two classes <br>
:cherry_blossom: the algorithm searches for the nearest line points -> suport vectors <br>
:cherry_blossom: is calculated the *margin*=the distance between the support vectors and the hyperplane <br>
:cherry_blossom: the hyperplane for which the margin is maximum => optimal hyperplane <br>

![image](https://user-images.githubusercontent.com/81037426/111915824-caee6480-8a80-11eb-9b0c-f416019b1120.png)
<br>
<br>
<br> 

### KERNEL SVM
:cherry_blossom: the algorithm operates with kernel functions <br>
:cherry_blossom: Kernel function generally transforms the training set of data so that a non-linear decision surface is able to transformed to a linear equation in a higher number of dimension spaces <br>
:cherry_blossom: the algorithm is able to find a decision surface that clearly divides between different classes <br>
:cherry_blossom: the most popular kernel functions are the polynomial kernel and the radial basis function (RBF) kernel <br>
![image](https://miro.medium.com/max/3600/1*mCwnu5kXot6buL7jeIafqQ.png)


