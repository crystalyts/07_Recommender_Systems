# 07_Recommender_Systems

This project explores simple methods to create recommender systems using movies data from IMDb.

Three recommenders are made

## Code
1. Popular Movies - A popularity-based, non-personalised recommender system
    - Use a hybrid method that mix rating and rating count
    
2. Similar Movies - A similarity-based, semi-personalised recommender system that takes a movie as an input 
    - Item-based collaborative filtering
    - Calculate the Pearson Correlation Coefficient between movies

3. A personalized recommender system that takes takes a `userID`
    - User-based collaborative filtering
    - Compute cosine similarity between users

---
Data [Download](https://drive.google.com/drive/u/0/folders/1lU8kfUNQaYx782O9FRfMmyRlr5Tm3Mfs)
