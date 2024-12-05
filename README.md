
# Student Performance Analysis 📊🎓



A data analysis and machine learning mini-project to evaluate student performance based on their scores in three subjects: Mathematics, Reading, and Writing. This project also predicts student grades using machine learning models.

# Features:

+ Classifies students into grades (A, B, C, etc.) based on their performance.
+ Achieved high accuracy with multiple machine learning models: Logistic Regression, Decision Tree, and Random Forest.
+ Visualized performance trends across demographic groups using seaborn.
+ Includes cross-validation and hyperparameter tuning for better model performance.
+ used Standard scaler to normalise the data .These models benefit from normalization for faster convergence and improved performance even though  features are on similar scales

# Dataset:

The dataset used for this project is StudentsPerformance.csv. It contains:

+ **Gender**: Gender of the student.
+ **Race/ethnicity**: Demographic group of the student.
+ **Math score**: Mathematics test score.
+ **Reading score**: Reading test score.
+ **Writing score**: Writing test score.


# Workflow :

  **Data Preprocessing:** 


   + Loaded and cleaned the dataset.
   + Created a new feature Total Marks by summing up scores from all subjects.
   + Categorized students into grades (A, B, C, etc.) using statistical     thresholds.


  **Exploratory Data Analysis (EDA):**

   + Visualized grade distributions for different demographic groups.
   + Explored trends and relationships among features.


  **Machine Learning:**

   Trained the following models for grade prediction:
   + Logistic Regression
   + Decision Tree
   + Random Forest

  **Model Evaluation:**

  Achieved the following performance metrics for the Random Forest Classifier:
  + **Accuracy**: 94%
  + **Precision**: 93%
  + **Recall**: 92%
  + **F1-score**: 92%
**Classification Report:**


    f            precision   recall     f1-score   support

    Grade A       0.95       0.96        0.95       105
    Grade B       0.91       0.89        0.90        95
    Grade C       0.94       0.92        0.93       100

    accuracy                             0.94       300
    macro avg       0.93      0.92       0.93       300
    weighted avg    0.94      0.94       0.94       300


# Conclusion

+ **Gender Comparison:** There was no significant difference in performance between male and female students.

+ **Demographic Trends:** Students from certain ethnic groups tended to perform better in specific subjects.

+ **Grade Insights:** Most students scored in the B grade category, with a significant number achieving A grades.

+ **Model Accuracy:** The Random Forest Classifier outperformed other models, achieving the highest accuracy (94%) and balanced precision, recall, and F1-scores.
