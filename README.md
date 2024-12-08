# Hybrid Recommendation Systems

This repository explores **hybrid recommendation systems**, combining **user-based** and **item-based** collaborative filtering methods. Using the MovieLens dataset, the project demonstrates how to generate personalized movie recommendations through functionalized and detailed implementations.

---

## 🎯 Objectives

- Build user-based and item-based recommendation systems.
- Combine collaborative filtering techniques for a hybrid approach.
- Generate accurate movie recommendations for a given user.

---

## 📚 Dataset Information

The dataset is sourced from **MovieLens**, a movie recommendation service:

- **Movies**: 27,278 titles.
- **Ratings**: 2,000,0263 ratings from 138,493 users.
- **Timeframe**: January 09, 1995, to March 31, 2015.

### Variables:

1. **`movie.csv`**
   - `movieId`: Unique movie identifier.
   - `title`: Movie title.

2. **`rating.csv`**
   - `userId`: Unique user identifier.
   - `movieId`: Unique movie identifier.
   - `rating`: User rating for the movie.
   - `timestamp`: Date of the rating.

---

## 🚀 Features

1. **User-Based Recommendation**  
   - Identify similar users based on their movie preferences.
   - Generate movie suggestions based on these users' ratings.

2. **Item-Based Recommendation**  
   - Suggest movies similar to a user's highly-rated titles using correlation analysis.

3. **Hybrid Approach**  
   - Combine user-based and item-based techniques for enhanced accuracy.

4. **Statistical and Data Preprocessing**  
   - Handle outliers and missing data.
   - Ensure data quality with normalization and filtering techniques.

---

## 🛠 Implementation Highlights

- **Correlation Analysis**: Identify relationships between users or movies.  
- **Weighted Average Recommendations**: Generate personalized scores based on user similarities.  
- **Frequent Pattern Mining**: Use Apriori and association rules for advanced recommendations.
