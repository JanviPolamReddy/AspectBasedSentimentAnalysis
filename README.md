# Aspect-Based Sentiment Analysis: Fine-tuning BERT for SemEval-2014 Task 4 Dataset

## Overview
This project aims to perform Aspect-Based Sentiment Analysis (ABSA) on the SemEval-2014 Task 4 dataset, focusing on the Laptops domain. The goal is to enhance sentiment analysis by identifying specific aspects within product reviews and classifying each aspect's sentiment, offering a more detailed understanding of customer feedback.

## Objectives
- Identify specific aspects within product reviews.
- Classify the sentiment of each identified aspect.
- Improve sentiment analysis granularity by focusing on aspects rather than overall reviews.

## Methodology
1. **Dataset Preparation**: Use the SemEval-2014 Task 4 dataset, specifically the Laptops domain, for ABSA.
2. **Preprocessing**: Clean and preprocess the text data to facilitate effective feature extraction.
3. **BERT Embeddings**: Employ a fine-tuned BERT model to generate contextualized embeddings for each word in the reviews.
4. **Aspect Extraction**: Develop a model to identify specific aspects within the reviews.
5. **Sentiment Classification**: Classify the sentiment of each identified aspect using a classifier trained on the BERT embeddings.
6. **Evaluation**: Measure the model's performance on the test set, focusing on both aspect identification and sentiment classification accuracy.

## Technologies
- Python
- PyTorch
- Transformers library (for BERT)
- NLTK (for preprocessing)

## Results
The results are a list of predicted analysis that may be either positive, negative or neutral. Achieved 90% accuracy for this aspect based sentiment analysis. 
