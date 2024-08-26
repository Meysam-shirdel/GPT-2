# Basic 124M parameter GPT Model Implementation with PyTorch

This repository contains a basic implementation of a GPT (Generative Pre-trained Transformer) model using PyTorch. The code is designed for educational purposes, demonstrating how to set up, train, and evaluate a GPT model from scratch.

# Key Features:
**PyTorch-based Implementation:** The core model and training loop are implemented using PyTorch, providing flexibility and control over the training process.
**Configurable Model Architecture:** A configuration class allows easy customization of the model architecture, including the number of layers, attention heads, and embedding size.
**Dataset Preparation:** Includes utilities for loading and tokenizing text data, specifically using the Tiny Shakespeare dataset.
**Training Utilities:** Features such as parameter counting, loss tracking, and average meter for monitoring training progress.
**Pretrained GPT Tokenizer:** Utilizes the tiktoken library for encoding text, ensuring compatibility with GPT-2 tokenization standards.
