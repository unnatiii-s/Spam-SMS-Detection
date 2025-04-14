# Spam-SMS-Detection

This project aims to detect whether an SMS message is spam or ham (not spam) using Natural Language Processing (NLP) and Machine Learning. The model processes the raw text data, extracts meaningful patterns, and classifies the messages with high accuracy.


Files Description
- spam.csv - Dataset containing labeled SMS messages (spam/ham)
- spamsmsdetection.ipynb - Jupyter Notebook with preprocessing, model training, and evaluation
- spam_sms_model.pkl - Saved trained spam detection model
The trained model achieved an accuracy of approximately 97.5% on the test data.


Features :
- Text Cleaning and Preprocessing: Removes punctuation, stopwords, and performs lemmatization.
- Feature Extraction: Uses TF-IDF Vectorization to convert text to numerical form.
- Model Training: Trained on a Multinomial Naive Bayes classifier or the best performing model from comparison.
- Evaluation Metrics: Includes accuracy, precision, recall, F1-score, and confusion matrix.
- Model Persistence: Saves the trained model using pickle for future use.
