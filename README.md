# 🤖 College Chatbot using Intent Recognition

This project is a machine learning-based chatbot that understands user queries and responds appropriately. It can recognize various ways of asking similar questions using intent classification and pattern matching.

---

## 🎯 Objective

To develop a chatbot that:
- Understands varied user queries using NLP
- Predicts the intent using a trained neural network model
- Returns an appropriate response from a predefined list

---

## 📂 Dataset

The chatbot supports two types of datasets:
1. ✅ Download from Kaggle: [Chatbots Intent Recognition Dataset](https://www.kaggle.com/datasets/elvinagammed/chatbots-intent-recognition-dataset)
2. ✅ Manually create a custom `intents.json` file with your own patterns, tags, and responses

---

## 💾 Data Storage

- `intents.json`: Acts as a simple structured database of intents
- `words.pkl`, `classes.pkl`: Save preprocessed vocabulary and labels
- `chatbot_model.h5`: Stores the trained Keras model

No traditional database (like SQLite or MySQL) is used in this project.

---

## 🛠️ Technologies Used

- Python
- TensorFlow (Keras)
- NLTK
- NumPy
- JSON
- Pickle

---

## 🧠 Model Workflow

1. Preprocess the data (tokenization, lemmatization)
2. Convert to Bag of Words vector
3. Train a dense neural network model
4. Save the model and helper files
5. Use the model to predict user intent
6. Return a suitable response from the dataset

---

## 📁 File Structure

Chatbot-Intent-Classifier/  
├── intents.json  # Dataset of patterns and responses  
├── train_chatbot.py  # Code to preprocess and train the model  
├── chatbot_model.h5  # Trained model  
├── words.pkl  # Vocabulary  
├── classes.pkl  # Intent labels  
├── chat.py  # Script to interact with the bot  
└── README.md  # Project documentation

---

## 📸 Demo

🎥 [Click here to watch the chatbot demo on Google Drive](https://drive.google.com/file/d/1EEfxDu_2foyXcqBrDCSlInz9bjVqa7rG/view?usp=drive_link)

---

## 🔮 Future Enhancements

- Add Named Entity Recognition (NER)
- Deploy with Flask/FastAPI
- Enable context for multi-turn conversations
- Use advanced language models (e.g., transformers)

---

## 👨‍💻 Author

**Bandi Shashivardhan**  
Application ID: TS202324000575169  
📧 shashibandi564@gmail.com# ChatBot
