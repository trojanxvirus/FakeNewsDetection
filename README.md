# FakeNewsDetection

This project focuses on detecting fake news using machine learning models including Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting. It involves data preprocessing, text cleaning, and feature extraction using TF-IDF vectorization.

# Table of Contents
> Project Overview
> Steps Involved
> Results and Visualizations
> Conclusion
> Future Work

# Project Overview
The goal of this project is to build a classification model that can accurately distinguish between real and fake news articles. The project involves several steps, including data preprocessing, feature extraction, model training, and evaluation.

# Steps Involved

# 1.Data Reading and Preparation:
> Loaded datasets from True.csv and Fake.csv.
> Assigned labels: 1 for true news and 0 for fake news.
> Combined the datasets into a single DataFrame.

# 2.Data Cleaning:
> Dropped unnecessary columns such as title, subject, and date.
> Shuffled the dataset to ensure random distribution.
> Applied a cleaning function to the text data to remove URLs, HTML tags, punctuation, digits, and newline characters.

# 3.Feature Extraction:
> Split the data into training and testing sets.
> Used TF-IDF vectorization to convert text data into numerical features suitable for machine learning models.
> Model Training:

#Trained four different models:
> Logistic Regression
> Decision Tree Classifier
> Random Forest Classifier
> Gradient Boosting Classifier

# 4.Model Evaluation:
> Evaluated the performance of each model using classification reports.
> Visualized the distribution of true and fake news labels.
> Created confusion matrices for each model to analyze prediction accuracy.

# 5.Manual Testing:
> Implemented a function to manually test news articles using the trained models.
> Provided predictions from all four models for a given input news article.

# 6.Manual Testing:
> Input a news article when prompted.
>The script will output predictions from all four models.



# Results and Visualizations
> Classification Reports:
Detailed performance metrics including precision, recall, f1-score, and support for each model.

> Confusion Matrices:
Graphical representation of the models' performance in terms of true positive, true negative, false positive, and false negative predictions.

# Conclusion
This project demonstrates the effectiveness of various machine learning models in detecting fake news. The Logistic Regression model provided the best performance in terms of accuracy and precision. The results indicate that text-based features extracted using TF-IDF are highly useful for distinguishing between real and fake news articles.

# Future Work
> Implementing deep learning models for potentially better accuracy.
> Exploring other feature extraction techniques.
> Integrating additional datasets for more comprehensive training.
