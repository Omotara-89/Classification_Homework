# Classification_Homework

Brief Summary of Activity
The activity involved the use of all the skills learnt so far during the bootcamp, while focusing on classification and the use of various machine learning techniques to predict credit risk using data  typically seen from peer-to-peer lending services. The activity tested various knowledge in different techniques for training and evaluating models with imbalanced classes. The imbalanced-learn and Scikit-learn libraries was used to build and evaluate models using the two following techniques:
a.	Resampling and 
b.	Ensamble learning

a. Resampling
This exercise began by:
1.	Read the CSV into a DataFrame
2.	Split the data into Training and Testing sets.
3.	Scale the training and testing data using the StandardScaler from sklearn.preprocessing.
4.	Use the provided code to run a Simple Logistic Regression:
•	Fit the logistic regression classifier.
•	Calculate the balanced accuracy score.
•	Display the confusion matrix.
•	Print the imbalanced classification report
The item “4” above was repeated to determine the best accuracy score as well as other relevant scores. Below is a table showing the summary of the result
 
For this technique, the following questions were answered:
Which model had the best-balanced accuracy score? From the above, the oversampling model (Random and SMOTE) as well as the combination sampling has same accuracy score of 0.9934649587814939.
Which model had the best recall score? The under sampling has the best recall score at 0.994 as compared to the other models which have a recall score of 0.9934.
Which model had the best geometric mean score? From the tables above, all the models have the same geometric mean score.

b.	Ensamble Learning
The process above was used to determine the best accuracy score as well as other relevant scores. The summary of the result is shown in the table below:
 

For this technique, the following questions were answered:
Which model had the best-balanced accuracy score? The model with the best accuracy score is Easy Enambler Classifier because it gives the higher score of 0.93
Which model had the best recall score? The model with the best recall score is Easy Enambler Classifier because it gives the higher score of 0.94.
Which model had the best geometric mean score? The model with the best geometric mean score is Easy Enambler Classifier because it gives the higher score of 0.93
What are the top three features? The top three features are : total_rec_prncp, total_rec_int and total_pymnt.
