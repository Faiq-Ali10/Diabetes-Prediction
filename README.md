## Overview
This repository contains a machine learning model for predicting the likelihood of diabetes in individuals based on various health indicators. The model is trained on a dataset containing information about pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, age, and diabetes outcome.

## Dataset
The dataset used for training the model is stored in the file `diabetes.csv`. It contains the following columns:

1. **Pregnancies**: Number of times pregnant
2. **Glucose**: Plasma glucose concentration after 2 hours in an oral glucose tolerance test
3. **BloodPressure**: Diastolic blood pressure (mm Hg)
4. **SkinThickness**: Triceps skin fold thickness (mm)
5. **Insulin**: 2-Hour serum insulin (mu U/ml)
6. **BMI**: Body mass index (weight in kg/(height in m)^2)
7. **DiabetesPedigreeFunction**: Diabetes pedigree function (a function that represents how likely the person is to have diabetes based on family history)
8. **Age**: Age (years)
9. **Outcome**: Whether the person has diabetes (1) or not (0)

## Requirements
To run the model, you need the following dependencies:

- Python 3.x
- NumPy
- Pandas
- Scikit-learn
