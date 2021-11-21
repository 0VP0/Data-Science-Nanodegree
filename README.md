# Data Science Nanodegree project-1

This project is A Blog Post for Data Scientist Nanodegree from Udacity. I worked on a students dataset containing 480 students, consisting of e.g.(gender, Nationality, Place of Birth, Semester). So I will ask some nice questions and answer them using python libraries (scikit-learn ,pandas, NumPy, matplotlib), And then I will make a machine learning model to predict a student’s final grade in a particular course.
In this project, I asked 3 questions:

### How many males and females, and which of them is the most numerous?
		Males    305
		Females    175
	
### What are the most nationalities in this data?
		KW           179
		Jordan       172
		Palestine     28
		Iraq          22
		lebanon       17
	
### How many students got (Low-Level, Middle-Level, High-Level)?
		Middle-Level    211
		High-Level      142
		Low-Level       127

### And then,I made a machine learning model to predict a student's final grade in a particular course using Decision Tree algorithm.

### The platform I used to implement the models:
#### I use Jupyter with python using scikit-learn library.

### Description of all data preprocessing I applied to the provided dataset:
#### I convert each string in data set into numerical values to make the modeling work.

### After Evaluation results of the models using a percentage split methodology (80% for training and 20% for testing) and we get the following results:
	
	Classification accuracy: 0.7604166666666666
	F1 Score:
	H 0.68
	L 0.79
	M 0.8
