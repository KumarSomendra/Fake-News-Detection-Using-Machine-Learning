# Fake-News-Detection-Using-Machine-Learning
A machine learning project for detecting fake news using NLP and classification models such as Logistic Regression, Decision Tree, Gradient Boosting, and Random Forest. Includes data preprocessing, TF-IDF feature extraction, model evaluation, and manual news testing.

This project is about detecting fake news using Machine Learning and Natural Language Processing (NLP). With the rise of misinformation online, this system aims to classify news articles as either Fake or True.

The dataset used for training comes from two CSV files:
Fake.csv → contains fake news articles
True.csv → contains true news articles

You can download both files from this Google Drive link: https://drive.google.com/drive/folders/1ByadNwMrPyds53cA6SDCHLelTAvIdoF_

What is done in this project?
1. Data Preprocessing
2. Removed unnecessary columns (title, subject, date)
3. Cleaned text (removing punctuation, numbers, URLs, HTML tags, etc.)
4. Feature Extraction
5. Applied TF-IDF Vectorization to convert text into numerical features
6. Model Training
7. Trained multiple classifiers:
    Logistic Regression
    Decision Tree
    Gradient Boosting
    Random Forest
    Evaluation

8. Compared models using accuracy, precision, recall, and F1-score

9. Manual Testing
   User can input a news article, and the system predicts whether it is Fake or True using all trained models. This project demonstrates how AI and ML can help fight misinformation by analyzing and classifying news content effectively.
