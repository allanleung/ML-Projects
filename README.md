# ML-Projects

Re-learning everything from UBC CPSC 340 and doing my own experiments with data

# Heart Disease CSV from Kaggle

## Predicting heart disease using machine learning

This notebook looks into using various python based machine learning and data science libraries in an attempt to build a machine learning model capable of predicting whether or not someone has heart disease based on their medical attributes. 

We're going to take the following approach:

1. Problem definition
2. Data
3. Evaluation
4. Features
5. Modelling
6. Experimentation

## 1. Problem Definition

In a statement,

> Give clinicial paramters about a patient, can we predict whether or not they have heart disease?

## 2. Data

The original dataset is from Cleavland data UCI Machine Learing Repository

https://archive.ics.uci.edu/ml/datasets/heart+disease

It can also be found on Kaggle as well.

https://www.kaggle.com/ronitf/heart-disease-uci



## 3. Evaluation

> If we can reach 95% accuracy at predicting whether or not a patient has heart disease during the proof of concept.

## 4. Features

*** Data dictioanry ***

1. age
2. sex
3. chest pain type (4 values) 0: typical angina, 1: atpical angina, 2: non anginal pain, 3: asymptomatic
4. resting blood pressure
5. serum cholestoral in mg/dl
6. fasting blood sugar > 120 mg/dl
7. resting electrocardiographic results (values 0,1,2)
8. maximum heart rate achieved
9. exercise induced angina
10. oldpeak = ST depression induced by exercise relative to rest
11. the slope of the peak exercise ST segment
12. number of major vessels (0-3) colored by flourosopy
13. thal: 3 = normal; 6 = fixed defect; 7 = reversable defect

## Preparing the tools

We are going to use pandas, matplotlib and umpy for data analysis and manipulation
