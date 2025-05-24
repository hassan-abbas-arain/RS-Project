🎥 Anime Recommendation System (Content + Collaborative Filtering)
This project is a hybrid Anime Recommendation System built using both content-based and collaborative filtering techniques. It leverages user ratings and anime metadata to provide intelligent recommendations personalised for each user.

🔍 Project Overview
Type: Recommendation System (Hybrid)

Domain: Anime

Techniques Used: Content-Based Filtering, Collaborative Filtering (KNN), Cosine Similarity

Input Data: Anime metadata, User ratings

Output: Top anime recommendations for a given user

📁 Files
File Name	Description
RS_Project_content_collaborative_anime_recommendation.ipynb	Jupyter Notebook implementing both content-based and collaborative filtering recommendation logic.
anime.csv (expected)	: Contains anime metadata (name, genre, rating, etc.)
rating.csv (expected)	contains user ratings for various anime

Note: You’ll need to provide or load the appropriate anime.csv and rating.csv files for the notebook to work correctly.

📌 Features
Content-Based Filtering:

Uses genre and synopsis to recommend similar anime

Based on cosine similarity

Collaborative Filtering:

Uses user rating matrix and KNN for nearest neighbours

Predicts anime that similar users liked

📊 Libraries Used
pandas

numpy

sklearn

scipy

surprise (for collaborative filtering)

matplotlib (optional for visualisation)

▶️ How to Run
Clone this repository:

bash
Copy
Edit
git clone https://github.com/hassan-abbas-arain/RS-Project
cd anime-recommendation-system


jupyter notebook
Open RS_Project_content_collaborative_anime_recommendation.ipynb and run all cells.

Make sure the anime.csv and rating.csv files are in the same directory as the notebook or update the paths accordingly.

🚀 Output Sample
Input: Anime Title or User ID

Output: Top 10 anime recommendations
