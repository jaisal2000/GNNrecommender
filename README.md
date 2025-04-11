# LightGCN Recommender System

A PyTorch implementation of LightGCN for recommendation systems, based on the paper [LightGCN: Simplifying and Powering Graph Convolution Network for Recommendation](https://arxiv.org/abs/2002.02126).

## Features

- 🚀 Lightweight Graph Convolution Network (GCN) architecture
- 💽 MovieLens dataset integration
- 📊 BPR loss with negative sampling
- 🎯 Evaluation metrics: Recall@K, Precision@K, NDCG@K
- ⚡ GPU acceleration support

## Requirements

- Python 3.7+
- PyTorch 1.10+
- PyTorch Geometric
- pandas
- numpy
- tqdm

## Installation

```bash
pip install torch torch-geometric pandas numpy tqdm