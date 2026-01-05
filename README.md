# 🎬 Netflix Recommendation System with Cosine Similarity

This project implements a **content-based recommendation system** using **TF-IDF** and **Cosine Similarity** to suggest similar movies or TV shows based on their descriptions.  
It also includes **data visualization** to better understand similarity scores.

https://huggingface.co/spaces/sevvaliclal/NetflixRecommendationApp

---

## 📌 Project Overview

The goal of this project is to recommend similar content by analyzing textual features such as:
- Description
- Genres
- Content Type (Movie / TV Show)

By converting text data into numerical vectors using **TF-IDF**, we calculate similarity scores between contents using **Cosine Similarity**.

---

## 📊 Dataset Features

Main columns used in the project:

- `Title`
- `Description`
- `Genres`
- `Content Type`
- `Imdb Score`
- `Release Date`

Missing values were handled during preprocessing to ensure model stability.

---

## 🛠 Technologies Used

- **Python**
- **Pandas**
- **Scikit-learn**
- **Matplotlib**
- **Streamlit**

---

