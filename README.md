# BloodPressurePrediction
Blood Pressure Prediction using LinearRegression

A healthy child’s systolic blood pressure p (in millimeters of mercury) and weight w (in pounds) are approximately related by the equation,

𝑝=𝛽0+𝛽1log(𝑤)

Hint: consider 𝑥=log(𝑤)

Use the following experimental data to estimate the systolic blood pressure of a healthy child weighing 100 pounds.

w	44	61	81	113	131
p	91	98	103	110	112


In this assignment, you will implement linear regression (without using np.polyfit) and apply it to the Assignment 4 Dataset. The dataset contains two columns, the first column is the feature and the second column is the label. The goal is find the best fit line for the data.

Use pd.read_excel() to read the file and make prediction of rainfall based on the average precipitation for past 10 days. Compare the  𝑟2  value obtained from the linear regression with that obtained through quadratic regression (Hint: use np.polyfit)
