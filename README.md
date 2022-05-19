# Rms_titanic
The RMS Titanic was a British passenger liner that sank in the North Atlantic Ocean in the early morning hours of 15 April 1912, after it collided with an iceberg during its maiden voyage from Southampton to New York City. There were an estimated 2,224 passengers and crew aboard the ship, and more than 1,500 died, making it one of the deadliest commercial peacetime maritime disasters in modern history. 
In this project we do complete analysis of what sort of people were likely to survive.
We have been given data regarding the titanic disaster, and we have to predict survivability of some given passenger according to their data set.
# Main_Goals and  objectives of this project are as follows: 
To determine the surviving chances  we have given data regarding the titanic disaster, and we have to predict survivability of some given passenger according to their data sets and to learn from that disaster we try to find best survival chances 
The objective of this approach was to build a model that could successfully determine whether the passenger lived or died.
The objective of this approach was to determine which model would best fit for the given data set.
# Data  Analysis
The training-set has 12 columns , 5 int values ,  5 object type values, 2 floating type values.
The Training set has 891 examples and 11 features + the target variable(Survived).
While importing the data set we observe that Age has only 714 values, Cabin 204 values and Embarked 889 values :
5 of them are int64 type,
5 of them are object type,
2 of them are float64 type.
We would have to change the object features into numeric value to get a viable result from the machine learning algorithm.
We obtain the minimum age(0.42), maximum age(80), Highest number of Siblings and spouses were 8, only 38% people survived, minimum fare given was 0 while maximum fare given was 512 there were 3 passenger classes from 1-3, so we got an idea and approach of the data.
Hence, total number of missing values,like Cabin has 687 missing values and age has 177 missing values along with the percentage of the missing value.
# Training Different Machine Learning Models
After using 7 different machine learning models, 

•Logistic Regression

•K-Nearest Neighbors

•Classification

•Support Vector Classification with Linear Kernel

•Support Vector Classification with Radial Bayes Function Kernel

•Gaussian Naïve Bayes

•Decision Tree Classification

Random Forest Classification,The highest accuracy score we got was 90.91% with both Decision Tree Classification, and Random Forest Classification.After comparing the importance of features that amounts to the prediction. It is evident that sex, age and fare amounts more to the decision than embarked, but since all feature’s importance is more than 0.050 so, the model seems fine.

# Conclusion

The input data contained 891 rows and 11 features. First we used the existing data to analyse the relation of that data and how it would be useful for the prediction. And then we used the analysis to clean the data, removing features which are not useful to the prediction.
We created some more relevant features such as title and deck. We used the pre-existing data like ticket and name to extract and fill missing values of features such as cabin, which made it possible to create a useful feature deck.
We transformed raw data to categories to scale the highly irrelevant range for features like age and fare, which both amounted to top three important features for the prediction. We trained seven different models from Logistic Regression to Random Forest Classification to find out the best fitting model for this problem, and Random Forest returned the accuracy score of 90.91 and was found to be the best model for the problem.




