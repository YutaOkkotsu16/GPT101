GPT101
# Bigram Language Model

This project implements a simple bigram language model using PyTorch. The model is trained on a text dataset and is capable of generating new text based on the learned patterns. The ultimate goal of this project is to ultimately create a specialized GPT capable of correctly diagnosing a patient based on the symptoms

## Setup
1. The required dependencies are installed by running `pip install torch`.
2. The `disease-handbook-complete.txt` is available in the project directory.

## Usage
1. Run the `bigram.py` script to train the bigram language model.
2. The model will be trained for a specified number of iterations, and the loss will be evaluated at regular intervals.
3. Once trained, the model can generate new text based on a given context.

## Files
- `bigram.py`: Contains the implementation of the bigram language model.
- `disease-handbook-complete.txt`: Text dataset used for training the model.

