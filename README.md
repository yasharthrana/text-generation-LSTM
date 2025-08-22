# Text Generation using Recurrent Long Short Term Memory Network

This project implements a text generation model using an LSTM neural network.  
The goal is to train the model on a corpus of text and generate new text sequences that resemble the training data.

## Project Overview

- Preprocesses raw text data
- Builds and trains an LSTM model using TensorFlow/Keras
- Generates new text based on a seed input
- Evaluates the model performance

## Files

- `Text_Generation_using_Recurrent_Long_Short_Term_Memory_Network.ipynb`: Main Jupyter notebook containing data preprocessing, model building, training, and text generation code
- `requirements.txt`: Python dependencies required to run the notebook
- `.gitignore`: Specifies files and folders to ignore in version control

## How to Run

1. Clone the repository:
    ```bash
    git clone https://github.com/yasharthrana/text-generation-LSTM
    cd text-generation-LSTM
    ```

2. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```

3. Open the notebook and run it:
    ```bash
    jupyter notebook Text_Generation_using_Recurrent_Long_Short_Term_Memory_Network.ipynb
    ```

## Results

The model learns the structure and style of the training corpus and generates new text sequences character by character or word by word, depending on the implementation.
