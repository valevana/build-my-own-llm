# Build My Own LLM

A small GPT-style language model that I'm building from scratch in PyTorch, to learn how large language models actually work: tokenisation, the transformer architecture, and training.

**🚧 In progress. Target: December 2026.**

![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?logo=pytorch&logoColor=white)
![Status](https://img.shields.io/badge/status-in_progress-orange)

## What it will do
Train a small decoder-only transformer on a text dataset, then generate new text from a prompt. The aim is to understand every part of the model, not to compete with real LLMs.

## Roadmap
- [ ] Set up the project and environment
- [ ] Load and clean a training dataset
- [ ] Tokeniser: character-level first, then byte-pair encoding (BPE)
- [ ] Bigram baseline model
- [ ] Self-attention and multi-head attention
- [ ] Full transformer block (attention, feed-forward, layer norm, residual connections)
- [ ] Training loop with validation loss tracking
- [ ] Text generation with temperature and top-k sampling
- [ ] Train a larger version and compare results
- [ ] Write up results, loss curves and sample outputs

## Tech
- **Python** and **PyTorch**
- **NumPy** and **Matplotlib** for data handling and loss curves
- **Jupyter** for experiments

## Results
Results, loss curves and sample outputs will go here once training is done.

## Learning resources
- Andrej Karpathy, *Neural Networks: Zero to Hero* (YouTube)
- Vaswani et al., *Attention Is All You Need* (2017)

---
*Personal learning project by [Akshay Valerio Vanalli](https://github.com/valevana).*
