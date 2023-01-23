# NLP for classification
This repository contains an AI model built using Tensorflow for predicting whether an amazon review is positive or negative. The dataset used for training and testing the model is from Kaggle.

The model consists of two different architectures:

- Long Short-Term Memory (LSTM)
- Gated Recurrent Unit (GRU)
Both models make use of a pre-trained word embedding called GloVe for representing the input text data in a numerical format that can be used as input to the model.

The models were trained and tested using the provided dataset, and the results were evaluated using commonly used metrics such as accuracy and log-loss.

To use the model, you will need to install Tensorflow, and other required dependencies listed in the requirements.txt file. You will also need to download the pre-trained GloVe embeddings and provide the path to the embeddings in the script.

Please refer to the comments in the code for further information and instructions on how to train the model.
