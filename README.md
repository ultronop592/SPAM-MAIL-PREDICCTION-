# SPAM-MAIL-PREDICTION: 

This project focuses on building an accurate spam detection model that can classify emails as **spam** or **ham (not spam)** . It leverages a Logistic Regression classifier trained on a real-world dataset of email messages.

# Project Overview

- Goal: Automatically identify whether an email is spam or legitimate (ham)
- Dataset: SMS Spam Collection Dataset (labelled)
- Algorithm: Logistic Regression
- Tech Stack:Python, Pandas, Scikit-learn, Natural Language Processing (NLP)

##  Workflow

1. Data Collection: Loaded and explored labeled SMS/email data
2. Preprocessing:
   - Lowercasing
   - Removing punctuation and stopwords
   - Tokenization and stemming
3. Feature Extraction:Converted text into numeric form using TF-IDF Vectorization
4. Model Training: Applied Logistic Regression
5. Evaluation:
   - Training Accuracy: 96.7%
   - Test Accuracy: 96.6%
   - Confusion Matrix & Classification Report
 6. Making predictive system     


 📈 Model Performance

| Metric        | Score      |
|---------------|------------|
| Training Acc. | 96.7%      |
| Test Acc.     | 96.6%      |
| F1-Score      | High (per class)


