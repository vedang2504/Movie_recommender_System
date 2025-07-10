🎬 Movie Recommender System
A content-based movie recommendation system built using Python, Pandas, scikit-learn, and Gradio for interactive UI. This project suggests similar movies based on a given title by analyzing their plot overviews, genres, and taglines using TF-IDF and cosine similarity.

🚀 Features
🔍 Search any movie title (fuzzy matching supported)

📚 Uses plot, genres, and tagline for accurate recommendations

✅ Returns top 5 similar movies

🖼️ Simple and clean web interface using Gradio

⚡ Optimized to work on limited memory by sampling dataset

📦 Dataset
Source: TMDB Movies Metadata (Kaggle)

File Used: movies_metadata.csv

🛠️ Tech Stack
Python 3.x

Pandas

Scikit-learn

Gradio

TfidfVectorizer for text feature extraction

Cosine Similarity for similarity computation

FuzzyWuzzy for fuzzy movie title matching

💡 How It Works
Clean and preprocess movie metadata (overview, genres, tagline).

Combine text features into one.

Convert text into numerical vectors using TF-IDF.

Calculate similarity scores between all movies.

When user enters a title:

Fuzzy match the closest title

Find top 5 most similar movies based on content
