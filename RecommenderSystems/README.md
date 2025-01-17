
# Movie Recommender System

**Objective**: Develop a movie recommender system using two approaches: Collaborative Filtering (Matrix Factorization) and Content-Based Filtering.

---

## Project Overview
This project involves creating a recommendation system that leverages user ratings and movie metadata. The key steps include:

1. **Dataset Description**: Loading and exploring the `MovieLens 100k` dataset, merging ratings and movie details, and preprocessing the data.
2. **Data Preparation**: Splitting the dataset into training and testing sets, and creating user-item matrices for modeling.
3. **Collaborative Filtering**: Implementing a matrix factorization approach using Singular Value Decomposition (SVD) to predict user preferences.
4. **Content-Based Filtering**: Using cosine similarity to recommend movies based on their genre features.
5. **Evaluation**: Comparing the performance of both models using RMSE and discussing their strengths and limitations.

---

## Dependencies

- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `scipy`

---

## Conclusion

In this project, we implemented two different movie recommendation systems: **Collaborative Filtering** based on matrix factorization and **Content-Based Filtering** using movie features. These models were compared based on their ability to provide accurate and relevant movie recommendations.

### Summary:
- **Collaborative Filtering** is based on user-item interactions and generates personalized recommendations. It works well when there is sufficient user data but can suffer from challenges like the cold-start problem and data sparsity.
- **Content-Based Filtering** utilizes movie metadata (e.g., genres) to recommend similar movies to the user. While it can operate effectively with limited user data, it may provide recommendations that lack diversity.

### Results:
Both models demonstrated different strengths in generating recommendations. The **Collaborative Filtering** model was able to predict ratings effectively but faced limitations in cold-start scenarios. The **Content-Based Filtering** model was able to recommend similar movies based on features, though it might not capture a user's unique preferences as well as the collaborative approach.

### Final Thoughts:
Each approach has its strengths and weaknesses. A hybrid model combining both collaborative and content-based techniques could lead to a more robust and effective recommendation system. The results from both models highlight the importance of tailoring recommendation systems to the specific needs and characteristics of the data.
