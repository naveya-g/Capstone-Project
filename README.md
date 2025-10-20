# 🦺 Industrial Safety Chatbot

This project focuses on developing an AI-powered chatbot to assist with **industrial safety risk assessment** using **Natural Language Processing (NLP)** and **machine learning** techniques.

---

### 📌 Project Objective

To design a chatbot that can analyze incident descriptions from manufacturing plants and highlight **potential safety risks** or **accident severity levels**. The chatbot helps safety professionals and factory workers assess critical risks in real-time by interpreting historical accident data.

---

### 📂 Dataset Summary

- Accident records from **12 plants across 3 countries**
- Each row represents a real accident occurrence
- Includes features such as:
  - Accident Level (severity I–VI)
  - Potential Accident Level
  - Description of the accident
  - Industry sector, Location, Gender, Employee type, etc.

---

### 🧠 Approach

- NLP preprocessing & data cleaning
- Text augmentation using **GloVe word embeddings**
- Classification of **Potential Accident Level**
- ML/DL model evaluation for chatbot response accuracy

---

### 🤖 Deep Learning Models

To better understand and classify textual incident reports, multiple deep learning architectures were explored:

- **Recurrent Neural Networks (RNN):** Captures sequential data in accident narratives.
- **Bidirectional LSTM (Bi-LSTM):** Reads text in both forward and backward directions, improving contextual understanding.
- **Convolutional Neural Networks (CNN):** Detects key n-gram patterns in descriptions using 1D convolutions.
- **GloVe Embeddings:** Used to convert text into dense vectors for input into DL models.

> Among these, **Bi-LSTM** achieved the best performance in classifying potential accident levels from unstructured text.

---

### 🛠️ Technologies Used

- Python, Pandas, NumPy
- NLP: NLTK, SpaCy
- Word Embeddings: GloVe
- ML Models: Logistic Regression, Random Forest, Gradient Boost
- Deep Learning: RNN, Bi-LSTM, CNN (Keras/TensorFlow)
- Chatbot Framework: Streamlit

---

### 🔍 Use Case

Industrial Safety Officers and Managers can use the chatbot to quickly analyze an incident description and receive a **risk level prediction** and **safety guidance**, improving response time and risk mitigation in hazardous environments.
