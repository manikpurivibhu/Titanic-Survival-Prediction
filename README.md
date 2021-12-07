# Titanic-Survival-Prediction

#### -- Project Status: [Active, On-Hold, Completed]
<br>

## Project Objective

Machine Learning Project which analyzes the Titanic survival dataset and uses Logistic Regression to predict if person would survive if they were on Titanic

&nbsp; &nbsp; &nbsp; &nbsp;

### Methods Used

* Machine Learning
* Data Visualization
* Predictive Modeling

&nbsp; &nbsp; &nbsp; &nbsp;

### License information

The work done in this project is made available under the Creative Commons Zero v1.0 Universal  License 

You are free to:

•	Share — copy and redistribute the material in any medium or format<br>
•	Adapt — remix, transform, and build upon the material.<br>

I have licensed this project for general public. The work done in this project is for learning and demonstration purposes. 
  
&nbsp; &nbsp; &nbsp; &nbsp;

## Libraries and Frameworks

•	Numpy – It provides a fast numerical array structure and operating functions.
 
 •	Pandas – It provides tools for data storage, manipulation and analysis tasks.
 
 •	Scikit-Learn – The standard machine learning library in Python.
 
 •  Matplotlib – It is the basic plotting library in Python, providing the necessary tools for plotting data.
 
 •  Seaborn – It is the advanced plotting library in Python. It provides clean and user friendly tools for making plots. 
 
 •  Pickle – It serializes the Machine Learning Model so that it need not be trained every time while in production. 
 
 &nbsp; &nbsp; &nbsp; &nbsp;
 
 ## Machine Learning Algorithm
 
 #### Logistic Regression
 
Logistic Reression is a Classification algorithm for categorical variables i.e. for predicting discrete values ({0, 1}, {True, False}, etc)<br><br>

The goal of a Logistic Regression model is to build a model to

- predict the class which the input sample case belongs to
- find the probability of input sample case belonging to a class

Logistic Regression passes the input through the logistic/sigmoid but then treats the result as a probability
 
 &nbsp; &nbsp; &nbsp; &nbsp;
 
 ## Evaluation Metrics
 
 * Jaccard Index - We can define jaccard as the size of the intersection divided by the size of the union of the two label sets.
 * Log Loss - Log-loss is indicative of how close the prediction probability is to the corresponding actual/true value (0 or 1 in case of binary classification). Mathematically, it is the negative average of the log of corrected predicted probabilities for each instance.
 * Confusion Matrix - Confusion Matrix is a (2 x 2) table that has the values

[[True Positive   False Positive]
 [False Negative  True Negative]]

* Accuracy - It is the proportion of correct predictions over total predictions
* Precision - It is the ratio tp/(tp+fp) where tp is the number of true positives and fp the number of false positives
* Recall is the ratio tp/(tp+fn) where tp is the number of true positives and fn the number of false negatives
* F-beta score can be interpreted as a weighted harmonic mean of the precision and recall, where an F-beta score reaches its best value at 1 and worst score at 0
* Support is the number of occurrences of each class in y_test
* ROC curve - Receiver operating characteristic curve is a graph showing the performance of a classification model at all classification thresholds.
This curve plots two parameters:<br>
1. True Positive Rate (TPR)  TPR = TP/(TP+FN)
2. False Positive Rate (FPR) FPR = FP/(FP+TN) 

* AUC - Area Under the ROC Curve measures the entire two-dimensional area underneath the entire ROC curve (think integral calculus) from (0,0) to (1,1)

&nbsp; &nbsp; &nbsp; &nbsp;

##  Interpretation and Conclusion

The accuracy of Logistic Regression is found to be 0.854. <br> 
So, the model is a <b>good fit</b> to the data. 

&nbsp; &nbsp; &nbsp; &nbsp;

## References:

*  Machine Learning notes by Andrew Ng
*  https://www.kaggle.com/mnassrib/titanic-logistic-regression-with-python/notebook
