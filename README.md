Student Performance Prediction
What This Does
Basically, this is a machine learning project to predict how well students perform academically. The dataset contains information about students' demographics and test scores. The goal is to provide insights into the factors that influence academic success and to predict outcomes for new students.

How I Did It
The project has two main parts: a classification task and a regression task.

Classification (Pass/Fail Prediction)
I used two models for this: a Logistic Regression model and a Random Forest Classifier. The process involved:

Data Loading: The dataset was loaded, and an average_score column was created.

Preprocessing: I converted the categorical columns (like gender and parental education) into numerical values so the models could understand them.

Training: The data was split into a training set and a testing set, and the models were trained.

Evaluation: I checked how well the models performed using accuracy metrics.

Regression (Average Score Prediction)
For this task, I used a Random Forest Regressor to predict the exact average score. The process was similar to the classification pipeline, with the final step being model evaluation using the Root Mean Squared Error (RMSE).

Wanna Run It Yourself?
You can clone the repo and run the Jupyter Notebook. It's pretty straightforward.

Clone the repository:

Bash

git clone https://github.com/syedaaniba/student-performance-prediction.git
Go into the project folder:

Bash

cd student-performance-prediction
Install the libraries: Make sure you have pandas and scikit-learn installed. If not, just run:

Bash

pip install pandas numpy scikit-learn matplotlib
Launch the notebook:

Bash

jupyter notebook studentperformance.ipynb
Results
The models performed well in both tasks.

Logistic Regression accuracy: ~86%

Random Forest accuracy: ~85.5%

Regression RMSE: ~14.78 points

Conclusion
The models are effective at predicting student outcomes. My analysis shows that key factors influencing performance include parental education level, test preparation course completion, and the type of lunch a student has.
