# Student Performance Prediction

## What This Does

This is a machine learning project that predicts how well students perform academically. The dataset contains information about students' demographics and their test scores in math, reading, and writing. The goal is to identify factors that influence academic success and predict outcomes for new students.

---

## How I Did It

The project addresses two main machine learning tasks: a **classification** task and a **regression** task.

### Classification (Pass/Fail Prediction)

I used a **Logistic Regression** model and a **Random Forest Classifier**. The pipeline for this was:

* **Data Loading:** The dataset was loaded, and an `avg_score` column was created.
* **Preprocessing:** Categorical data was converted into numerical values that the models could understand using one-hot encoding.
* **Training:** The data was split into training and testing sets, and the models were trained on the training data.
* **Evaluation:** The models were evaluated on the test data using accuracy metrics.

### Regression (Average Score Prediction)

For this task, I used a **Random Forest Regressor** to predict the exact average score. The process was similar to the classification pipeline, with the final step being evaluation using the **Root Mean Squared Error (RMSE)**.

---

## Dataset

The dataset contains:

* Gender
* Race/ethnicity
* Parental level of education
* Type of lunch (standard or free/reduced)
* Test preparation course completion status
* Scores in math, reading, and writing

---

## Wanna Run It Yourself?

You can clone the repo and run the Jupyter Notebook. It's pretty straightforward.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/syedaaniba/student-performance-prediction.git](https://github.com/syedaaniba/student-performance-prediction.git)
    ```

2.  **Go into the project folder:**
    ```bash
    cd student-performance-prediction
    ```

3.  **Install the libraries:** Make sure you have pandas and scikit-learn installed. If not, just run:
    ```bash
    pip install pandas numpy scikit-learn matplotlib
    ```

4.  **Launch the notebook:**
    ```bash
    jupyter notebook studentperformance.ipynb
    ```

---

## Results

* **Logistic Regression accuracy:** ~86%
* **Random Forest accuracy:** ~85.5%
* **Random Forest Regressor RMSE:** ~14.78 points

---

## Key Findings

The analysis shows these factors significantly influence student performance:

* Parental education level
* Completion of a test preparation course
* Lunch type

---

## Conclusion

This project demonstrates practical machine learning skills like data preprocessing, model training, and evaluation. The models are effective at predicting student pass/fail status and average scores, which could be useful for academic interventions or support programs.
