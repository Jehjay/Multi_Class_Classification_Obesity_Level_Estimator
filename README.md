# Multi_Class_Classification_Obesity_Level_Estimator
Decision Tree | Support Vector Machine (SVM) Classifier

<h2> <i>Aim</i> </h2>		
<ul>
<li> To Develop a model for estimating the obesity level in individuals between 14 and 61 and the affectation level of an individual based on several factors that propitiate the apparition of obesity problems, such as eating habits and physical condition, from anonymised survey data.
<i>Techstack</i>: Python 3.7, numpy, pandas, matplotlib, sklearn, seaborn. </li>
<li> I Implemented and evaluated <i> Multi-class Decision Tree Classifier with 76% accuracy and Support Vector Machine (SVM) Classifier with 69% accuracy </i> to estimate the obesity level of an individual using seven categories: Underweight-less than 18.5, Normal-18.5 to 24.9, Overwieght I-25.0 to 29.9, Overweight II-, Obesity I-30.0 to 34.9, Obesity II-35.0 to 39.9, Obesity III-higher than 40 based on the formula - body mass index = (weight/(height*height)), allowing a detailed analysis of the affectation level of an individual. </li>
</ul>

❖ Non-pre-processed dataset sourced from:
https://archive.ics.uci.edu/dataset/544/estimation+of+obesity+levels+based+on+eating+habits+and+physical+condition

❖ There are 17 features/attributes and 2111 records with 77% of data synthetically generated using the SMOTE filter for the balancing process to decrease the probability of skewed learning in favour of a majority class.

STEPS 1
<ul><li>Import libraries</li></ul>
STEP 2
<ul><li>Fetch data and load CSV file in pandas data frame</li></ul>
STEP 3
<ul><li>Data Wrangling: Transform and Analyse the data.</li></ul>
STEP 4
<ul><li>Determine the Target variable and create an Explanatory variable</li></ul>
<ul><li>Testing and Training data split</li></ul>
<ul><li>Build Decision Tree and Support Vector Machine (SVM) multi-class classification models</li></ul>
<ul><li>Run Predictions</li></ul>
STEP 5
<ul><li>Evaluate the Models</li></ul>
<ul><li>Visualise results</li></ul>
