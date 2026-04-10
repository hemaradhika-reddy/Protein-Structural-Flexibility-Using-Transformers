📌 Semester 8 - FINAL PROJECT

# Protein Structural Flexibility Using Transformers

A deep learning model to predict protein structural flexibility (B-factors) using only amino acid sequences.

## Problem

Understanding protein flexibility is important in biology, but traditional methods require complex structural data.

## Solution

This project predicts protein flexibility directly from sequences using transformer-based embeddings and deep learning.

## Features

- Predicts per-residue B-factors
- Uses ESM-2 transformer embeddings
- Combines BiLSTM for sequence learning
- Works only with protein sequence data

## Tech Stack

- Python
- PyTorch
- HuggingFace Transformers
- Biopython

## How it Works

1. Input protein sequence  
2. Generate embeddings using ESM-2  
3. Pass embeddings through BiLSTM  
4. Predict flexibility scores (B-factors)  
5. Evaluate using correlation metrics  

## Results

- Pearson correlation: 0.891  
- Tested on 1,192 protein sequences  
- Better scalability than traditional methods  

