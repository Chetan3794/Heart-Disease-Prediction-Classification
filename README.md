
<h1 align="center"> 
Heart-Disease-Prediction-Classification </h1>
<h3 align="center"> AlmaBetter Verfied Project - <a href="https://www.almabetter.com/"> AlmaBetter </a> </h5>

<p align="center"> 

![image](https://user-images.githubusercontent.com/114068950/214820769-a267a654-bc48-4440-8de2-c5dba3cc5e1c.png)

<h2> :floppy_disk: Project Files Description</h2>

<p>This Project includes 1 colab notebook, 1 CSV file as well as 1 presentation pdf</p>
<h4>Executable Files:</h4>
<ul>
  <li><b>Heart_disease.ipynb
</b> - Includes all functions required for classification operations.</li>
</ul>

<h4>Input Files:</h4>
<ul>
  <li><b>data_cardiovascular_risk.csv</b> - The dataset acquired contain various information related to human body health as well as body condition. The information incorporates the data containing various classification based values as explain in the dataset.</li>
</ul>


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :book:Introduction</h2>
Cardiovascular Diseases (CVDs) proven to be the major reason for a large number of death in the entire world over the many years and has comes up as the most life-threatening issue, not only in Indian contingent  but in the entire world. So, there is a serious need for the accurate, reliable and adaptable system to predict such diseases in time for the precautionary measure. Machine Learning based algorithms as well as techniques have been applied to datasets for the analysis of large and complicated data. Many researchers, in recent years, were being using many machines learning algorithm to help the health care sector and the professionals in the analysis of heart-related diseases. Heart is one of the major body organs. Machine learning classification approach is one of the useful techniques in this field to predict the upcoming coronary heart disease (CHD) with the help of previously available data. The main objective of this project is to build a binary classifier model, which can predict whether a person will be at a 10-year risk of future coronary heart disease (CHD) on the basis medical history and other relevant information. This article mainly concentrates on the classification approach of machine learning as the data is nominal and continuous type.


<h2> :book: Problem Statement</h2>
The dataset acquired contain various information related to human body health as well as body condition. The information incorporates the data containing various classification based values as explain in the dataset. The main purpose of this project is to understand the dataset, visualize and prepare a classification based model to predict whether a person is prone to 10 year coronary heart disease or not. 

<h2> :book: Data Summery</h2>
Illustration of the some major data contained is given below:

* Sex : male / female ("M" or "F") 

* Age : Age of the person 

* Education : Education level of the person 

* is_smoking : whether the person is smoking or not (YES  or  No) 

* CigsPerDay: No. of cigarettes person used to have per day.

* BPMeds: whether the person taking medicine for Blood Pressure or not

* prevalentstroke: whether the person had heart stroke previously or not

* prevalenthyp: whether the person having prevalent hypertension issue or not

* Diabetes: whether patient having diabetic or not

* TotChol: total cholesterol level in the body of person

* sysBP: systolic blood pressure of person

* diaBP: diastolic blood pressure of person

* BMI: Body Mass Index of persons

* HeartRate: heart rate of the person

* Glucose : glucose level of the person

* tenyearchd : 10-year risk of coronary heart disease CHD 




![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


# :book:Approach:


**1] Raw Data Collection:**
The data collected from the source contains various information useful for the  analysis as well as for visualization purpose. There two ways one can utilize the data. By importing the data file into the system and then accessing by writing code for it or by directly mounting the drive.  

**2] Data Processing and Feature Engineering:**

* Dealing with missing values:

It checks whether our data contains any missing value is there or not, then it will replace it with the zero. In this article some column has missing values, so we will replace them by zero.

* Checking for duplicates

The given dataset does not contain any duplicate values

* Removing unnecessary features:

In the given model some the features are not relevant to 10-Year risk of CHD. The columns are education, id. Hence, we have dropped these columns for further analysis.



# :book:Steps involved:

**1] Exploratory data analysis:** 
Here, we wish to gain important statistical insights from our data and analyze the distribution of various attributes, correlations between attributes and target variables, and important quotas and proportions of categorical attributes.

**2]Training split of data**
We have considered the train size of the data to be 85% of total data set whereas test set will be covered with 5% of data
Various allgrithms used are as follows:

* DecisionTree Classifier
* RandomForestClassifier
* XGBoost Classifier
* Logistic Regression

# Logistic Regression:

Logistic regression is one of the most popular Machine Learning algorithms, which comes under the Supervised Learning technique. It is used for predicting the categorical dependent variable using a given set of independent variables. Logistic regression predicts the output of a categorical dependent variable. Therefore the outcome must be a categorical or discrete value. It can be either Yes or No, 0 or 1, true or False, etc. but instead of giving the exact value as 0 and 1, it gives the probabilistic values which lie between 0 and 1. Logistic Regression is much similar to the Linear Regression except that how they are used. Linear Regression is used for solving Regression problems, whereas Logistic regression is used for solving the classification problems. In Logistic regression, instead of fitting a regression line, we fit an "S" shaped logistic function, which predicts two maximum values (0 or 1).

The Logistic regression equation can be obtained from the Linear Regression equation. The mathematical steps to get Logistic Regression equations are given below:

We know the equation of the straight line can be written as:

![image](https://user-images.githubusercontent.com/114068950/214811862-8dafd95e-33b2-47f9-8f16-5153e7433289.png)

In Logistic Regression y can be between 0 and 1 only, so for this let's divide the above equation by (1-y):

![image](https://user-images.githubusercontent.com/114068950/214811895-f6992367-c859-41f2-87f0-dec59f012838.png)

But we need range between -[infinity] to +[infinity], then take logarithm of the equation it will become:

![image](https://user-images.githubusercontent.com/114068950/214811918-daa24444-8678-482e-b1f3-d3269884fec0.png)

# :book: Result

![image](https://user-images.githubusercontent.com/114068950/214812048-379a6839-a941-4472-ac5e-812cf4d7a583.png)


Amongst all XGBoost classifier and Logistic regression gives best accuracy score of 84.31 and 84.54 respectively. Whereas, Random FOrest classifier gives the accuaracy of around 84.09%. Decision Tree proven to be less effective model for the project as it gives the efficiency as 73.18%. The performance results is varying from 70 to 84 % and the reason could be no proper pattern of data, not relevant data or not enough data.

# :book: Conclusion

A cardiovascular risk prediction model is being prepared with the help of various classification techniques such as Logistic regression, RandomForest technique, XGBoost, Decision tree. The designed model can predict the 10 year risk of Coronary Heart Disease (CHD) for the individual. It is completely based on the previous and present health as well as medical condition.

# 📜 Credits
Chetan Chavan | Aspiring Data Scientist

linkedin.com/in/chetanchavan3794


# 📚 References 

1. GeekforGeeks (https://www.geeksforgeeks.org/removing-stop-words-nltk-python/?ref=lbp)

2. Kaggle (https://www.kaggle.com/)

3. Analytics Vidya
