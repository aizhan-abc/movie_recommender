# 🎬 Movie Recommendation System (Netflix-Style Mini Project)

This project is a simple **content-based movie recommendation system** built using the [MovieLens dataset](https://grouplens.org/datasets/movielens/).  
It suggests movies based on their genres using **cosine similarity**.

---

## ✅ Project Overview

- Recommends similar movies based on genres.
- Uses **pandas** for data handling and **scikit-learn** for feature extraction and similarity calculation.
- Easy and beginner-friendly — no deep machine learning required!

---

## ✅ How It Works:
1. Loads movie data from the MovieLens dataset (`movies.csv`).
2. Converts movie genres into numerical feature vectors using `CountVectorizer`.
3. Calculates similarity between movies using **cosine similarity**.
4. Recommends the top 5 movies most similar to the selected movie.

---

## ✅ Technologies Used:
- Python
- pandas
- scikit-learn (CountVectorizer & cosine similarity)
- Google Colab 

---

## ✅ Dataset Used:
[MovieLens Latest Small Dataset (ml-latest-small.zip)](https://grouplens.org/datasets/movielens/)

---

## ✅ How to Use:
1. Download the MovieLens dataset and upload `movies.csv` to your notebook.
2. Run the notebook.
3. Enter any movie title to get recommendations!

---

## ✅ Sample Recommendation Output:
