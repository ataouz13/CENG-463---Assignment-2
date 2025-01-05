# CENG-463 Assignment 2: NLP Model Software

This repository contains the software and scripts for completing the second assignment of CENG-463, focusing on NLP tasks. The project is organized into three primary Jupyter Notebooks:

## Notebooks Overview

### 1. Prepare Data Notebook
- Combines `.tsv` files required for training and evaluation.
- Stratifies the data into training and testing sets.
- Excludes samples with missing or invalid labels.
- **Customizable parameters:**
  - **Path to data files**: Update paths as needed.
  - **Task parameter**: Set to `1` or `2` based on the assignment requirements.

### 2. Fine-Tuning Notebook
- Designed for training NLP models using Google Colab for enhanced hardware support.
- Supports two modes:
  - **Load a pre-trained model**: Skip training and evaluate the model.
  - **Initiate training**: Start training from scratch.
- Evaluates model performance and displays key metrics:
  - Confusion Matrix
  - Precision, Recall, F1 Score, and Accuracy
- **Customizable parameters:**
  - **Path to data files**: Update paths as needed.
  - **Task parameter**: Set to `1` or `2`.

### 3. Inference Notebook
- Handles inference tasks using trained models, leveraging Colab for hardware support.
- Similar to the Fine-Tuning Notebook:
  - Evaluates performance with key metrics.
  - Displays a confusion matrix.
- **Customizable parameters:**
  - **Path to data files**: Update paths as needed.
  - **Task parameter**: Set to `1` or `2`.

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/ataouz13/CENG-463---Assignment-2.git
