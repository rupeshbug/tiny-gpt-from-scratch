# GPT-From-Scratch (PyTorch)

A minimal implementation of a GPT-style Transformer language model, trained from scratch on the Tiny Shakespeare dataset.  

This project is for learning and understanding how modern LLMs work under the hood — including tokenization, embeddings, self-attention, Transformer blocks, and autoregressive text generation. 

It implements the Transformer architecture introduced in the *Attention Is All You Need* paper — a landmark model that laid the foundation for modern LLMs. This project also follows Andrej Karpathy’s GPT-from-scratch tutorial for guidance.

---

## 🚀 Features

- Character-level tokenization
- PyTorch implementation of:
  - Token + positional embeddings
  - Multi-head self-attention
  - Feed-forward MLP block
  - Transformer blocks with residual connections & layer norm
- Autoregressive (GPT-style) training loop
- Training on Tiny Shakespeare (≈1 MB of text)
- Text generation with temperature sampling
- Fully commented code for learning purposes

---

## 📦 Dataset

This project uses the **Tiny Shakespeare** dataset (included in the repo).

