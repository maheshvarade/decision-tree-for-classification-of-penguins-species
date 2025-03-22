🐧 Decision Tree for Classification of Penguin Species
This project implements a Decision Tree Classifier to classify different species of penguins using the Palmer Penguins dataset. The dataset contains features such as bill length, bill depth, flipper length, and body mass to predict the species (Adelie, Chinstrap, or Gentoo).

📌 Key Features & Workflow
Exploratory Data Analysis (EDA) 🔍

Handled missing values

Feature correlation using a heatmap

Feature Engineering & Scaling ⚖

Decision Tree Classification 🌳

Implemented using sklearn.tree.DecisionTreeClassifier

Visualized decision boundaries and tree structure

Model Evaluation 📊

Accuracy Score: 97%

   precision    recall  f1-score   support

           0       1.00      0.95      0.97        40
           1       1.00      1.00      1.00        29
           2       0.89      1.00      0.94        17

    accuracy                           0.98        86
   macro avg       0.96      0.98      0.97        86
weighted avg       0.98      0.98      0.98        86


Hyperparameter Tuning 🔧
The criterion='gini' parameter in DecisionTreeClassifier specifies that the Gini Impurity will be used to measure the quality of splits in the decision tree.

