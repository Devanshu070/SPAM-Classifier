# Spam Classifier 📧

## Overview
This project focuses on building a Spam Classifier to categorize messages as either "spam" or "not spam." The classifier leverages machine learning algorithms to effectively detect spam based on message content. The model is trained on a labeled dataset containing a variety of spam and non-spam text samples, using text processing and feature extraction to improve classification accuracy.

## Dataset
The dataset used in this project contains labeled examples of spam and non-spam messages. It can be sourced from widely available datasets, such as the [SMS Spam Collection](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset) dataset on the UCI Machine Learning Repository. This dataset provides a comprehensive selection of SMS messages labeled for spam or legitimate classification.

## Text Preprocessing
To prepare the text data for machine learning, several preprocessing steps are applied:
- **Tokenization:** Messages are broken down into individual words.
- **Stopword Removal:** Common stopwords that do not contribute to spam detection are removed.
- **Stemming/Lemmatization:** Words are reduced to their base form, allowing for better generalization.
- **Vectorization:** Text data is transformed into numerical features using methods like TF-IDF (Term Frequency-Inverse Document Frequency), which captures the relevance of words in individual messages.

## Model Training
1. **Data Split:** The dataset is divided into training and testing subsets to evaluate model performance.
2. **Model Selection:** Various algorithms, including Naive Bayes, Support Vector Machines, and Logistic Regression, are considered for spam detection.
3. **Training:** The selected classifier is trained on the processed text data.
   
## Results
- **SVM Classifier**: Achieved the highest accuracy, with a score of 97.84%.
- **Naive Bayes**: Reached an accuracy of 96.77%.

## Conclusion
This spam classifier project illustrates an end-to-end approach for text classification, from preprocessing and feature extraction to model training and evaluation. The results affirm the model's effectiveness in filtering spam, making it a valuable tool for applications requiring automated spam detection in messaging systems.
