# Phishing URL Detection with BERT and PCA

This project involves detecting phishing URLs using a combination of BERT (Bidirectional Encoder Representations from Transformers) and PCA (Principal Component Analysis) to improve classification accuracy. The model processes URL data, extracts features using a pre-trained BERT model, and combines these with PCA-transformed numerical features to classify URLs as phishing or legitimate.

## Project Overview

- **Objective**: Classify phishing URLs using deep learning techniques.
- **Dataset**: The dataset consists of URL data labeled as phishing or legitimate.
- **Preprocessing**: The URLs are cleaned by removing HTTP/HTTPS, "www", and non-alphanumeric characters. Numerical features are standardized and reduced using PCA.
- **Model**: A custom neural network model that combines BERT embeddings with PCA features for improved classification performance.
- **Evaluation**: The model is evaluated using accuracy, confusion matrix, and classification report metrics.

## Dependencies

The following Python libraries are required for this project:

- `pandas`
- `numpy`
- `tensorflow`
- `sklearn`
- `seaborn`
- `matplotlib`
- `transformers`

You can install the required libraries by running:

```bash
pip install -r requirements.txt
