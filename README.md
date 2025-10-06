# ai-medical-chatbot
NLP-powered medical chatbot that provides symptom-based diagnosis using BERT and Flask.
# 🤖 AI-Powered Medical Chatbot

An intelligent medical chatbot built using **Python, Flask, and NLP (BERT)** that provides preliminary diagnoses and symptom-based suggestions.  
This project demonstrates natural language understanding, model integration, and web app deployment — ideal for healthcare automation use cases.

---

## 🧠 Overview

This chatbot helps users input symptoms and receive potential medical conditions or advice using AI-driven text classification and entity extraction.

It is designed to:
- Understand user input via **NLP**
- Predict possible illnesses from symptoms
- Provide relevant healthcare suggestions
- Offer a web-based chat interface built with **Flask**

---

## 🔧 Tech Stack

| Area | Technologies |
|------|---------------|
| **Language** | Python |
| **Frameworks** | Flask, Scikit-learn |
| **NLP Models** | BERT, NLTK, SpaCy |
| **Frontend** | HTML, CSS, JavaScript |
| **Database** | SQLite (or MongoDB optional) |
| **Deployment** | AWS / Render / Heroku |

---

## 🚀 Features

✅ Symptom-based diagnosis using trained ML model  
✅ Context-aware chatbot with NLP preprocessing  
✅ Real-time response through Flask web app  
✅ Secure and lightweight architecture  
✅ Extendable to handle multi-language input  

---

## 📊 Model Details

The ML model was trained on a dataset of **5,000+ medical symptom records** using:
- **TF-IDF Vectorizer** for text features  
- **Random Forest Classifier** for prediction  
- Fine-tuned **BERT** for named entity recognition (NER)

Model accuracy: **~89%** on validation data.  

---

## 🧪 How to Run Locally

```bash
# 1️⃣ Clone the repository
git clone https://github.com/yourusername/ai-medical-chatbot.git
cd ai-medical-chatbot

# 2️⃣ Create a virtual environment
python -m venv venv
source venv/bin/activate   # (Mac/Linux)
venv\Scripts\activate      # (Windows)

# 3️⃣ Install dependencies
pip install -r requirements.txt

# 4️⃣ Run the app
python app.py

# 5️⃣ Open in browser
http://127.0.0.1:5000/
