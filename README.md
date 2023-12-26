# Song Generation with TensorFlow
Welcome to the Song Generation project! 🎶

## Overview
This project utilizes the power of TensorFlow to generate song lyrics in three distinct genres: rock, pop, and hip-hop. The models are trained on lyrics from top singers in each genre, collected through the Deezer API, and lyrics are obtained using the MusixMatch API during the data scraping phase.

## Data Scraping
The project starts with the scraping of song data through the Deezer API and lyrics via the MusixMatch API. Approximately 700 songs across the three genres serve as the training data for the models.

## Preprocessing
### Genre Categorization
The songs are categorized into their respective genres to ensure a balanced training dataset.

### Data Cleaning
A thorough data cleaning process is performed to remove any inconsistencies or anomalies in the text data.

## Text Preprocessing
1. Cleaning Text: The lyrics are preprocessed using TensorFlow text preprocessing functions to ensure that the input is suitable for model training.

2. Sequence Generation: Input sequences are created, and tokenization is applied to convert words into numerical representations.

3. Padding: Sequences are padded to ensure uniform length, allowing the model to process the data efficiently.

## Model Architecture
The heart of the project lies in the use of TensorFlow's Keras layers. The chosen architecture includes a Bidirectional LSTM layer. The model undergoes an iterative process of experimentation, with various configurations of layers tested to optimize performance.

## Results
The project results in a powerful model capable of generating song lyrics that capture the essence of rock, pop, and hip-hop genres. Explore the generated lyrics and unleash your creativity!

Feel free to contribute, report issues, or suggest improvements. Happy song generating! 🚀🎤
