---
layout: page
title: Alzheimer's Detection
description: Advanced Speech Processing Replication of Pappagari et al.
importance: 1
category: AI & Deep Learning
---

**Technologies:** Python, PyTorch, Whisper, Parakeet TDT, BERT, XGBoost.

Re-implemented the multimodal framework by Pappagari et al. (2021), replacing legacy ASR (Kaldi) with SOTA Transducers (Parakeet TDT) and Whisper. Achieved a new SOTA accuracy of 87.32% (surpassing the original paper's 84.51%) by leveraging a "Single Best" linguistic strategy. 
Benchmarked Deep Embeddings (Whisper Encoder) against handcrafted features (eGeMAPS), proving the superiority of representation learning for pathological speech.

[View on GitHub](https://github.com/ashenclock/pappagari2021-inter-replication)