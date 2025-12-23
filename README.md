# chatbot.py# Chatbot Project 🤖

This project is a simple AI-powered chatbot built using **Python**, **TensorFlow/Keras**, **NLTK**, **NumPy**, and **Pickle**. The chatbot is trained on a custom dataset (`intents.json`) containing user intents, example phrases, and responses. During preprocessing, we use **NLTK’s WordNetLemmatizer** for text normalization and tokenization, and build a bag-of-words model to represent input sentences. The training data is stored in `words.pkl` and `classes.pkl`, while the trained model is saved in the modern Keras format (`chatbot_model.keras`).

The chatbot learns to classify user input into different intent categories and respond accordingly. It uses a **Sequential neural network** with dense layers, dropout for regularization, and softmax activation for intent prediction. Accuracy achieved during training is around 94%, showing strong performance on the dataset.

### 🔧 Libraries Used
- **TensorFlow / Keras** → for building and training the neural network  
- **NLTK** → for tokenization and lemmatization (text preprocessing)  
- **NumPy** → for numerical operations and array handling  
- **Pickle** → for saving and loading preprocessed data (`words.pkl`, `classes.pkl`)  
- **JSON** → for reading the intents dataset  

### 🚀 How to Run
1. Install dependencies:
   ```bash
pip install tensorflow nltk numpy
