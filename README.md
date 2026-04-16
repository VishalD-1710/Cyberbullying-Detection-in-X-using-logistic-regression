**Cyberbullying Detection on Social Media using Logistic Regression**

**Overview**
This project focuses on detecting cyberbullying in social media platforms such as X (Twitter) using a Machine Learning approach. The system classifies user-generated text into offensive and non-offensive categories in real time. It combines Logistic Regression with TF-IDF feature extraction to achieve accurate and efficient text classification.

**Objectives**
Detect offensive and abusive language in social media content
Build a lightweight and interpretable machine learning model
Enable real-time monitoring using Twitter API
Provide a logging mechanism for flagged content

**Key Features**
Real-time tweet and reply monitoring using Twitter API
Text preprocessing including cleaning and normalization
TF-IDF based feature extraction
Logistic Regression for binary classification
Automated logging of offensive tweets into CSV files
Scalable and low computational cost solution

**Tech Stack**
Python

Scikit-learn

Pandas and NumPy

TF-IDF Vectorizer

Tweepy (Twitter API integration)

**Methodology**
**1. Data Collection**
Collected labeled dataset of tweets (offensive and non-offensive)
Integrated Twitter API for real-time data

**2. Preprocessing**
Converted text to lowercase
Removed special characters and extra spaces
Cleaned and normalized input text

**3. Feature Extraction**
Applied TF-IDF to convert text into numerical vectors

**4. Model Training**
Trained Logistic Regression model on processed data
Used threshold-based classification

**5. Real-Time Detection** 
Retrieved tweets using Twitter API
Applied preprocessing and TF-IDF
Classified tweets instantly

**6. Logging and Reporting**
Stored offensive tweets with metadata
Generated CSV files for analysis

**Results**
The model achieved strong performance on the test dataset:
Accuracy: ~90%
Precision: High
Recall: High
F1-score: Balanced

The system performs efficiently in real-time with low latency and effectively identifies offensive content.

**Sample Output**
Tweet	Prediction
You are useless	Offensive
Have a nice day	Non-offensive

**Future Improvements**
Integration of deep learning models (BERT, Transformers)
Multilingual cyberbullying detection
Deployment as a web application
Continuous model retraining with new data

**Conclusion**
This project demonstrates an effective and scalable solution for detecting cyberbullying in social media using traditional machine learning techniques. The combination of TF-IDF and Logistic Regression provides a balance between accuracy, interpretability, and computational efficiency, making it suitable for real-time applications.
