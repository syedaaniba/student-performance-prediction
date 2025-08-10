Student Performance Prediction
This project uses machine learning models to predict how well students perform academically. The dataset contains information about students like gender, race, parental education, lunch type, and test preparation course, along with their scores in math, reading, and writing.

The project has two parts:

Classification: Predict whether a student passes or fails based on average scores.

Regression: Predict the exact average score of a student.

I used Logistic Regression and Random Forest classifiers for the classification task and Random Forest Regressor for predicting average scores.

How to Use
Clone the repository:

Bash

git clone https://github.com/syedaaniba/student-performance-prediction.git
Install required libraries (if not installed):

Bash

pip install pandas numpy scikit-learn matplotlib
Open the Jupyter notebook studentperformance.ipynb and run the cells to see the analysis and model training.

Results
Logistic Regression accuracy: around 86%

Random Forest accuracy: around 85.5%

Regression RMSE: about 14.78 points

Conclusion
The models perform well for predicting pass/fail and average scores. Important factors influencing performance include parental education level, test preparation course, and lunch type.







give me read me file


Student Performance Prediction
This project uses machine learning models to predict how well students perform academically. The dataset contains information about students such as their gender, race, parental education, lunch type, and whether they completed a test preparation course, along with their scores in math, reading, and writing.

The project addresses two main tasks:

Classification: Predicting whether a student passes or fails based on their average scores.

Regression: Predicting a student's exact average score.

I used Logistic Regression and Random Forest classifiers for the classification task and a Random Forest Regressor for predicting average scores.

How to Use
Clone the repository:

Bash

git clone https://github.com/syedaaniba/student-performance-prediction.git
Install the required libraries:

Bash

pip install pandas numpy scikit-learn matplotlib
Run the notebook:
Open the Jupyter notebook studentperformance.ipynb and execute the cells to see the data analysis, model training, and results.

Results
Logistic Regression accuracy: ~86%

Random Forest accuracy: ~85.5%

Regression RMSE: ~14.78 points

Conclusion
The models perform well for predicting both pass/fail status and average scores. The analysis shows that key factors influencing student performance include parental education level, completion of a test preparation course, and lunch type.
