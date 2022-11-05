# Diabetes-prediction
### Main points:
1. Data understanding.
     * Dataset for predicting diabetes, and its columns are Pregnancies, Glucose, BloodPressure, SkinThickness, Insulin, BMI, DiabetesPedigreeFunction, Age, and Outcome.
     * Information about dataset attributes:
        * Pregnancies: To express the Number of pregnancies.
        * Glucose: To express the Glucose level in blood.
        * BloodPressure: To express the Blood pressure measurement.
        * SkinThickness: To express the thickness of the skin.
        * Insulin: To express the Insulin level in blood.
        * BMI: To express the Body mass index.
        * DiabetesPedigreeFunction: To express the Diabetes percentage.
        * Age: To express the age.
        * Outcome: To express the final result 1 is Yes and 0 is No.
     * All data is numeric.
     * All columns' distribution is the same and not far alot.
     * No outliers but when I see the min description of first five columns was zero and this express that there are missing values at these columns, so I turned it into mean becouse dataset is numeric.
     * The important feature that Insulin, Glucose, and DiabetesPedigreeFunction.
2. Modelling:
     * I use two algorithims (Linerregression and RandomForestClassifier), and the best accurecy was 100% of RandomForestClassifier with max_depth=10.
