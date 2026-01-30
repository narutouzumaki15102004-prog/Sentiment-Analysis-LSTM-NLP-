# IMDB Reviews Sentiment Analysis using LSTM

This project implements a sentiment analysis system for IMDB movie reviews using a Long Short-Term Memory (LSTM) neural network. The objective is to classify reviews as positive or negative based on their textual content.

The project demonstrates an end-to-end Natural Language Processing (NLP) pipeline using deep learning.

## Project Overview

- Task: Binary Text Classification
- Dataset: IMDB Movie Reviews Dataset
- Model: LSTM-based Neural Network
- Framework: TensorFlow / Keras
- Output: Sentiment prediction (Positive / Negative)

## Tech Stack

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib / Seaborn

## Workflow

1. Dataset Loading  
   IMDB reviews and corresponding sentiment labels are loaded.

2. Text Preprocessing  
   - Tokenization of text data  
   - Vocabulary size limitation  
   - Padding of sequences for uniform input length  

3. Model Architecture  
   - Embedding Layer  
   - LSTM Layer  
   - Dense Output Layer with Sigmoid activation  

4. Model Training  
   - Loss Function: Binary Cross-Entropy  
   - Optimizer: Adam  
   - Metric: Accuracy  

5. Evaluation  
   - Training and validation performance analysis  
   - Sentiment prediction on unseen reviews  

## Model Architecture (High-Level)

Embedding → LSTM → Dense (Sigmoid)

- The Embedding layer converts words into dense vector representations.
- The LSTM layer captures sequential and contextual dependencies in text.
- The Dense layer outputs the probability of a review being positive or negative.

## Results

- Achieves strong validation accuracy on the IMDB dataset
- Effectively distinguishes between positive and negative reviews
- Demonstrates practical application of deep learning for NLP tasks

Note: Exact results may vary depending on training configuration.



## Key Learnings

- Text preprocessing for deep learning models
- Sequence modeling using LSTM
- Handling variable-length text inputs
- Building an end-to-end NLP pipeline

## Acknowledgements

- IMDB Movie Reviews Dataset
- TensorFlow and Keras documentation
