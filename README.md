# BART-Summarization-CNN

This repository contains the code to train a summarization model using the BART architecture. The training and evaluation is performed on a subset of the CNN_Dailymail dataset. The model is fine-tuned for the task of summarizing news articles.

## Key Features
1. <b>Environment Setup</b>: Initial setup including the installation of necessary libraries such as Pytorch Lightning, Transformers, and Torchmetrics.
2. <b>Data Preparation</b>: Loading and preparation of the CNN_Dailymail dataset from parquet files, and data tokenization using the BART tokenizer.
3. <b>Custom Dataset</b>: Definition of a custom dataset class for PyTorch's DataLoader for efficient data loading.
4. <b>Model Configuration</b>: Configuration of the BART model for summarization, including setting hyperparameters like learning rate, batch sizes, and number of epochs.
5. <b>Training</b>: Training loop for the summarization model, with loss tracking and logging.
6. <b>Validation</b>: Validation step to monitor the model performance during training.
7. <b>Testing</b>: Testing step to evaluate the model's summarization performance, along with ROUGE score calculation for evaluation.
8. <b>Model Saving</b>: Saving the trained model and tokenizer for future use.
9. <b>Example Usage</b>: Code to create a summary for a new article and evaluate its performance using ROUGE scores.
10. <b>Google Drive Access</b>: Code to mount Google Drive in Colab for accessing/saving models.
