# PyTorch RNN-Based QA System

## Overview
This repository contains a Recurrent Neural Network (RNN)-based Question-Answering (QA) system implemented using PyTorch. The system is designed to process and answer questions based on a provided dataset.

## Features
- Tokenization and preprocessing of text data
- Vocabulary building from question-answer pairs
- Implementation of an RNN model for text-based QA
- Training and evaluation of the QA model using PyTorch

## Dataset
The model is trained using `100_Unique_QA_Dataset.csv`, which contains unique question-answer pairs for supervised learning.

## Installation
To run this project, ensure you have Python installed along with the following dependencies:

```bash
pip install torch pandas numpy
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/pytorch-rnn-based-qa-system.git
   ```
2. Navigate to the project directory:
   ```bash
   cd pytorch-rnn-based-qa-system
   ```
3. Run the Jupyter Notebook to preprocess data, train, and evaluate the model:
   ```bash
   jupyter notebook pytorch-rnn-based-qa-system.ipynb
   ```

## Model Architecture
The model uses an RNN-based architecture, including:
- Token embedding
- Recurrent layers for sequence processing
- Output layer for generating answers

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests.



