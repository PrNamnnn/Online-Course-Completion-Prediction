# Online Course Completion Prediction using Machine Learning

##  Project Overview
Online learning platforms often face high learner dropout rates.  
This project aims to predict whether a user will complete an online course based on their engagement and activity data using machine learning techniques.

The goal is not only to achieve high prediction accuracy but also to understand learner behavior and enable early intervention strategies.


##  Problem Statement
Can we predict course completion status using learner engagement metrics such as time spent, quiz activity, and course completion rate?

Early prediction can help platforms:
- Identify at-risk learners
- Provide personalized support
- Improve overall course completion rates


##  Real-World Questions Addressed
- Can we predict which learners are likely to drop out of an online course?
- Which engagement factors most influence course completion?
- How can online platforms use these predictions for early intervention?
- How reliable is machine learning in supporting educational decision-making?


##  Dataset Description
The dataset contains anonymized user engagement data from an online learning platform.

### Features:
- **UserID**: Unique identifier for each user  
- **CourseCategory**: Category of the course (Programming, Business, Arts, etc.)  
- **TimeSpentOnCourse**: Total time spent on the course (hours)  
- **NumberOfVideosWatched**: Total videos watched  
- **NumberOfQuizzesTaken**: Total quizzes attempted  
- **QuizScores**: Average quiz score (%)  
- **CompletionRate**: Percentage of course content completed  
- **DeviceType**: Device used (0: Desktop, 1: Mobile)  
- **CourseCompletion (Target)**:  
  - 0 → Not Completed  
  - 1 → Completed  


##  Exploratory Data Analysis (EDA)
- Analyzed target variable distribution to check class balance  
- Examined key engagement metrics such as time spent and completion rate  
- Due to the structured and behavioral nature of the data, visual patterns were limited  
- Feature importance analysis was prioritized over excessive visualizations


##  Model & Methodology
- Baseline model accuracy: **79%**  
- Implemented **Random Forest Classifier** to capture non-linear relationships  
- Improved accuracy to **95%** through ensemble learning  
- Random Forest helped reduce overfitting and improved generalization


##  Results
- **Model Accuracy:** 95%  
- Key contributing features:
  - Completion Rate  
  - Time Spent on Course  
  - Quiz Performance  
- The model effectively identifies learners at risk of not completing the course


##  Tools & Technologies
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Matplotlib, Seaborn  
- Jupyter Notebook  


##  Future Improvements
- Hyperparameter tuning  
- Model deployment using Streamlit  
- Real-time learner monitoring dashboard  
- Integration with online learning platforms


##  Conclusion
This project demonstrates how machine learning can be applied to real-world educational data to improve learner engagement and reduce dropout rates.  
It emphasizes both predictive performance and practical usability in online education systems.


## Author
**Naman Prabhakar**  
BS in Data Science & Applications, IIT Madras  
