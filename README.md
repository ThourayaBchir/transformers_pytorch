# Minimal GPT Implementation and Training on TinyShakespeare with PyTorch

Minimal GPT Training from Scratch on TinyShakespeare (Character-Level) This script implements a compact, fully-trainable GPT-like language model using PyTorch. It demonstrates:

A minimal transformer decoder architecture (GPT) built from scratch using self-attention and feed-forward layers.

- Character-level language modeling on the Tiny Shakespeare dataset.

- Training with mixed-precision (autocast & GradScaler), gradient clipping, and learning rate scheduling (OneCycleLR).

- Optional end-to-end kernel fusion via torch.compile for acceleration.


The model learns to predict the next character in a sequence and can be adapted for other sequence modeling tasks with minimal changes.

