# AcademicPerformanceML

# Student Exam Outcome Prediction
This project predicts whether a student will pass or fail their final examination based on their performance in the first two examinations and several demographic, social, and behavioral factors. The goal is to build a machine learning model that can classify students into "Pass" or "Fail" categories with high accuracy.

# Dataset Overview
The dataset contains information about students, including their exam scores and personal attributes. Below are the features used for prediction:
## Key Features
### Academic Performance:
First exam score
Second exam score
### Demographic Information:
School
Gender (Sex)
Age
Address (Urban/Rural)
### Family Information:
Family size
Mother's job
Father's job
### Social & Behavioral Factors:
Free time
Health status
Travel time to school
Study time
Internet access

### Target Variable:
Final exam result (Pass/Fail)

# Objective
This project aims to leverage machine learning algorithms to accurately classify students' final exam outcomes based on the above features.

# Methodology
The project explored multiple classification models to identify the best-performing one. The following models were tested:
Logistic Regression
Random Forest Classifier
Gradient Boosting

# Best Performing Model: Logistic Regression
Logistic Regression emerged as the best model for this task, achieving an accuracy of 93% on the test data. This high performance is attributed to the linear relationship between the input features and the target variable.

# Results
- Accuracy: 93%
- Precision, Recall, and F1-Score: Evaluated for both "Pass" and "Fail" classes, showing balanced performance across both outcomes.
- ROC-AUC Score: High, indicating a strong ability of the model to distinguish between the two classes.

# How to Use
1. Clone the Repository:
```
  git clone 
https://github.com/yourusername/StudentExamOutcomePrediction.git 
cd StudentExamOutcomePrediction
```
2. Install Dependencies:
```
pip install -r requirements.txt
```
3. Run the Model:
Execute the main script to train the logistic regression model and test its performance.

4. Input New Data:
Provide new student data in the required format to predict whether they will pass or fail.

# Conclusion
This project demonstrates the effectiveness of logistic regression in predicting student outcomes based on academic performance and other influencing factors. The model can be further improved by incorporating additional features or fine-tuning hyperparameters.
For questions or contributions, feel free to open an issue or pull request.
