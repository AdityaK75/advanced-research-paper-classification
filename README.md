# Advanced Research Paper Classification

A deep learning project that leverages **transformer-based models (SciBERT)** to automatically classify research papers into **57 arXiv subject categories** using only their abstracts.

## 🔍 Overview

Research paper classification is essential for effective indexing and retrieval in large academic repositories like **arXiv**. This project builds a **robust classification pipeline** that:

* Extracts features from paper abstracts using **SciBERT**, a transformer model pretrained on scientific text.
* Applies fine-tuning and classification layers to assign one or more of the 57 arXiv labels.
* Achieves strong performance by exploiting contextual embeddings from transformers, outperforming traditional NLP methods.

## ⚙️ Features

* **Automated classification** into 57 subject categories.
* **Transformer-based architecture (SciBERT)** optimized for scientific domain language.
* Modular pipeline for preprocessing, training, and evaluation.
* Support for **multi-label classification** (papers often span multiple fields).

## 📂 Tech Stack

* **Python**
* **PyTorch / HuggingFace Transformers**
* **SciBERT** (pretrained model)
* **Scikit-learn** for evaluation and preprocessing

## 📊 Results

* Improved accuracy and F1-score compared to baseline classical NLP approaches.
* Robust generalization across multiple domains of research papers.

## 🚀 Future Scope

* Expand classification to **full-text papers**, not just abstracts.
* Integrate with a **search or recommendation system** for academic repositories.
* Experiment with **Llama 3 / GPT fine-tuning** for enhanced performance.

---
