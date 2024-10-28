# Transformer Model for Simple Arithmetic Operations - From Scratch

This **Transformer Arithmetic Project** was completed as part of Assignment 5-2 from the *EECS 498-007 Deep Learning for Computer Vision* course at the University of Michigan. As a Computer Engineering student at the University of Toronto, I independently followed this course through publicly available YouTube lectures to deepen my understanding of Transformers.

## Project Overview

In this project, I implemented the Transformer model based on the original *Attention is All You Need* paper. The model was trained on a toy dataset for basic arithmetic operations, specifically addition and subtraction. This project involved building the Transformer architecture from scratch and visualizing its attention weights to understand its learning process.

## Key Features

- **Transformer Architecture**: Implemented various Transformer components, including multi-head attention, feed-forward layers, layer normalization, encoder, and decoder blocks, following the *Attention is All You Need* paper.
  
- **Toy Dataset for Arithmetic**: The model processes simple arithmetic expressions (addition and subtraction of integers) as sequence-to-sequence tasks.

- **Attention Visualization**: Examined attention weights to gain insights into how the Transformer model learns sequence relationships in arithmetic tasks.

## Technology Stack

- **Deep Learning Framework**: PyTorch
- **Transformer Building Blocks**: MultiHeadAttention, FeedForward, LayerNorm, Encoder, Decoder
- **Dataset**: Custom arithmetic sequence data (vector-to-vector sequences)
- **Tools**: Google Colab, Python, matplotlib for attention visualization

## Project Details

1. **Data Preparation**: Created a toy dataset consisting of simple arithmetic expressions and their results. The input and output sequences are tokenized and prepared for the model.

2. **Transformer Block Implementation**: Implemented individual Transformer blocks, including MultiHeadAttention, FeedForward, and LayerNormalization, then integrated them into Encoder and Decoder structures.

3. **Model Training**: The model was trained on the toy dataset to learn addition and subtraction operations through a sequence-to-sequence learning framework.

4. **Attention Weight Visualization**: Visualized attention weights to understand how the model focuses on different parts of the input sequence during learning.

This project demonstrates my commitment to independent learning and my initiative to explore the field of deep learning and Transformers beyond my current curriculum.
