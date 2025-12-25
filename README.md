# RapidFire Rag Experiments

This repository contains my experiments for the RAG track in the RapidFire AI Competition. 
The goal is to explore how different retrieval and chunking settings 
affect retrieval quality (precision@K, recall@K, MRR, NDCG).

## Structure

- `notebooks/' – Colab notebooks running RapidFire's multi-config evals
- `logs/' – The 'rapidfire.log' files + metric plots from each experiment
- `data/' – Dataset files (once I pick one) or download scripts

## Tools

- RapidFire AI (Handles all the parallel config testing + live metrics)
- Google Colab (free-tier GPU)
