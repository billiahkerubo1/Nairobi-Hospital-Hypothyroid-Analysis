# Nairobi-Hospital-Hypothyroid-Analysis

This is an analysis on whether or not the patient's symptoms indicate that the patient has hypothyroid. The first procedure is to import the necessary libraries such as pandas , numpy and sklearn. The next process is loading the data, understanding it and do the necessary data cleaning such as removing duplicates and dealing with missing values, if any. The next thing is to explore data to understand its distribution,and statistical summaries. Univariate and bivariate analysis are important because they help get a clearer understanding of the data, especially using visualization.

After exploring data, the classification of the data is carried out. In this case, the algorithms used for classification are random forests, adaboosted trees and gradient boosted trees. The metrics of success used are confusion matrix, RMSE and accuracy score. Other procedures that aided the process are cross-validation and hyperparameter tuning. The accuracy scores obtained were above 80% for every algorithm, making them both good for classification.

However, I would prefer using the gradient boosting algorithm because its accuracy is flexible with the number of estimators. The more the number of estimators, the higher the accuracy! While using the SVM, I would use the rbf algorithm because of the transformations on the C and gamma hyperparameters to improve accuuracy of the model.


PROJECT INSTALLATION Data analysis was conducted on Google Colab using pandas and numpy libraries.

Setup Requirements: The analysis was done using Google Colab.

Technologies used: The libraries used are Python Pandas, numpy, seaborn and matplotlib and Sklearn.

Known bugs: No known bugs

CREDITS The credits go to Moringa School Data Science Technical Mentors for guiding me through and teaching me the skills for data analysis. The skills learnt in class were applied in creating this project. CONTACT DETAILS user email : kbmenyenya@gmail.com You can contact me through the given email for any enquiries or contributions. COPYRIGHT Copyrigt(C) Moringa School Data Science
