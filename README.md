### [Project 2: Diabetics prediction using logistic regression](https://github.com/TheAnuska/Diabetics_prediction_using_logistic_regression/tree/master)

Predicting whether the person is having diabetics or not. 

# Project overview:
1. Create a tool that cood help to predict the diabetic dessies
2. Data source https://www.kaggle.com/kandij/diabetes-dataset.
3. Pre-processing data.
4. Feature investigation.
5. Visualization data.
6. Model prediction. 


# FEATURES INFORMATION
* Pregnancies: Number of times pregnant
* Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test
* BloodPressure: Diastolic blood pressure (mm Hg)
* SkinThickness: Triceps skin fold thickness (mm)
* Insulin: 2-Hour serum insulin (mu U/ml)
* BMI: Body mass index (weight in kg/(height in m)^2)
* DiabetesPedigreeFunction: Diabetes pedigree function
* Age: Age (years)
* Outcome: Class variable (0 or 1)


RESULTS: 

1. Cleaninge data.

Figure 1 presents the first insights into the dataset - statistical description. 

Using the cleaning techniques, I reduced the number of rows from 768 to 350. One of the techniques was to exclude the values from the outliers based on the box plot. 

2. Modeling and Evaluation.



3. Final message.



![](https://github.com/TheAnuska/Diabetics_prediction_using_logistic_regression/blob/master/figures/df_describe.png)

Figure 1. Statistical description of the dataset.

![](https://github.com/TheAnuska/Diabetics_prediction_using_logistic_regression/blob/master/figures/Pregnancies_vs_Glucose.png)

Figure 2. Relation between "Pregnancies" and "Glucose". The blue colour indicates a person without diabetes, and the orange means a person with diabetes.

![](https://github.com/TheAnuska/Diabetics_prediction_using_logistic_regression/blob/master/figures/Remove_outliers.png)

Figure 3. (A) Box plot of Glucose, including Outcome=1 (person with diabetes). (B) Box plot of Glucose, including Outcome=0 (a person without diabetes).




