# SkimLit: Abstract Sentence Classification for Medical Literature

## Project Overview
In this project, we aim to replicate the deep learning model presented in the 2017 paper [*PubMed 200k RCT: a Dataset for Sequential Sentence Classification in Medical Abstracts*](https://arxiv.org/abs/1710.06071). The goal is to classify sentences within medical abstracts into specific roles (e.g., objective, methods, results) to facilitate efficient reading and comprehension of research articles.

## Problem Statement
The growing number of randomized controlled trial (RCT) papers poses challenges in efficiently reviewing the literature, particularly for unstructured abstracts. We aim to address this by developing an NLP model that classifies abstract sentences into their respective roles, aiding researchers in quickly skimming through the literature while allowing for in-depth exploration when needed.

## Project Structure

### 1. Dataset
We start by downloading the PubMed RCT200k dataset from GitHub, which serves as the foundation for our model training and evaluation.

### 2. Data Preprocessing
We develop a preprocessing function to prepare the dataset for modeling, including tokenization and embedding creation.

### 3. Baseline Model
We create a TF-IDF classifier to establish a baseline for our modeling experiments.

### 4. Deep Learning Models
We experiment with various deep learning models, incorporating different combinations of token embeddings, character embeddings, pretrained embeddings, and positional embeddings.

### 5. Multimodal Model
We build a multimodal model, replicating the architecture outlined in the research paper, which takes multiple types of data inputs.

### 6. Model Evaluation and Analysis
We evaluate the models and identify the most incorrect predictions to gain insights and improve model performance.

### 7. Predictions on New Data
Finally, we use our trained model to make predictions on unseen PubMed abstracts, demonstrating the model's practical application.

## How to Use This Notebook
To fully understand and absorb the content, consider the following approach:
1. Read through the provided descriptions and code.
2. Attempt to write the code on your own, using this notebook as a guide.
3. Experiment with the code, make modifications, and observe the effects.


---
