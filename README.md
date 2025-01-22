# Sparse Autoencoder for Language Model Interpretability 

🔬 *Attempting to replicate findings from* [**Sparse Autoencoders for Language Model Interpretability**](https://arxiv.org/pdf/2401.12181) *by [Wes Gurnee et al]*

---

## Project Description 
This project implements a sparse autoencoder to analyze activations from GPT-2-small. I am following methodologies described in the referenced research paper. My goal is to:
- 🎯 Replicate key findings about feature decomposition in transformer models
- 🔍 Identify interpretable directions in activation space
## Features 
- 🧩 Activation extraction from GPT-2's intermediate layers  
- 🏗️ Custom sparse autoencoder architecture

## Installation ⚙️

```bash
# Required packages
pip install torch transformers datasets tqdm numpy
git clone https://github.com/yourusername/sparse-ae-gpt2.git
cd sparse-ae-gpt2
jupyter notebook sparse_autoencoder.ipynb
```

Saved models will appear as my_sparse_ae.pth
