# Predicting Penguin Species


**Introduction and Background Information**

The goal of this project is to determine which features are most predictive of penguin species and build and optimize a machine learning model that predicts penguin species.

**Python Packages**

- pandas 1.4.2
- numpy 1.21.5
- urlib
- seaborn 0.11.2
- pyplot from matplotlib 3.5.1
- train_test_split, cross_val_score, preprocessing, RandomForestClassifier, SVC, LogisticRegression, confusion_matrix from sklearn 1.0.2

**Exploratory Data Analysis**

<img width="370" alt="Screen Shot 2023-04-07 at 11 05 28 PM" src="https://user-images.githubusercontent.com/108093223/230706248-f485ec34-3d90-44d0-af45-6944db09c4a3.png">

Our final visualization shows that island, culmen length, and culmen depth are the best predictive features to use in our model.

**Modeling**

A number of models were created including, the random forest classifier, support vector machines, and multinomial logistic regression. 

- Random Forest Classifier:
  -  Best depth: 9
  -  Score: 0.9545
- Support Vector Machine (SVM): 
  -  Best gamma: 1
  -  Score: 0.9545 
- Multinomial Logistic Regression (MLR)
  - Best C: 2.5
  - Score: 0.9394

**Conclusions and Recommendations**

We recommend both the Support Vector Machines Model with Island, Culmen Length (mm), and Culmen Depth (mm) or the Random Forest Model with Island, Culmen Length (mm), and Culmen Depth (mm). We recommend both of these models because they both had the highest accuracy (95.45%) in combination with these features. They both produce the same number of mistakes when analyzing their confusion matrices and decision plot regions. If more data were available for our project, we could have potentially increased the accuracy of our models even further as there would be more entries for our models to get trained on. Likewise, the study would also greatly benefit from different kinds of data being available: if there were more features to look at, we have a higher chance of finding a feature(s) more suited to distinguishing different species. For example, we could even include behavioral data like diet, mating patterns, etc. 

