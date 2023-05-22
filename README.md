# Product Review Bot

## Overview
The Product Review Bot is an AI-powered language model that generates restaurant reviews based on a dataset of 1000 reviews. The model utilizes LSTM (Long-Short Term Memory), a type of neural network architecture that is well-suited for sequence-to-sequence tasks like generating natural language.

## Training Data
The language model was trained on a dataset consisting of 1000 restaurant reviews. These reviews were used to teach the model about the structure, language, and content typically found in restaurant reviews.

## Model Architecture
The model utilizes LSTM, which is a recurrent neural network architecture known for its ability to capture long-term dependencies in sequential data. LSTM is particularly suitable for tasks that involve processing and generating sequences, making it a good choice for generating restaurant reviews.

## Training Process
The model was trained on a CPU using a subset of the available training data. Due to limited computational resources, only 300 reviews were used for training. While this smaller dataset still allowed the model to learn patterns and generate coherent reviews, it is important to note that using a larger dataset and more powerful hardware could potentially improve the quality of the generated reviews.

## Evaluation and Review Generation
The generated reviews produced by the model are generally good, but there is room for improvement. The limited training data and the model's architecture may result in shorter reviews, and occasionally, some words may appear to be missing. This is likely due to the constraint set on the output length, as only the first 10 words are displayed. Adjusting this constraint can yield longer review outputs.


