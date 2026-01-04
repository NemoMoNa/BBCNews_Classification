# BBC News Text Classification (Mini Project)

## Overview
This is a mini project for training toward becoming an AI Engineer.
The goal is not only to train a classifier, but to build a practical
end-to-end pipeline similar to real-world AI development.

This project was developed with strong support from AI assistants,
which is intentionally disclosed.

## Dataset
- BBC News Dataset
- Multi-class text classification

## Model
- DistilBERT
- Hugging Face Transformers

## Training Pipeline
- Dataset loading & splitting
- Tokenization
- Training loop with logging
- Evaluation (accuracy, macro F1)
- Error analysis (errors.tsv)

## Evaluation
- Metrics are logged in TSV format
- Misclassified samples are extracted for manual inspection

## What I Learned
- Handling dataset-specific label formats
- Writing a robust eval_model function
- Importance of logging and reproducibility
- Debugging model/data mismatches

## Notes
This project is part of a continuous AI engineering training series.
