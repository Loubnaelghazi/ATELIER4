# Objective : The main purpose behind this lab is to get familiar with NLP language models
using Pytorch library.

## Overview
This LAB involves 3 parts :
Part1 Classification /Regression
Part 2 Transformer (Text generation)
Part 3 BERT

## Table of Contents
1. [Part 1](#Part 1)
2. [Part 2](#Part 2)
3. [Part 3](#Part 3)
4. [Acknowledgements](#Acknowledgements)

## Part 1
The preprocessing pipeline includes:
- Tokenization
- Stemming
- Lemmatization
- Stop words removal
- Text discretization

## Part 2
This part aims to fine-tune the pre-trained GPT-2 model on a custom dataset and generate text based on a given prompt.
The code consists of the following key components:

    Data Preparation: A subset of the Wikipedia dataset is loaded using the Hugging Face Datasets library. The text data is tokenized and truncated to a maximum sequence length using the GPT-2 tokenizer.

    Model Initialization: The GPT-2 model is initialized and configured for fine-tuning. The model architecture and parameters are set up for further training.

    Fine-tuning: The model is fine-tuned on the tokenized dataset using the AdamW optimizer. Training parameters such as learning rate, epochs, and batch size are specified.

    Text Generation: A function is defined to generate text based on a given prompt using the fine-tuned GPT-2 model. The generated text is decoded and printed.
    
Results

After fine-tuning the GPT-2 model on the Wikipedia dataset, the generated text demonstrates coherence and relevance to the provided prompts. The model effectively captures the language patterns and context from the training data.

Conclusion

Transformer-based models like GPT-2 offer powerful capabilities for natural language generation tasks. By fine-tuning on domain-specific datasets, these models can produce contextually relevant text outputs. This part showcases the process of fine-tuning and text generation using GPT-2, paving the way for various applications in text generation and language understanding.


## Part 3
For regression tasks, I trained:
- Support Vector Regression (SVR)
- Naive Bayes
- Linear Regression
- Decision Tree

For classification tasks, I trained:
- Support Vector Machine (SVM)
- Naive Bayes
- Logistic Regression
- Ada Boosting



## Acknowledgements
Special thanks to Pr. Elaachak Lotfi for his guidance and support throughout this project.
