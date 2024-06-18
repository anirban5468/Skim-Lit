# Skim-Lit
This repository contains the implementation of a deep learning model for sequential sentence classification in medical abstracts, replicating the methodology outlined in the 2017 paper "PubMed 200k RCT: A Dataset for Sequential Sentence Classification in Medical Abstracts".

### Overview

The project explores the capability of natural language processing (NLP) models, particularly Recurrent Neural Networks (RNNs) such as Long Short-Term Memory networks (LSTMs), to classify sentences that appear sequentially in medical abstracts. It aims to replicate the model described in the paper to understand its performance and potential applications in biomedical text classification tasks.

### Key Features

Dataset: Utilizes the PubMed 200k RCT dataset, which consists of abstracts from randomized controlled trials (RCTs).
Models: Implements RNN-based models, including LSTMs, for sequential sentence classification.
Evaluation: Measures model performance using metrics such as accuracy and F1-score, as reported in the original paper.
Integration: Concatenates different model architectures to optimize classification results.

### Project Structure

PubMed-200k-RCT-Replication/
├── data/                    # Directory for storing dataset and data processing scripts
├── models/                  # Directory for model implementations
├── evaluation/              # Directory for evaluation scripts and metrics calculation
├── train.py                 # Script for training the models
├── evaluate.py              # Script for evaluating model performance
├── requirements.txt         # List of dependencies
└── README.md                # Project overview and instructions

### Dependencies

Python 3.x
TensorFlow 2.x
NumPy
Pandas
Usage

### Clone the repository:
git clone https://github.com/your_username/PubMed-200k-RCT-Replication.git
cd PubMed-200k-RCT-Replication
Install dependencies:

### Install dependencies:
pip install -r requirements.txt
Train the models:

### Train the models:
python train.py
Evaluate model performance:

### Evaluate model performance:
python evaluate.py

