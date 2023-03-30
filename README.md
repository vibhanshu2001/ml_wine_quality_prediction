# ml_wine_quality_prediction
This is a Python code for analyzing a wine dataset. The code imports various libraries such as numpy, pandas, matplotlib, seaborn, and scikit-learn to perform different tasks such as data analysis, data visualization, and machine learning. The dataset used in this code is stored in a CSV file named 'data.csv'.
<br/><br/>
The data consists of 1599 rows and 12 columns. The code analyzes the data by displaying the descriptive statistics of the dataset using the describe() function and checks for any missing values in the dataset using the isnull() and sum() functions.
<br/><br/>
The code also creates visualizations using the seaborn library to show the count of wine quality levels and the relationship between the wine quality and volatile acidity, citric acid, and other features.
<br/><br/>
Finally, the code applies machine learning by using the Random Forest Classifier to predict wine quality. The dataset is split into training and testing sets using the train_test_split() function. The model's accuracy is evaluated using the accuracy_score() function.
<br/><br/>The accuracy of this model is 90%. I also attempted to train the model using logistic regression, but the accuracy was very low at 50%. Therefore, I opted to use the random forest algorithm for improved accuracy.
