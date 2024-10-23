# Machine_Translation
# Task 1: Load a pre-trained LSTM-based NMT model and use it to translate a sentence from one language to another.

## Overview
This task involves loading a pre-trained LSTM-based Neural Machine Translation (NMT) model to translate sentences from English to Spanish. The model is built using TensorFlow and Keras, and the data is processed using various NLP techniques.

## Model
- The model uses an LSTM-based architecture for sequence-to-sequence translation.
- The input data is tokenized and padded to create uniform input sequences.
- The model is trained to translate English sentences to Spanish.

## Data
- Data is fetched from a Spanish-English translation dataset.
- Sentences are split into training, validation, and test sets.
- Punctuation and special characters are handled during preprocessing.

## Files
- `Eng_Spanish.ipynb`: Contains the LSTM-based model and training script.
- `gui.py`: GUI script to interact with the model.

## Setup
1. Clone the repository:
   ```bash
   git clone <repo_url>
   cd <repo_name>
