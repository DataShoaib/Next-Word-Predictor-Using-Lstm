# Next Word Prediction using LSTM (NLP)

This project builds a **Next Word Prediction model** using Natural Language Processing (NLP) and Deep Learning.
The model learns patterns from text data and predicts the **most likely next word** in a sentence.

The system uses an **LSTM-based neural network** to understand sequential language patterns and generate predictions based on context.

---

# Project Overview

Language models are widely used in modern AI applications such as chatbots, smart keyboards, and text assistants.
This project demonstrates how a neural network can learn word relationships from text data and generate predictions for the next word in a sequence.

The model is trained on text data using tokenization and sequence generation techniques.

---

# Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Natural Language Processing (NLP)
* Google Colab / Jupyter Notebook

---

# Model Architecture

The neural network architecture used in this project:

Embedding Layer
↓
LSTM Layer
↓
LSTM Layer
↓
Dense Layer (Softmax)

### Embedding Layer

Converts words into dense vector representations.

### LSTM Layers

Capture sequential dependencies and contextual relationships between words.

### Dense Layer

Predicts the probability distribution of the next word.

---

# Training Pipeline

The model training process follows these steps:

1. Text preprocessing
2. Tokenization
3. Sequence generation
4. Padding sequences
5. Model training
6. Model saving

---

# Project Structure

next-word-prediction/

data/

notebook/

training_notebook.ipynb

models/

next_word_model.keras


README.md

requirements.txt

---

# Real World Use Cases

## 1. Smart Keyboard Autocomplete

Modern smartphone keyboards predict the next word while typing.

Example:

Input
I love machine

Prediction
learning

This technology is used in messaging apps, search engines, and mobile keyboards.

---

## 2. Chatbots and Conversational AI

Language models help chatbots generate natural responses.

Example:

Input
Artificial intelligence is

Prediction
transforming

This technique is widely used in virtual assistants and conversational systems.

---

# How to Run the Project

### Step 1: Clone the repository

git clone https://github.com/DataShoaib/Next-Word-Predictor-Using-Lstm

cd next-word-prediction

### Step 2: Install dependencies

pip install -r requirements.txt

### Step 3: Run the notebook

Open the notebook in Jupyter or Google Colab and train the model or load the saved model.

---

# Model Saving

The trained model is saved using:

model.save("models/next_word_model.keras")

Tokenizer is saved using:

pickle.dump(tokenizer, open("models/tokenizer.pkl","wb"))

---

# Future Improvements

Train the model on larger datasets
Use Bidirectional LSTM or Transformer models
Deploy the model as a web application
Build a chatbot interface

---

# License

This project is open-source and intended for educational and learning purposes.
