# BBC Urdu Neural NLP Pipeline
*Ayesha Amer (23i-2503)**

## Project Overview
This project implements a complete neural natural language processing pipeline for BBC Urdu text using PyTorch. Following strict assignment guidelines, all components (including BiLSTMs and Transformers) were built from scratch without using pre-trained weights or high-level libraries like HuggingFace.

## Installation and Requirements
To run this project, you need Python 3.x and the following libraries:
- PyTorch
- NumPy
- Pandas
- Scikit-learn
- Matplotlib / Seaborn

## How to Run
1. Ensure all data files are placed in the `data/` directory.
2. Open the Jupyter Notebook `i23-2503_Assignment2_DS-6C.ipynb`.
3. Run the cells sequentially. The notebook handles:
    - Data preprocessing and vocabulary building.
    - Training the BiLSTM models for POS and NER.
    - Training the Scratch Transformer for topic classification.
    - Generating T-SNE plots and Attention Heatmaps.

## Key Features
- **Scratch Transformer:** Implemented manual Multi-Head Attention and Positional Encodings.
- **BiLSTM Sequence Labeling:** Context-aware labeling for Urdu morphology.
- **Statistical-Neural Embeddings:** Hybrid approach using TF-IDF and PPMI for word representation.
