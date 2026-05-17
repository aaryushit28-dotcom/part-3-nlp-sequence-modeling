# Part 3 – NLP and Sequence Modeling Mini Project

## Overview
This project builds an end-to-end NLP pipeline to classify customer support messages into three sentiment categories: **positive**, **neutral**, and **negative**.

## Dataset
- **File:** `customer_support_text_classification.csv`
- **Records:** 1,500
- **Target column:** `sentiment_label` (positive / neutral / negative)
- **Input column:** `customer_message`

## Project Structure
```
part-3-nlp-sequence-modeling/
├── README.md
├── notebook.ipynb          ← Complete walkthrough with code & explanations
├── requirements.txt
└── results/
    ├── model_evaluation.csv
    └── sample_predictions.txt
```

## Tasks Covered
| Task | Description |
|------|-------------|
| Task 1 | Dataset understanding & EDA |
| Task 2 | Text preprocessing pipeline |
| Task 3 | TF-IDF & Bag-of-Words vectorization |
| Task 4 | Logistic Regression + Naive Bayes baselines |
| Task 5 | LSTM architecture design & implementation |
| Task 6 | Attention & Transformer reflection |

## Results Summary
| Model | Accuracy |
|-------|----------|
| TF-IDF + Logistic Regression | 100% |
| BoW + Naive Bayes | 100% |

> The dataset is well-structured with clear lexical signals per class, resulting in near-perfect classification even with simple models.

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook notebook.ipynb
```
