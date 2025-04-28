# H&M Fashion Recommendations with Product2Vec

## Project Overview 👀
A personalized fashion recommendation system for H&M using Product2Vec, developed for DTSA5511 at the University of Colorado Boulder. This approach adapts Word2Vec from NLP to learn product embeddings from customer purchase sequences.

## Problem Statement 🎯
This project predicts which articles each H&M customer will purchase in a 7-day period by leveraging historical transaction data, addressing the challenge of connecting online shoppers with relevant products.

## Dataset 📊
- 31M+ transaction records from 1.3M+ customers
- 105K+ unique clothing items with metadata
- Transaction details including dates, customer IDs, and article IDs

## Methodology 🧑‍💻
- Product2Vec approach: treating purchase sequences as "sentences" and products as "words"
- 128-dimensional vector representations capture co-occurrence patterns
- Skip-gram architecture with recency bias and popular-item fallbacks
- Parallelized processing with memory optimizations for scalability

## Results 🏆
- MAP@12: 0.002
- Item coverage: 56.4%
- Customer coverage: 72.3%

## Future Work 🔮
Potential improvements include better temporal modeling, hyperparameter tuning, cold-start problem mitigation, and incorporation of product attributes and images.
