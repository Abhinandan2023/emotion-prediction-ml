Emotion Prediction using NLP

A machine learning project that predicts the emotion expressed in text using TF-IDF and Logistic Regression, deployed with Streamlit.

Features

* Text preprocessing using NLP techniques
* TF-IDF feature extraction
* Logistic Regression for emotion classification
* Interactive Streamlit web interface
* Supports multiple emotion categories

Tech Stack

Python · NLTK · Scikit-learn · Pandas · TF-IDF · Logistic Regression · Streamlit · Joblib

Workflow

Text Input → Preprocessing → TF-IDF → Logistic Regression → Emotion

Project Structure
├── app.py
├── emotion_model.pkl
├── tfidf_vectorizer.pkl
├── emotion_mapping.pkl
├── stop_words.pkl
├── requirements.txt
└── README.md

Run Locally

git clone https://github.com/Abhinandan2023/emotion-prediction-ml.git
cd emotion-prediction-ml
pip install -r requirements.txt
python -m streamlit run app.py

Live Demo

Streamlit App: https://emotion-prediction-ml.streamlit.app/

Author

Abhinandan Maity

[GitHub](https://github.com/Abhinandan2023)
