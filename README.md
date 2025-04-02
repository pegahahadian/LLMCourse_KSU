#  Next Token Prediction with Transformers

This project implements and compares two neural architectures for next-token prediction using the [WikiText-2](https://paperswithcode.com/dataset/wikitext-2) dataset:

1.  **Baseline Feedforward Neural Network (FFN)**
2.  **Transformer-Based Model with Multi-Head Self-Attention**

The goal is to understand the impact of attention mechanisms and Transformer encoders on language modeling performance.

---

##  Project Structure

- `Next Token Prediction.ipynb` — Main Colab-compatible notebook with all steps:
  - Tokenization & Vocabulary Creation
  - Dataset Preparation
  - FFN & Transformer Architectures
  - Training, Evaluation & Visualization
- `requirements.txt` — Python dependencies (Hugging Face `transformers`, `datasets`, `torch`, etc.)
- `README.md` — This file.

---

##  Installation

Ensure Python ≥ 3.7 is installed, then install the dependencies:

```bash
pip install -r requirements.txt
