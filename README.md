# Recommend It!

## About
Recommend It! is a restaurant recommender system developed for DSCI 591 at Drexel University by Team BetterYelp. The official Yelp dataset that is used in this project can be found [here](https://www.kaggle.com/datasets/yelp-dataset/yelp-dataset/data).

## Abstract
This project explores the development of a recommender system using Yelp data, focusing on Philadelphia restaurants. After preprocessing business, user, and review datasets, exploratory data analysis (EDA) was performed to uncover trends in restaurant ratings, user engagement, and review behavior. A user-based collaborative filtering model was implemented, achieving an RMSE of 1.224 and MAE of 0.937, establishing a baseline for future enhancements.

## Dataset
- **Restaurants**: 12,641 Philadelphia restaurants with attributes such as categories, hours, and amenities.  
- **Users**: 312,426 users preprocessed into features including activity level, elite membership, and account age.  
- **Reviews**: 693,137 reviews filtered for quality, including ratings and text analysis.  
- **Rating Matrix**: 44,997 users × 12,591 restaurants with 693,137 ratings (99% sparsity).

## Methodology
1. **Data Preprocessing**: Cleaning, handling missing values, engineering features (e.g., user activity segments, restaurant traits).  
2. **EDA**: Distribution of ratings, user activity segmentation, review trends, and restaurant categories.  
3. **Modeling**: User-based collaborative filtering with mean-centered cosine similarity, shrinkage, and minimum overlap thresholds.

## Results
- RMSE: **1.224**  
- MAE: **0.937**  
- Able to provide Top-N personalized restaurant recommendations.  

## Future Work
- Enhance collaborative filtering with matrix factorization.
- Build content-based and hybrid recommender systems.
- Incorporate knowledge-based recommenders to address the cold-start problem.
- Apply sentiment analysis and other NLP techniques to review text to create new features that can be used to improve predictions.