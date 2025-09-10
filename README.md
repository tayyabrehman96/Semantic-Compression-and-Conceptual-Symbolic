# Reasoning over Transformer Embeddings for Interpretable Crime News Classification

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)  
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<your-username>/<repo-name>/blob/main/Reasoning%20over%20Transformer%20Embeddings%20for%20Interpretable%20Crime%20News%20Classification.ipynb)  
[![GitHub Stars](https://img.shields.io/github/stars/<your-username>/<repo-name>?style=social)](https://github.com/<your-username>/<repo-name>/stargazers)  
[![GitHub Forks](https://img.shields.io/github/forks/<your-username>/<repo-name>?style=social)](https://github.com/<your-username>/<repo-name>/network/members)  

---

This repository implements and analyzes interpretable multi-label classification of Italian criminal news using transformer embeddings, neural classifiers, and semantic clustering to enhance both accuracy and explainability. Critical for forensic and legal NLP applications, the approach demonstrates how high-performing models can also deliver transparent decision-making.

---

## Dataset

This project uses **DICE: a Dataset of Italian Crime Event news**—an annotated corpus of Italian crime news from the province of Modena, spanning 2011 to 2021. DICE includes 10,395 news articles tagged across 13 crime categories, enriched with metadata such as geolocation, event date, and automatic/manual annotations of entities and relations :contentReference[oaicite:1]{index=1}.

Because the dataset is shared under a **CC BY-NC-SA 4.0** license, you can redistribute and adapt it for non-commercial purposes with attribution :contentReference[oaicite:2]{index=2}.

---

## Detailed Description

This project bridges high-accuracy transformer embeddings with interpretable reasoning, targeting forensic applications where transparency is vital.

- **Transformer Embeddings**: Leverages multilingual instruction-tuned embeddings (e.g., `E5-Large`) to capture nuanced semantics from Italian crime reports.
- **Neural Classifiers**: CNN-based multi-label models trained atop embeddings to predict multiple crime categories per article.
- **Semantic Clustering**: K-Means clusters enhance interpretability and rare-label detection, providing structured semantic groupings for legal experts.
- **Evaluation**: Robust assessment using Macro-F1 (important for imbalanced data), paired *t*-tests for statistical reliability, and bootstrapped confidence intervals.

---

## Results

- Achieved **Macro-F1 ≈ 74%**, outperforming baseline and zero-shot approaches.
- Semantic clustering notably improved rare-label detection and interpretability.
- The framework confirms transformer embeddings serve not only as features but also as foundations for structured, explainable AI.

---

## Repository Structure

├── Reasoning over Transformer Embeddings for Interpretable Crime News Classification.ipynb # Main notebook
├── data/ # Place DICE dataset here (not included)
├── models/ # Pre-trained or fine-tuned models
├── results/ # Experimental outputs and plots
└── README.md # Project documentation
