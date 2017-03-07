# ML 2017 HW 1.

## Decision Trees and Random Forests


__Question 1: Accuracy vs Interpretability.__
Describe real-world prediction problems where interpretability is preferable to accuracy, vice versa. 

__Question 2: Build a Decision Tree by hand to classify records.__
Build a decision tree using only numpy and pandas. No sklearn. 

For this assingment I completed the following: 
- Defined functions to calculate the: 
    1. most common value in the data set
    2. entropy
    3. information gain
    4. best split 
- Split the data 
- Created a decision tree 

__Question 3: Use Sklearn models to predict burden of disease.__

For this assignment I completed the following: 

- Train/test split data and choose hyper-parameter 
- Fit decision tree with different hyper-parameter values
- Plot AUC score vs model simplicity (max leaf nodes)
- Cross validated data using GridSearchCV

__Question 4: Fit a Random Forest to data from Question 3.__

For this assignment I completed the following: 

- Train/test split data and choose hyper-parameter 
- Fit Random Forest with data
- Compare AUC score with Decision Tree accuracy
