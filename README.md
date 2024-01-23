# Phishing URL Detection using RoBERTa for Feature Extraction

## Overview
This project presents a machine learning-based approach to detect phishing URLs using RoBERTa (Robustly Optimized BERT Approach) for advanced feature extraction. The model analyzes URLs by decoding their lexical, syntactic, and semantic characteristics. It integrates SHAP (SHapley Additive exPlanations) for model interpretability, providing insights into feature attributions behind each prediction.

## Dataset
The model is validated on a dataset of 550,000 URLs, achieving a high accuracy of 98.34%, demonstrating a significant improvement over traditional phishing detection methods.

## Requirements
- Python 3.6 or higher
- PyTorch
- Transformers library
- SHAP library
- Kaggle API (for dataset access)

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repository/phishing-url-detection-roberta.git
