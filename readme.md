# Movie Recommender System

This repository contains a content-based and collaborative filtering movie recommender system built using Python. It leverages machine learning and data science techniques to suggest movies to users based on similarity metrics. The project also features a deployed Streamlit web app for interactive recommendations.

## Table of Contents

- [Project Overview](#project-overview)
- [Features](#features)
- [Datasets](#datasets)
- [Methods](#methods)
- [Results](#results)
- [Deployment](#deployment)
- [Contributors](#contributors)

---

## Project Overview

The goal of this project is to develop a robust movie recommendation engine that suggests movies based on content similarity. The recommender system uses content-based filtering models and is deployed via a user-friendly web interface.

## Features

- **Content-Based Filtering:**  
  Recommends movies based on genres, keywords, cast, crew, and overview similarity using cosine similarity and feature engineering.

- **Streamlit Web App:**  
  An interactive UI built with Streamlit to allow users to select a movie and get visual recommendations.

## Datasets

- **Movies Metadata:**  
  [TMDb 5000 Movie Dataset](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)

## Methods

- **Data Preprocessing:**  
  Handling null values, and extracting relevant features such as genres, keywords, cast, and crew.

- **Feature Engineering:**  
  CountVectorizer, and cosine similarity for content-based filtering.

- **Modeling:**  
  - Cosine similarity on vectorized movie features.

- **Visualization:**  
  Recommended movies displayed in a neat layout using Streamlit's UI components.

## Results

- Accurate and visually appealing movie recommendations based on the selected title.
- Enhanced user experience with a simple, responsive UI.
- Easy deployment and usability across devices via Streamlit.

## Deployment

- The complete system is deployed as a [Streamlit Web App](https://movie-recommendation-system-deploy.streamlit.app/)

## Contributors

- [Harshit Anand](https://www.linkedin.com/in/harshit-anand-a33172284)