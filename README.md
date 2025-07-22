# model-persistence-rnn

A hands-on implementation of a character-level Recurrent Neural Network (RNN) for text generation, trained to approximate the structure of Limerick poetry. This repository demonstrates model persistence (saving and loading), efficient training using Google Colab, and performance comparison across model variations.

📌 Overview

The project consists of two tasks:

Task A – Model Training and Persistence
Set up for execution in Google Colab with GPU acceleration
Dataset loading and preprocessing for character-level modeling
RNN architecture implemented using PyTorch
Model training loop
Model saving and loading logic using torch.save and torch.load
Task B – Text Generation with Trained RNNs
Functions to generate limerick-style text from trained models
Use of temperature scaling to control output diversity
Comparison of outputs from two versions:
model_v1: shorter generation
model_v2: longer generation with increased temperature
Critical reflection on model performance:
Structure partially learned (line breaks, poetic form)
Limitations in rhyme and semantics
