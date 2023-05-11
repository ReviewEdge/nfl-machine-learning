# nfl-machine-learning
### Inference Task
Predict whether a given play will be a pass or run, epxloring different synthetic features and feature crosses to improve effectiveness
### Method
Decision Tree
### Instructions
All notebooks currently have their outputs displayed, but if you would like to run the code yourself, you can download the dataset from Kaggle here: \
https://www.kaggle.com/datasets/maxhorowitz/nflplaybyplay2009to2016 \
Use the csv titled 'NFL Play by Play 2009-2018 (v5),' and rename it to 'nflData.csv'.
### Credit
The primary source I referenced was a project by Brandon Donelan, predicting play type for the Cleveland Browns: https://www.kaggle.com/code/gnarlyinsights/nfl-analysis-predicting-play-type \
I used his work as general outline for the process of creating a decision tree with Sklearn.  I referenced his data cleaning techniques, though he was using an older version of the dataset and had constrained his inference task specifically to the Browns, so there were significant differences in the cleaning process.  Additionally, I based my rushing and passing quarterly means synthetic feature off of a similar feature that he created in his project.

