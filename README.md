# Reasoning over Transformer Embeddings for Interpretable Crime News Classification  

[![Python](https://img.shields.io/badge/Python-3.9%2B-blue.svg)](https://www.python.org/)  
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)  
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/<your-username>/<repo-name>/blob/main/Reasoning%20over%20Transformer%20Embeddings%20for%20Interpretable%20Crime%20News%20Classification.ipynb)  
[![GitHub Stars](https://img.shields.io/github/stars/<your-username>/<repo-name>?style=social)](https://github.com/<your-username>/<repo-name>/stargazers)  
[![GitHub Forks](https://img.shields.io/github/forks/<your-username>/<repo-name>?style=social)](https://github.com/<your-username>/<repo-name>/network/members)  

---

This repository contains the implementation and experiments for a research project on **interpretable multi-label classification of Italian criminal news**. The work investigates how transformer-based sentence embeddings, when combined with deep classifiers and semantic reasoning techniques, can improve both **classification accuracy** and **interpretability** in forensic and legal NLP applications.

The project integrates transformer embeddings, CNN-based classifiers, and clustering mechanisms to support rare-label detection and explainability. It demonstrates that high-performing models can also be interpretable and reliable, which is critical in sensitive domains such as law enforcement and justice systems.

---

## Detailed Description  

1. **Transformer Embeddings**  
   Uses instruction-tuned multilingual embeddings (`E5-Large`) to capture nuanced semantics across Italian crime reports.  

2. **Neural Classifiers**  
   CNN-based multi-label classifiers trained on embeddings to categorize each article into multiple crime types.  

3. **Semantic Clustering**  
   K-Means clustering enhances interpretability and rare-label detection, offering structured insights for investigators.  

4. **Evaluation Metrics**  
   - Macro-F1 score for imbalanced datasets  
   - Paired *t*-tests for statistical validity  
   - Bootstrapped confidence intervals for robustness  

---

## Dataset  

- **Domain:** Italian criminal news  
- **Split:** 80% training / 20% testing  
- **Labels:** Multi-label categories for different crime classes  
- ⚠️ Dataset is not included due to licensing restrictions — please prepare your own dataset in the same format.  

---

## Results  

- Achieved **Macro-F1 ≈ 74%**  
- Outperformed baseline classifiers and zero-shot embedding methods  
- Semantic clustering improved rare-label detection and interpretability  

Outcome: The study confirms that transformer embeddings are not just powerful features but also enable **reasoning and explainable AI** in legal NLP contexts.  


## Repository Structure  

