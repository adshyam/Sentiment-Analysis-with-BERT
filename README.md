# Sentiment-Analysis-with-BERT
Fine-tuned BERT model for sentiment classification

This repository contains a fine-tuned BERT model for sentiment classification on the IMDb dataset of movie reviews.

Model Details
Pre-trained Model: bert-tiny from Hugging Face ("https://huggingface.co/prajjwal1/bert-tiny)
Dataset: IMDb Dataset of 50k Movie Reviews from Kaggle ( "https://www.kaggle.com/datasets/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews")

Notebook Structure
Loading Libraries: Importing necessary libraries and modules.
Data Loading: Loading the IMDb dataset of 50k movie reviews 
Tokenization: Tokenizing the dataset using the BERT tokenizer.
Padding: Making sure all tokenized sequences are of the same length.
Data Split: Dividing the dataset into training and testing sets.
Data Modeling: Establishing the model architecture.
Training: Fine-tuning the BERT model on the IMDb dataset.
Evaluation: Assessing the trained model's performance on the test set.
Predictions: Demonstrating how to make sentiment predictions using the trained model.






