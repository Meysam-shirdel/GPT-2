# Basic 124M parameter GPT-2 Model Implementation with PyTorch

This repository contains a basic implementation of a GPT (Generative Pre-trained Transformer) model using PyTorch. The model architecture and training pipeline follow the principles outlined in the original GPT-2 architecture, with modifications for simplicity and educational purposes. The code is designed for educational purposes, demonstrating how to set up, train, and evaluate a GPT model from scratch.

# Key Features:

**PyTorch-based Implementation:** The core model and training loop are implemented using PyTorch, providing flexibility and control over the training process.

**Configurable Model Architecture:** A configuration class allows easy customization of the model architecture, including the number of layers, attention heads, and embedding size.

**Dataset Preparation:** Includes utilities for loading and tokenizing text data, specifically using the Tiny Shakespeare dataset.

**Training Utilities:** Features such as parameter counting, loss tracking, and average meter for monitoring training progress.

**Pretrained GPT Tokenizer:** Utilizes the tiktoken library for encoding text, ensuring compatibility with GPT-2 tokenization standards.


# Getting Started:
-Install Dependencies: Ensure you have the necessary libraries installed:

  !pip install torch transformers tiktoken tqdm

-Run the Script: You can run the code from top to down sections to start training the model on the Tiny Shakespeare dataset:

-Customization: Modify the GPTConfig class in the script to adjust the model architecture according to your needs.
