# Project: Netflix Movie Recommendation System

## Problem Statement

With the rapid growth of OTT and streaming platforms, users are presented with thousands of movies and TV shows, making it difficult to discover content that matches their interests. Recommendation systems play a crucial role in enhancing user experience by analyzing historical user interactions and suggesting personalized content.

In this project, you will build a Movie Recommendation System using the Netflix Prize dataset. The objective is to analyze user ratings, movie information, and genre data to understand user preferences and generate personalized movie recommendations. The recommendation engine should be implemented using the Singular Value Decomposition (SVD) algorithm, a collaborative filtering technique that predicts user preferences based on latent factors learned from historical ratings.

### Dataset Description & Preprocessing Requirements:

The Movie Ratings dataset requires preprocessing, as both User IDs and Movie IDs are stored in the same column in the raw log format:
- Entries ending with a colon (`:`) represent the entity identifier (e.g., `MovieID:` or `UserID:`).
- The subsequent rows until the next colon identifier represent the interactions associated with that entity (e.g., `CustomerID, Rating, Date`).
- Learners are expected to correctly transform this raw semi-structured data into a structured tabular format (`CustomerID`, `MovieID`, `Rating`, `Date`) before performing analysis and model development.

### Objectives and Tasks:

1. **Data Loading & Preprocessing:**
   - Fetch/read raw ratings data and `movies.csv` metadata (supporting Google Drive links and local paths).
   - Parse and transform the colon-separated raw rating logs into a clean, structured pandas DataFrame.
   - Merge rating records with movie metadata (`title`, `genres`).
   - Clean data, check missing values, and handle edge cases.

2. **Exploratory Data Analysis (EDA):**
   - Rating distribution (1 to 5 stars) and average rating trends.
   - User interaction analysis (distribution of ratings per user, identifying top active users).
   - Movie popularity analysis (most reviewed movies, highest-rated movies with significant view counts).
   - Genre analysis and temporal rating patterns over time.

3. **Collaborative Filtering Model with SVD (Singular Value Decomposition):**
   - Understand latent factor modeling and matrix factorization principles.
   - Build and train the SVD recommendation engine using `scikit-surprise` (or `scipy.sparse.linalg.svds` / `sklearn.decomposition.TruncatedSVD`).
   - Evaluate model prediction accuracy using Root Mean Squared Error (RMSE) and Mean Absolute Error (MAE).

4. **Generating Personalized Top-N Recommendations:**
   - Generate top recommendations tailored to specific users for unseen movies.
   - Compare recommendations against historical user preferences.
   - Interpret latent factors and summarize business impact for streaming platforms.
