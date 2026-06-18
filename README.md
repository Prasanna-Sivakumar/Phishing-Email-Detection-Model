# Phishing-Email-Detection-Model
Machine Learning-based phishing email detection system using Scikit-learn, TF-IDF, and URL feature analysis to classify emails as Phishing or Safe.

# Phishing Email Detection Model

A Machine Learning-based phishing email detection system developed using Python and Scikit-learn. This project analyzes email content and URL-related features to classify emails as either **Phishing** or **Safe**.

## Features

* Email text analysis using TF-IDF vectorization
* URL extraction and suspicious link detection
* Keyword-based phishing feature extraction
* Machine Learning classification using Random Forest
* Accuracy evaluation and confusion matrix generation
* Prediction on new email messages
* Model saving and loading using Joblib

## Technologies Used

* Python
* Scikit-learn
* Pandas
* NumPy
* Joblib
* Regular Expressions (Regex)

## Workflow

1. Load phishing and legitimate email dataset.
2. Extract textual and URL-based features.
3. Convert email text into numerical features using TF-IDF.
4. Train a Random Forest classifier.
5. Evaluate model performance using accuracy, classification report, and confusion matrix.
6. Predict whether a new email is Phishing or Safe.

## Expected Outcome

The model successfully identifies phishing emails by analyzing suspicious keywords, malicious URLs, and email content patterns. It helps improve email security awareness and demonstrates the application of Machine Learning in cybersecurity.

## Learning Outcomes

* Feature Engineering for Cybersecurity Applications
* Natural Language Processing (NLP)
* Machine Learning Model Training and Evaluation
* Phishing Detection Techniques
* Building End-to-End Security Projects with Python

## Future Enhancements

* Integration with real-world phishing datasets
* Web-based user interface using Flask or Streamlit
* Real-time email scanning
* Deep Learning and BERT-based phishing detection
* Advanced URL reputation analysis
