# 🎬 Movie Recommendation System

A simple **content-based movie recommender** built with Python and scikit-learn.  
It suggests movies similar to a given title by analyzing **genres** and **overviews** using text vectorization and cosine similarity.

---

## 📌 Features
- Recommends movies based on similarity of genres and story overviews.
- Uses **CountVectorizer** for text feature extraction.
- Employs **cosine similarity** to measure closeness between movies.
- Case-insensitive search with error handling.
- 
## 🎯 Learning Objectives
- Understand text vectorization using **CountVectorizer**
- Apply **cosine similarity** for content-based recommendations
- Practice building a simple **ML/NLP project**
- Learn how to structure and document a project with clear sections

## ⚙️ Installation
Clone the repository and install dependencies:
```bash
git clone https://github.com/your-username/movie-recommender.git
cd movie-recommender
pip install -r requirements.txt
```
## 🐍 Requirements
- Python 3.8+
- scikit-learn
- pandas
- numpy

## 🚀 Usage
Run the script:
- python movie_recommender.py
Example in Python:
print(recommend("Iron Man"))
Output:
['Iron Man 3', 'Guardians of the Galaxy Vol. 2', 'Avengers: Age of Ultron', 'Star Wars: Episode III - Revenge of the Sith', 'Iron Man 2']

## 📂 Project Structure

movie-recommender/
├── data/
│   └── movie_dataset.csv   # dataset
├── movie_recommender.py    # main code
├── requirements.txt        # dependencies
└── README.md               # project description

## 📊 Dataset
This project uses a movie dataset with columns:

id → unique movie ID
title → movie name
overview → short description of the movie
genre → type of movie (crime, comedy, romance, horror, etc.)

## 🔮 Future Work
- Add a Streamlit UI for interactive recommendations.
- Extend with collaborative filtering for user-based suggestions.
- Integrate more features like ratings, actors, and directors.

