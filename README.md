# ML-PROJECT-FAKE-NEWS

Project Overview
The notebook focuses on detecting fake news using machine learning techniques. It involves text preprocessing, feature extraction, and the training of several classification models to distinguish between real and fake news.

Key Steps and Methods
Data Handling:
The dataset, fake_real_news_78k.csv, is loaded using pandas. It contains labeled news data.
Text Preprocessing:
A custom function, wordopt, is used for cleaning the text. This involves:
Converting text to lowercase.
Removing URLs, HTML tags, punctuation, and numeric characters.
Machine Learning Models:
Four models are trained on the processed text data:
Logistic Regression
Decision Tree Classifier
Random Forest Classifier
Gradient Boosting Classifier
Each model is trained using transformed text features and evaluated based on classification metrics.
Model Evaluation:
The models are assessed using precision, recall, F1-score, and accuracy.
Accuracy scores indicate that Logistic Regression and Gradient Boosting perform the best (~87%).
Manual Testing:
A function allows users to test individual news articles. It preprocesses the input and generates predictions from all trained models, classifying the article as "Fake News" or "Not A Fake News."


6. Libraries Used
Data Handling and Analysis: pandas, numpy
Visualization: matplotlib.pyplot, seaborn
Text Processing: re, string
Machine Learning: scikit-learn modules for training and evaluation.
Results



Model Performance:
Models achieved varying levels of accuracy, with Logistic Regression and Gradient Boosting leading (~87% accuracy).
Random Forest and Decision Tree showed slightly lower performance (~78%-80%).
Observations:
The dataset is effectively processed for machine learning tasks.
Ensemble methods and linear models are highly effective for the problem.

References
1. https://www.kaggle.com/datasets/sreechrn/fake-news-detection-78k
