# Customer Support Text Classification using NLP

## Overview
This project implements a Natural Language Processing (NLP) pipeline for customer support sentiment classification.

The objective is to classify customer messages into:

- Positive
- Neutral
- Negative

---

## Dataset Information

Dataset Name: Customer Support Text Classification Dataset

Number of Records: 1500

Target Variable:

- sentiment_label

Input Feature:

- customer_message

---
## Datasorce

`customer_support_text_classification.csv`

## Project Workflow

### Task 1: Dataset Understanding
Performed exploratory analysis including:

- Number of records
- Class labels
- Sample text records
- Average text length
- Class distribution

### Task 2: Text Preprocessing
Applied preprocessing techniques:

- Lowercasing
- Removing special characters
- Tokenization
- Stopword removal
- Sequence padding

### Task 3: Text Vectorization
Implemented:

- TF-IDF Vectorization
- Tokenizer-based sequences

### Task 4: Baseline Model
Model Used:

- Logistic Regression with TF-IDF

Performance:

- Accuracy: 100%

### Task 5: Sequence Model
Model Used:

- LSTM

Architecture:

Input → Embedding → LSTM → Dense Output

Performance:

- Test Accuracy: 100%

### Task 6: Attention and Transformers
Concepts Covered:

- RNN limitations
- LSTM memory mechanism
- Attention mechanism
- Transformers in modern NLP

---
