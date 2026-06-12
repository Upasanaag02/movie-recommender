# 🎬 CineMatch — Movie Recommendation System

A content-based movie recommendation system that suggests similar movies using NLP and TF-IDF vectorization, powered by the TMDB API.

## 🌐 Live App
👉  [CineMatch](https://cinematche.streamlit.app)

## 📌 Overview
- Recommends similar movies based on plot, genre, and content similarity
- Uses TF-IDF vectorization and Cosine Similarity to find related movies
- Fetches real-time movie data and posters via TMDB API
- Built with a FastAPI backend and Streamlit frontend

## ✨ Features
- 🔍 Search any movie by title with autocomplete suggestions
- 🎯 Content-based recommendations using TF-IDF + Cosine Similarity
- 🎭 Genre-based recommendations
- 🖼️ Real movie posters fetched from TMDB
- 📄 Movie details page with overview, genres, release date, and backdrop
- 🏠 Home feed with trending, popular, top rated, now playing, and upcoming movies

## 🛠️ Tech Stack
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat&logo=fastapi&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-FF4B4B?style=flat&logo=streamlit&logoColor=white)
![NLP](https://img.shields.io/badge/NLP-green?style=flat)
![TMDB](https://img.shields.io/badge/TMDB_API-01B4E4?style=flat&logo=themoviedatabase&logoColor=white)

## 🧠 How It Works
1. Movie overviews and metadata are vectorized using **TF-IDF**
2. **Cosine Similarity** finds the most similar movies in the vector space
3. Results are ranked and displayed with real posters from TMDB
4. Genre-based filtering provides additional recommendations

## 🚀 Run Locally
```bash
