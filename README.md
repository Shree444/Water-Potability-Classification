# Water-Potability-Classification

This project contains the code for Pre-Processing the Dataset and applying various Classification Algorithms to find the best accuracy producing model using Python3, JupyterNotebook. 

In this study we employ a small dataset collection using data on various characteristics of drinking water to identify its potability. 
The output given models will help us determine the most potable or drinkable water. 

Dependency Libraries:
```
* Python 3
* pandas
* numpy
* scipy
* scikit-learn
* matplotlib
* seaborn
* jupyter notebook
```
   
Project Outline:
```
- Data Preparation
- Data Wrangling
- Data Exploration
- Model Development
- Model Evaluation and Refinement
```

Pre Processing Steps Followed:
```
1. Identifying Null Values.
2. Filling the Null Values with the Mean values of its corresponding feature.
3. For each feature, identifying Outliers.
4. Outliers Treatment using IQR Method for each feauture.
```
Machine Learning Steps Followed:
```
1. The required libraries are imported.
2. Tha Dataset is read in Jupyter Notebook.
3. Correlation Matrix is formed.
4. Dropping columns that doesn't affect the output variable.
  -No such columns are found.
5. Train, Test Split is done.
6. Feature Scaling is performed.
7. Fitting the model to various Classification Algorithms such as 
  -Decision Tree
  -Random Forest
  -SVM
  -Naive Bayes
  -KNN
  -Logistic Regression
8. Performance metrics of each of the algorithm is found.
9. Comparision Bar Graph is plotted using the Accuracy metrics of each algorithm.

```
# From the comparision we can find that Random Forest Classification gives the best accuracy score of 69.27%.
