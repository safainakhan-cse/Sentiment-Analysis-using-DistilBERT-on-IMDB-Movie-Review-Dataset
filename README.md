# Sentiment-Analysis-using-DistilBERT-on-IMDB-Movie-Review-Dataset

Fine-tuned a DistilBERT model for binary sentiment classification (positive/negative) on the IMDb movie reviews dataset.

## Overview

- **Task:** Binary sentiment classification
- **Model:** DistilBERT (distilbert-base-uncased)
- **Dataset:** IMDb Movie Reviews (50,000 reviews)
- **Training data used:** 8,000 samples (subset)
- **Accuracy on test set:** 89.75%

## Results

- Accuracy: 89.80% (Validation), 89.75% (Test)
- Precision: 90.43% (Validation), 88.26% (Test) 
- Recall: 89.73% (Validation), 91.70% (Test)
- F1-Score: 90.08% (Validation), 89.95% (Test)
- BERTScore: 0.9924 (Validation), 0.9924 (Test)

## Open the notebook in Colab: 
https://colab.research.google.com/drive/1ydYN5yhkLSr4dN3Ni9zgpwp7ie4G7xQe?usp=sharing
[Open in Colab]

## Tools & Technologies 
- Python, PyTorch, HuggingFace
- Transformers: DistilBERT
- Google Colab (T4 GPU)

