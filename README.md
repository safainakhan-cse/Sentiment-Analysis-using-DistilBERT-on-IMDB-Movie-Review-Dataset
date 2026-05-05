# Sentiment-Analysis-using-DistilBERT-on-IMDB-Movie-Review-Dataset

Fine-tuned a DistilBERT model for binary sentiment classification (positive/negative) on the IMDb movie reviews dataset.

## Overview

- **Task:** Binary sentiment classification
- **Model:** DistilBERT (distilbert-base-uncased)
- **Dataset:** IMDb Movie Reviews (50,000 reviews)
- **Training data used:** 8,000 samples (subset)
- **Accuracy on test set:** ~92% (or whatever your actual accuracy was — fill this in)

## Results

|
 Metric 
|
 Validation 
|
 Test 
|
|
--------
|
-----------
|
------
|
|
 Accuracy 
|
 89.80% 
|
 89.75% 
|
|
 Precision 
|
 90.43% 
|
 88.26% 
|
|
Recall
|
 89.73% 
|
 91.70% 
|
|
 F1-Score 
|
 90.08% 
|
 89.95% 
|
|
 BERTScore 
|
 0.9924 
|
 0.9924
|


## Requirements
transformers
torch
datasets
scikit-learn
pandas
numpy

## Usage Open the notebook in Colab and run all cells: https://colab.research.google.com/drive/1ydYN5yhkLSr4dN3Ni9zgpwp7ie4G7xQe?usp=sharing
[Open in Colab]

## Tools & Technologies 
- Python, PyTorch, HuggingFace
- Transformers: DistilBERT
- Google Colab (T4 GPU)

