# Sleep Stage Analysis using Deep Learning and Explainable AI

## Overview
This project focuses on automated **sleep stage classification** using physiological signals such as EEG and PSG data. The objective is to accurately classify different sleep stages while maintaining **model interpretability**, which is critical for clinical and research applications.

The system combines deep learning models with **explainable AI (XAI)** techniques to move beyond black-box predictions and provide insights into model decision-making.

---

## Problem Statement
Manual sleep stage scoring is:
- Time-consuming
- Subjective
- Requires expert domain knowledge

Traditional machine learning approaches struggle to capture complex temporal and spectral patterns in sleep data. This project explores **deep neural architectures** to improve classification accuracy while ensuring interpretability.

---

## Key Features
- Automated sleep stage classification from EEG/PSG signals  
- Multiple deep learning architectures explored and compared  
- Integration of explainable AI techniques (SHAP, LIME)  
- Knowledge graph–based reasoning for enhanced interpretability  
- Focus on clinical relevance and transparency  

---

## Models Implemented
The following models were designed, trained, and evaluated:

- **CNN (Convolutional Neural Networks)**  
  For spatial and frequency-based feature extraction.

- **LSTM (Long Short-Term Memory Networks)**  
  To capture temporal dependencies in sleep cycles.

- **Deep Neural Networks (DNNs)**  
  As baseline and comparative architectures.

- **Transformer-based Models**  
  For long-range temporal modeling and attention-driven learning.

---

## Explainability & Interpretability
To address the black-box nature of deep learning models:

- **SHAP (SHapley Additive exPlanations)** was used to quantify feature contributions.
- **LIME (Local Interpretable Model-Agnostic Explanations)** was applied for local interpretability.
- **Knowledge Graphs** were incorporated to represent relationships between sleep stages, physiological patterns, and disorders.

This combination improves trust, transparency, and clinical usability.

---

## Dataset
- EEG / PSG-based sleep datasets were used for training and evaluation.
- Data preprocessing included:
  - Signal normalization
  - Noise filtering
  - Segmentation into sleep epochs

*(Dataset details can be added or anonymized based on usage constraints.)*

---

## Methodology
1. Data preprocessing and feature extraction  
2. Model training and hyperparameter tuning  
3. Performance evaluation across architectures  
4. Explainability analysis using SHAP and LIME  
5. Knowledge graph integration for reasoning and insights  

---

## Results
- Deep learning models significantly outperformed traditional baselines.
- Transformer and CNN–LSTM hybrids showed strong performance on temporal patterns.
- Explainability techniques provided meaningful insights into sleep stage transitions and signal importance.

*(Quantitative metrics can be added if you want later.)*

---

## Tech Stack
- **Programming Language:** Python  
- **Deep Learning:** TensorFlow / PyTorch  
- **Explainability:** SHAP, LIME  
- **Data Processing:** NumPy, Pandas, SciPy  
- **Visualization:** Matplotlib, Seaborn  

---

## Use Cases
- Sleep disorder research
- Clinical decision support
- Sleep quality monitoring
- Biomedical signal analysis

---

## Future Work
- Real-time sleep stage prediction
- Multi-modal signal fusion (EEG, ECG, EMG)
- Deployment as a clinical decision support tool
- Expansion of knowledge graph reasoning

---

## Author
**Suharssh** and **Gautham Shenoy** 
Final-year Computer Science student with interests in Machine Learning, Deep Learning, and Applied AI Systems.

---

## License
This project is intended for academic and research purposes.  
License details can be added as needed.
