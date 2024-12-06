# IMDB Sentiment Analysis with RNN - Streamlit Application

This project demonstrates a sentiment analysis application built using a **Recurrent Neural Network (RNN)** for classifying movie reviews from the **IMDB dataset**. The model is trained to predict whether a movie review is positive or negative. The model is then deployed on a **Streamlit app** that allows users to input movie reviews and receive sentiment predictions.

## Features

- **Train an RNN Model**: The model is trained on the IMDB dataset using TensorFlow/Keras. It uses an **Embedding Layer**, **SimpleRNN Layer**, and a **Dense Output Layer** for binary classification.
- **Streamlit Interface**: The Streamlit app provides a user-friendly interface where users can input movie reviews and receive real-time sentiment predictions.
- **Early Stopping**: The model training includes early stopping to prevent overfitting and improve the model's generalization.

## Model Architecture

- **Embedding Layer**: Converts words into dense vectors of fixed size (128).
- **SimpleRNN Layer**: A Recurrent Neural Network layer that processes sequences of words to capture the temporal patterns in the text.
- **Dense Layer**: A final layer with a sigmoid activation function to output a binary classification (positive/negative sentiment).

## Model Details
- **Dataset**: IMDB Movie Reviews Dataset
- **Model**: Recurrent Neural Network (RNN)
  - **Embedding Layer**: 128-dimensional vectors
  - **RNN Layer**: 128 units with ReLU activation
  - **Dense Layer**: Sigmoid activation for binary classification
- **Loss Function**: Binary Crossentropy
- **Optimizer**: Adam
- **Early Stopping**: The model training halts if the validation loss doesn’t improve for 5 epochs to prevent overfitting.

