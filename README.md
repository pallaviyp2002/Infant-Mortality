This project aims to develop a machine learning model to predict infant mortality using various healthcare and socio-economic features. 
The goal is to leverage predictive analytics to identify at-risk infants and provide timely interventions to improve survival rates.



Introduction
Infant mortality is a critical public health issue. Predictive analytics using machine learning can help identify factors contributing to infant mortality and predict outcomes based on healthcare data. 
This project employs various machine learning algorithms to predict infant mortality and aims to provide insights that can guide healthcare policies and practices.

Dataset
The dataset used in this project includes various features such as:

Birth details :
 Body Temperature
 Oxygen level
 Body Weight
 Breath rate
 Heart rate
 Blood Pressure
 Jaundice

 The importance of a child to a mother is the same as that of the child to that mother. The main purpose of this project is to keep them both healthy.

 The work involved pre-processing raw data to ensure its suitability for implementing Random Forests [RF] algorithms. Subsequently, after analysing the data, relevant features were extracted to facilitate Machine Learning algorithm. The models was trained and evaluated using appropriate performance metrics to ensure accuracy and reliability. This workflow is designed to provide accurate and efficient fetal health monitoring, enabling healthcare providers to intervene promptly if necessary and ultimately improve pregnancy outcome. This model further enhance the systems capabilities to meet the evolving needs of pregnant women and their healthcare providers.

 Results
The random forest algorithm was applied to predict the important factors in infant mortality data. Infant heart rate, Oxygen level of the infant, blood pressure and body temperature of the infant are the important factors considered in our project to predict the infant mortality risk factor.
All predictive models of mortality were applied to training data of 70% with all factors. The models were tested on test data of 30%. The performance of predictive models will be
 

evaluated and compared using various metrics namely confusion matrix, sensitivity, specificity, precision, accuracy, F1 score, negative predictive value.
We are using random forest model to find the risk factors or important features that had a major contribution to the mortality of infant. We are using the information gain rank method of random forest to check feature importance concerning its predictive power.
At the end of the project, the results are expected to show the accuracy of 94% for the random forest algorithm and F1 score of 0.460.


