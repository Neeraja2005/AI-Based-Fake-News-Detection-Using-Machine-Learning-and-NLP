PROJECT TITLE:

AI‑Based Fake News Detection Using Machine Learning and NLP


---

PROBLEM STATEMENT

The accelerated spread of misinformation on social media requires a scalable solution. Manual verification is insufficient—an automated system is needed to identify and flag fake news before it spreads further.


---

PROPOSED SOLUTION

This project uses Natural Language Processing (NLP) and Machine Learning to classify news articles or headlines as "Real" or "Fake." The system:

Cleans and preprocesses the text

Transforms text via TF‑IDF or embeddings

Trains ML models like Logistic Regression, Random Forest, SVM

Deploys a Flask/Streamlit web interface for real-time use  



---

SYSTEM DEVELOPMENT APPROACH

Technologies Used:

Python

Pandas, NumPy

Scikit-learn (Logistic Regression, Random Forest, SVM)

NLTK for preprocessing

Streamlit or Flask for front end  


Tools Required:

Jupyter Notebook

GitHub

Python packages: scikit-learn, nltk, flask, streamlit, joblib




---

ALGORITHM & DEPLOYMENT

Dataset:

Two CSV files: Fake.csv and True.csv containing labeled articles  


Preprocessing Steps:

Remove noise, stopwords, punctuation

Tokenize and lemmatize text  


Feature Extraction:

TF‑IDF vectorization of news content  


Model Training:

Train several classifiers (Logistic Regression, Random Forest, SVM)

Evaluate via accuracy, precision, recall, F1-score  


Deployment:

app.py (Streamlit or Flask) loads the pickled model and vectorizer

Users input text; model classifies and shows probability scores  




---

RESULTS

The repository reports ≈99% accuracy and F1-score, demonstrating very high performance  

Users can test live via Streamlit/Flask interface

![Screenshot 2025-07-15 114107](https://github.com/user-attachments/assets/3d28b2c3-a1a3-45c7-9515-11d88ed64a09)


---

CONCLUSION

This system effectively classifies fake vs real news with high accuracy and provides a user-friendly interface for real-time detections. It can be integrated into news platforms or browsers for instant fact-checking.


---

FUTURE SCOPE

Add transformer models (BERT, LSTM, etc.) for better semantic understanding

Support multiple languages (e.g. Hindi)

Enhance model explainability (e.g. highlight keywords influencing predictions)

Deploy on cloud platforms and integrate with social media or messaging tools  



---

REFERENCES

Scikit-learn Documentation

NLTK Guide

Dataset: Fake vs Real News CSVs

Research: “CSI: A Hybrid Deep Model for Fake News Detection”


