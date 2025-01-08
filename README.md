Next Word Prediction using LSTM
Description:
This project implements a Next Word Predictor using Long Short-Term Memory (LSTM) networks, trained on the "All Attention You Need" PDF dataset. The model achieves approximately 98% accuracy in predicting the next word in a given sentence, making it highly efficient for natural language processing (NLP) tasks such as text completion and language modeling.

The LSTM model learns the dependencies between words in a sequence and uses this knowledge to predict the most probable next word given a context. The training dataset, derived from the "All Attention You Need" PDF, consists of diverse text samples, providing the model with a wide range of vocabulary and syntactical structures.

Key Features:
LSTM-based Model: The core architecture uses LSTM layers to capture long-term dependencies in text sequences.
High Accuracy: Achieves around 98% accuracy in next-word prediction, demonstrating high effectiveness in NLP tasks.
Text Preprocessing: Preprocessing steps include tokenization, text cleaning, and padding to ensure optimal model performance.
Dataset: Trained on the "All Attention You Need" PDF dataset, which was carefully processed and transformed into a suitable format for training.
Requirements:
Python 3.x
TensorFlow (2.x)
Keras
NumPy
Pandas
