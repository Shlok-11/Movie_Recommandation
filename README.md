# Movie_Recommandation
Movie Recommandation using Cosine Similarity
# 🎬 Movie Recommendation System

A content-based movie recommendation system that suggests similar movies based on their overview and genre. Built using Natural Language Processing (NLP) techniques in Python.

## 📝 Overview
This project uses a dataset of 10,000 movies. It processes movie overviews and genres to create "tags" for each movie. By converting these text tags into mathematical vectors using `CountVectorizer` and calculating the `cosine_similarity` between them, the system can accurately predict and recommend 5 movies that are most similar to the one you choose.

## 🛠️ Tech Stack
* **Language:** Python
* **Data Manipulation:** Pandas
* **Machine Learning / NLP:** Scikit-Learn (`CountVectorizer`, `cosine_similarity`)
* **Serialization:** Pickle (for saving the trained models)

## 📂 Project Structure
* `Main.ipynb`: The main Jupyter/Colab notebook containing all the code for data preprocessing, model building, and testing.
* `dataset.csv`: The dataset containing movie IDs, titles, overviews, and genres. *(Note: make sure your dataset is uploaded to the repo).*
* `movies_list.pkl`: A serialized dataframe containing the processed movie data.
* `similarity.pkl`: A serialized matrix containing the calculated cosine similarity scores between all movies.

## 🚀 How to Use

### 1. Run it locally
To run this project on your local machine, follow these steps:

**Clone the repository:**
```bash
git clone [https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git)
cd YOUR_REPO_NAME
