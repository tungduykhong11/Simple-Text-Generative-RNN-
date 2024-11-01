
Text Generation with Recurrent Neural Networks (RNN) using Truyện Kiều
This project demonstrates a simple text generation model using RNN, trained on a portion of the Vietnamese classic Truyện Kiều. Using an RNN-based model, it predicts and generates text sequences by learning from the patterns in the text data.

Table of Contents
Overview
Dataset
Requirements
Installation
Usage
Model Training
Results
Future Improvements
License
Overview
Text generation is an NLP task where a model generates text by learning patterns and contexts in a dataset. Here, we use a simple Recurrent Neural Network (RNN) model with word embeddings to capture the structure of Vietnamese text, inspired by Truyện Kiều.

Dataset
The text data is scraped directly from Wikisource using BeautifulSoup to get the first few lines of Truyện Kiều. The text data is preprocessed to remove punctuation and special characters.

Requirements
Python 3.7+
TensorFlow 2.x
Pandas
NumPy
BeautifulSoup
Requests
Matplotlib (optional, for visualization)
