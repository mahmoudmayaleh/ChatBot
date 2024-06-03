# ChatBot using Neural Networks

--------------------------------------------------------  ![image](https://github.com/mahmoudmayaleh/ChatBot/assets/124529384/1bd0197d-7d18-43aa-b3a5-892619553dec) -----------------------------------------------------

## Overview
This project implements a simple chatbot using neural networks, specifically a feedforward neural network trained on intents extracted from a JSON file. The chatbot can understand and respond to various user queries by classifying them into predefined categories.

## Features
Intent Recognition: The chatbot recognizes the intent behind user messages and responds accordingly.
Neural Network Model: Utilizes a sequential neural network model built with TensorFlow/Keras.
Bag-of-Words Representation: Converts user messages into a bag-of-words representation for training.
JSON Data Handling: Loads intent data from a JSON file for training the model.

## Dependencies
Google Colab: For running the code in a collaborative environment.
Python 3
TensorFlow 2.8
nltk: Natural Language Toolkit for text processing.
numpy: For numerical operations.

## Installation
Clone the repository: git clone https://github.com/mahmoudmayaleh/ChatBot.git
Navigate to the project directory: cd ChatBot
Install the required dependencies: pip install -r requirements.txt

## Usage
Open the Jupyter Notebook ChatBot.ipynb in Google Colab or any other compatible environment.
Execute each cell in the notebook sequentially.
The notebook will guide you through the process of importing dependencies, extracting features, building and training the neural network model.
After training, you can interact with the chatbot by sending messages and observing its responses.
Dataset
The dataset used for training is stored in Intent.json. It contains a collection of intents along with example patterns for each intent.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Credits
This project was developed by [Mahmoud Mayaleh].
