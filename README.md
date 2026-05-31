# UAS-Data-Mining-Business-Intelligence
# Food Nutrition Classification Using Machine Learning
Project UAS : Perbandingan 10 model klasifikasi dengan SMOTE, Hypertuning Parameter dan Threshold Prediction

**Abstrak**
Project bertujuan untuk mengklasifikasikan makanan ke dalam kategori nutrisi seimbang dan nutrisi tidak seimbang berdasarkan kandungan gizi seperti energi, protein, karbohidrat, lemak, serat, gula, dan sodium. Penelitian membandingkan berbagai algoritma machine learning, yaitu KNN, Decision Tree, Random Forest, Bagging, Logistic Regression, Naive Bayes, AdaBoost, Gradient Boosting, CatBoost, dan XGBoost. Proses analisis mencakup preprocessing data, standarisasi fitur, penanganan ketidakseimbangan kelas menggunakan SMOTE, hyperparameter tuning, threshold prediction, evaluasi menggunakan confusion matrix dan balanced accuracy, serta analisis kemampuan generalisasi model. Hasil penelitian menunjukkan bahwa Logistic Regression dengan SMOTE memberikan performa terbaik dengan balanced accuracy sebesar 98,5% pada skenario split data 80:20.

**Keywords**: Machine Learning, Food Nutrition Classification, Balanced Nutrition, SMOTE, Hyperparameter Tuning, Logistic Regression, Balanced Accuracy.

This project focuses on classifying food items into two categories:

0 = Balanced Nutrition
1 = Unbalanced Nutrition

The classification is performed using nutritional attributes including:
Energy (Calories)
Protein
Carbohydrates
Fat
Fiber
Sugar
Sodium

# Objectives
Compare the performance of multiple machine learning algorithms for food nutrition classification.
Evaluate the impact of data balancing and model optimization techniques.
Identify the best-performing model for detecting balanced and unbalanced nutritional content.

## Machine Learning Models
K-Nearest Neighbor (KNN)
Decision Tree
Random Forest
Bagging
Logistic Regression
Naive Bayes
AdaBoost
Gradient Boosting
CatBoost
XGBoost

## Methodology
Data Preprocessing
Feature Standardization (StandardScaler)
Class Imbalance Handling using SMOTE
Hyperparameter Tuning
Threshold Prediction Optimization
Model Evaluation using:
Confusion Matrix
Accuracy
Precision
Recall
F1-Score
Balanced Accuracy
Generalization Analysis (Overfitting Detection)
Results

## Best Model
The best model obtained in this study was:
| Model | Technique | Data Split | Balanced Accuracy |
|---------|---------|---------|---------|
| Logistic Regression | SMOTE | 80:20 | **0.985** |

The best-performing model in this project was **Logistic Regression with SMOTE**, achieving a **Balanced Accuracy of 98.5%** on the 80:20 train-test split. The model showed excellent classification performance and good generalization ability without significant signs of overfitting.

The results indicate that machine learning models can effectively support nutritional assessment and food classification tasks, achieving high predictive performance while maintaining good generalization ability.

## Technologies
Python
Pandas
NumPy
Scikit-Learn
Imbalanced-Learn (SMOTE)
Matplotlib
Seaborn
CatBoost
XGBoost


