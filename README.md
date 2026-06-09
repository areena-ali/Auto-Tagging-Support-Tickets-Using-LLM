# Auto-Tagging-Support-Tickets-Using-LLM
## Objective

Automatically classify customer support tickets into predefined categories using Large Language Models (LLMs) and return the top 3 most probable tags.

## Methodology

1. Dataset Loading
2. Data Cleaning and Preprocessing
3. Zero-Shot Classification
4. Few-Shot Learning
5. Fine-Tuning Dataset Preparation
6. Model Development using TF-IDF and Logistic Regression
7. Evaluation using Accuracy and Classification Report
8. Top-3 Tag Prediction
9. Performance Visualization

## Key Results

| Method | Accuracy |
|----------|----------|
| Zero-Shot | 78% |
| Few-Shot | 86% |
| Fine-Tuned | 92% |

## Observations

- Few-Shot Learning performs better than Zero-Shot Learning.
- Fine-Tuning provides the highest accuracy.
- The system successfully predicts the top three categories for support tickets.

## Files

- support_tickets.csv
- Task5_Auto_Tagging_Support_Tickets.ipynb
- README.md
