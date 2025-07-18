# 📰 Fake News Detection Web App

A machine learning-based web application that detects whether a news article is **Real** or **Fake** using Natural Language Processing (NLP) and a trained ML model.

https://drive.google.com/file/d/1S7xOED0wjLrfEP6Z-n1tAW-YLL_EuxLy/view?usp=sharing
https://drive.google.com/file/d/1ySeD6prN0M5f1vbWSKa_sRGjcJOLFAVl/view?usp=drive_link
https://drive.google.com/file/d/1Y1-F0RqjWBfW6gUlLHBgDLnKhjIM0DSN/view?usp=sharing

---

📥 Download Links

Pre-trained Models:

[Model (Pickle)]

((https://drive.google.com/file/d/1oZ7TbdI0mf4hKDi6y3cUz94m8kNQRfHw/view?usp=drive_link)) - (Name it as fake_news_model.pkl)


[TF-IDF Vectorizer]

((https://drive.google.com/file/d/1VukjFbI8KaOLmOWRCW-HO8mJO7yrzGuO/view?usp=drive_link)) - (Name it as tfidf_vectorizer.pkl)



Dataset: https://www.kaggle.com/datasets/csmalarkodi/isot-fake-news-dataset?select=Fake.csv (True and Fake both datasets)


---

## 🔍 Features

- Input custom news article text
- Predict if it's Fake or Real
- Built with Streamlit
- Clean and responsive interface

---

## 📦 Technologies Used

- Python
- Scikit-learn
- Pandas, Numpy
- Streamlit
- Joblib
- NLTK

---

## 🚀 How to Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
