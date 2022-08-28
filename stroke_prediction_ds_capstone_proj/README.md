# Data_Science_Nano_Degree_Capstone_Project
# Stroke Prediction using Machine Learning Models with Scikit-Learn and Pandas
 

## Installations
 - NumPy
 - Pandas
 - Seaborn
 - Matplotlib
 - Scikit-Learn
 
 
No additional installations were made beyond the distribution of Python and Jupyter notebooks.

## Project Motivation
For this Capstone project, I used various Machine Learning Models to predict the risk of Stroke amongst patients of various age and bio-metric details. 

In this project, I used the Stroke Prediction data set from kaggle, and performed the following steps in the process using Pandas, Scikit-Learn and Numpy:
* performed loading and cleaning of the data, 
* we explored the dataset to see the risk ratio , mutual info , corelation of various feature to the target variable. 
* we also prepared the data along the way, by converting datatypes to more suitable types, imputing values, and applying One-Hot encoding. 
* We then looked at various estimators to solve the binary classification problem of predicting the Stroke, viz. Random Forest, Support Vector Machine, Naive-Bayes, K-Nearest Neighbor and Logistic Regression. 
* We tuned the model and achieved an accuracy of 95% for both Random Forest and Support Vector Classifier. 
 

## File Descriptions
Apart from this ReadMe file, there is one exploratory notebook showing my approach for predicting the risk of Stroke in the patients. Markdown cells and comments were used throughout the notebook to explain the steps taken in the process.
And also CSV file which is a Stroke Prediction Dataset from Kaggle.

## Medium Blog Post 
The main findings of the code can be found at my Medium Blog post available [here](https://medium.com/@ashwinibhatt85/racial-predilections-of-sleep-apnea-a7772f8eee24) explaining the technical details of my project.
Random Forest & Support Vector Machine estimator were chosen to be the best models by evaluating Time taken, Score and accuracy metrics. The final models achieved an Accuracy score of 95%. 

## Licensing, Authors, Acknowledgements, etc.
I'd like to acknowledge Udacity for the project idea and workspace and @fedesoriano for providing this dataset for use.
