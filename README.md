# GPT-1

# Character-Level GPT in PyTorch

This project was completed as part of a class assignment for CECS 451, Artificial Intelligence at CSULB.
The goal was to manually implement a character-level GPT model using PyTorch, following the decoder architecture from "Attention Is All You Need".

This project implements a simplified **character-level GPT model** using PyTorch, based on the decoder architecture from the ["Attention Is All You Need"](https://arxiv.org/abs/1706.03762) paper by Vaswani et al.

The model is trained on a plain text file to learn and generate new sequences of characters, using **masked multi-head self-attention** and **learned token/position embeddings**.

---

## Features

- Manual implementation of:
  - Scaled Dot-Product Attention
  - Multi-Head Attention
  - Feedforward sublayers
  - Residual connections and Layer Normalization
- Decoder-only architecture (GPT-style)
- Character-level tokenization
- Causal masking using lower-triangular matrix
- Autoregressive generation from context

---

## Files

| File | Description |
|------|-------------|
| `GPT_1.ipynb` | Full notebook with data loading, model definition, training, and generation |
| `input.txt`       | Text data for training (e.g. play script, Shakespeare, etc.) |
| `README.md`       | This file |

---

## Pre-req
    Make sure you have Python installed: https://www.python.org/downloads/

## How to Run

1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/character-level-gpt.git
   cd character-level-gpt

2. Install pytorch
    pip install torch

3. Run the Jupyter notebook
    jupyter notebook gpt_model.ipynb
