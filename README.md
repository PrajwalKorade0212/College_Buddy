

# NLP Chatbot Project

## Overview

This project focuses on building a chatbot using Natural Language Processing (NLP) techniques. The chatbot is designed to understand and respond to user inputs based on predefined intents. The project leverages libraries such as NLTK for text preprocessing and TensorFlow for building and training the neural network model.

## Features

- **Text Preprocessing**: Tokenization, lemmatization, and preparation of text data.
- **Model Training**: Building and training a neural network model to classify user intents.
- **Chatbot Interaction**: Predicting user inputs and generating appropriate responses.

## Project Structure

- `main.ipynb`: Jupyter Notebook containing the complete implementation of the chatbot.
- `intents.json`: JSON file with predefined intents, patterns, and responses.
- `words.pkl`: Pickled file containing the processed vocabulary.
- `classes.pkl`: Pickled file containing the intent classes.
- `chatbot_model.h5`: Trained model file.

## Installation

To run this project, ensure you have the following dependencies installed:

```bash
pip install numpy nltk tensorflow pickle-mixin
```

## Usage

1. **Download NLTK Data**:
    ```python
    import nltk
    nltk.download('punkt')
    nltk.download('wordnet')
    ```

2. **Run the Jupyter Notebook**:
    Open and execute `main.ipynb` to preprocess data, train the model, and save the necessary files.

3. **Interact with the Chatbot**:
    Use the trained model to predict user inputs and generate responses.

## Contributing

Contributions are welcome! Please open an issue or create a pull request for suggestions or improvements.



