# Yiren-590Assignment8
# Embedding Space Visualization Project

## Overview
This project explores various dimensionality reduction techniques for visualizing word embeddings generated by a Sentence Transformer model. Through interactive visualizations using PCA, t-SNE, and UMAP, the project aims to illustrate how these methods represent semantic relationships between words in the embedding space.

## Features
- Utilizes the **intfloat/e5-large-v2 model** from Sentence Transformers for embedding generation on the Banking77 dataset.
- Implements three distinct dimensionality reduction techniques:
  - **Principal Component Analysis (PCA)**
  - **t-Distributed Stochastic Neighbor Embedding (t-SNE)**
  - **Uniform Manifold Approximation and Projection (UMAP)**
- Provides interactive visualizations using **Plotly**.
- Includes a comprehensive analysis of each method's characteristics.

## Usage
The notebook is organized into several sections:
1. **Data Preparation**: Loads the model and generates embeddings.
2. **PCA Analysis**: Demonstrates linear dimensionality reduction.
3. **t-SNE Analysis**: Shows non-linear local structure preservation.
4. **UMAP Analysis**: Presents a balance between local and global structure preservation.

Each section contains:
- A detailed explanation of the method.
- Parameter settings and rationale.
- Interactive visualizations.
- Result analysis.

### Key Findings
- Each method provides unique insights into the embedding space.
- **PCA** offers a broad overview of the global structure.
- **t-SNE** effectively displays local relationships between words.
- **UMAP** achieves a good balance between local and global structures.
