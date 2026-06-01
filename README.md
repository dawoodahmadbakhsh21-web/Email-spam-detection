# Email-spam-detection
AI-powered Spam Detection System using Python, NLP, TF-IDF, and Machine Learning.
# 📧 AI Spam Detection System

An AI-powered Spam Detection System built with Python and Machine Learning. This project classifies messages as **Spam** or **Not Spam (Ham)** using Natural Language Processing (NLP) and a Naive Bayes classifier.

## 🚀 Features

* Spam and Ham message classification
* Text preprocessing using TF-IDF Vectorization
* Machine Learning model using Multinomial Naive Bayes
* High accuracy on real-world SMS spam data
* Easy to train and test
* Beginner-friendly AI project

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* TF-IDF Vectorizer
* Multinomial Naive Bayes

## 📂 Dataset

The project uses the SMS Spam Collection Dataset from Kaggle.

## 📊 Workflow

1. Load Dataset
2. Data Cleaning
3. Label Encoding
4. Train-Test Split
5. TF-IDF Feature Extraction
6. Model Training
7. Prediction
8. Evaluation

## 🎯 Model Performance

* Algorithm: Multinomial Naive Bayes
* Accuracy: ~95% to 99% (depending on dataset split)

## ▶️ Installation

```bash
pip install pandas numpy scikit-learn
```

## ▶️ Run Project

```bash
python spam_detection.py
```

## 📸 Example

Input:
Congratulations! You have won a free iPhone. Click now!

Output:
Spam

Input:
Hello David, class starts at 9 AM tomorrow.

Output:
Not Spam

## 📁 Project Structure

spam-detection/
│
├── spam_detection.py
├── spam_model.pkl
├── vectorizer.pkl
├── README.md
└── dataset.csv

## 👨‍💻 Author

Dawood ahmad

## ⭐ Future Improvements

* Flask Web App
* Streamlit Dashboard
* Deep Learning Models
* Email Integration
* Real-time Spam Detection
