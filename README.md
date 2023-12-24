# NameEntityRecognition-Using-BERT

## Overview

This project implements Named Entity Recognition (NER) using the BERT (Bidirectional Encoder Representations from Transformers) model, fine-tuned on the CoNLL-2003 dataset. NER is the task of identifying and classifying entities (such as persons, organizations, and locations) within unstructured text.

## Project Structure
train_ner_model.ipynb: Jupyter Notebook containing the code for training and fine-tuning the BERT model on the CoNLL-2003 dataset.

inference.ipynb: Notebook demonstrating how to use the fine-tuned model for NER on new text.

ner_model/: Directory containing the fine-tuned BERT model and tokenizer.

datasets/: Placeholder for the CoNLL-2003 dataset (downloaded separately).

## Getting Started
Install the required dependencies: pip install -r requirements.txt

Download the CoNLL-2003 dataset and place it in the datasets/ directory.

Run train_ner_model.ipynb to train and fine-tune the BERT model.

Use inference.ipynb to perform NER on new text using the trained model.

## Model Performance
The fine-tuned BERT model achieves an accuracy of 98.60% on the validation set of the CoNLL-2003 dataset. For detailed evaluation metrics and results, refer to the training notebook.

## Dependencies
transformers==4.10.0

torch==1.9.0

datasets==1.12.0

seqeval==1.2.2
