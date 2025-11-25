# GPT-From-Scratch (PyTorch)

A minimal implementation of a GPT-style Transformer language model, trained from scratch on the Tiny Shakespeare dataset.  

This project is for learning and understanding how modern LLMs work under the hood — including tokenization, embeddings, self-attention, Transformer blocks, and autoregressive text generation.

---

## 🚀 Features

- Byte-level tokenizer (simple and easy to understand)
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

