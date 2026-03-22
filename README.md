# 😊 Emotion Detection from Text (BiLSTM + Streamlit)

## 📌 Project Overview

This project is a **Deep Learning-based Emotion Detection system** that predicts emotions from text using a **BiLSTM (Bidirectional LSTM)** model. The application is deployed using **Streamlit**, allowing users to input text and get real-time emotion predictions.

The model classifies text into:

* 😄 Happy
* 😢 Sad
* 😡 Angry
* 😨 Fear

---

## 🎯 Objectives

* Build an NLP model to classify emotions from text
* Use BiLSTM for better context understanding
* Deploy an interactive web app
* Provide real-time predictions with confidence scores

---

## 🚀 Features

* 🧾 Simple text input interface
* ⚡ Real-time emotion prediction
* 😊 Emoji-based output visualization
* 📊 Prediction confidence score
* 🔍 Probability distribution for all emotions
* 🧹 Automatic text preprocessing

---

## 🛠️ Tech Stack

* **Python**
* **TensorFlow / Keras**
* **Streamlit**
* **Scikit-learn**
* **Pickle**

---

## 📂 Project Structure

```id="zq5b7a"
├── app.py                      # Streamlit app
├── bilstm_emotion_model.h5     # Trained BiLSTM model
├── tokenizer.pkl               # Tokenizer
├── label_encoder.pkl           # Label encoder
├── max_len.pkl                 # Max sequence length
├── requirements.txt            # Dependencies
```

---

## 🧠 Model Architecture

* Embedding Layer
* Bidirectional LSTM (BiLSTM)
* Dense Layer
* Softmax Output Layer (4 classes)

---

## 🧪 How It Works

1. User enters text
2. Text is cleaned (remove links, special characters)
3. Converted into sequences using tokenizer
4. Padded to fixed length
5. Passed into BiLSTM model
6. Model predicts emotion + confidence

Example implementation: 

---

## ▶️ How to Run Locally

### 1. Clone the repository

```bash id="8x9h4f"
git clone <your-repo-link>
cd your-project-folder
```

### 2. Install dependencies

```bash id="q2m8dk"
pip install -r requirements.txt
```

Dependencies: 

### 3. Run the app

```bash id="w2x3l9"
streamlit run app.py
```

---

## 🌐 Deployment

You can deploy this app on:

* Streamlit Cloud
* Render
* Hugging Face Spaces

---

## 🔍 Key Highlights

* Uses **BiLSTM** for better context understanding
* Real-time NLP application
* Clean UI with emoji outputs
* Displays probability for each emotion

---

## 📌 Future Improvements

* Upgrade to **Transformer models (BERT)**
* Add more emotion classes
* Improve dataset size & accuracy
* Add voice input feature

---

## 👨‍💻 Author

**Santhosh Kumar G**
Aspiring Data Scientist / Data Analyst

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
