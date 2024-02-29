# Recommendation Systems Repository

Welcome to the Recommendation Systems Repository! This repository contains implementations and examples of recommendation systems using various techniques and algorithms. Below, you'll find a brief overview of the contents and how to navigate through them.

[Recommendation system image](https://www.nvidia.com/content/dam/en-zz/Solutions/glossary/data-science/recommendation-system/img-1.png)

## Table of Contents

- [Introduction](#introduction)
- [Notebooks](#notebooks)
  - [Music Recommendation](#music-recommendation)
  - [Item-Item Collaborative Filtering](#item-item-collaborative-filtering)
  - [User-User Collaborative Filtering](#user-user-collaborative-filtering)
  - [Matrix Factorisation using Singular Value Decompostion](#Rating_prediction_using_matrix_factorization)
- [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

Recommendation systems play a crucial role in providing personalized suggestions to users, whether it's recommending music, movies, or products. This repository contains Jupyter Notebooks and code examples that demonstrate different recommendation techniques.

## Notebooks

### Music Recommendation

- [View Notebook](Music_Recommendation_System_using_KNN.ipynb)
- Description: This notebook explores music recommendation using KNN Algorithm. It demonstrates how to build a music recommendation system from scratch.

### Item-Item Collaborative Filtering

- [View Notebook](Item_Based_Collaborative_Filtering.ipynb)
- Description: In this notebook, we delve into Item-Item Collaborative Filtering, a popular recommendation technique. It shows how to leverage user-item interaction data to make item-based recommendations.

### User-User Collaborative Filtering

- [View Notebook](User_User_Based_Collaborative_Filtering.ipynb)
- Description: This notebook focuses on User-User Collaborative Filtering, another recommendation approach. It demonstrates how to create user-based recommendations based on user behavior.

### Matrix Factorisation
- [View Notebook](Rating_prediction_using_matrix_factorization.ipynb)
- Description: This notebook focuses on implementing our own functions for SGD, batch gd, user bias and item bias for implenting Singular value decomposition for rating predictions. It also includes experimentation with hyperparameter tuning.

### SVD
- [View Notebook](Singular Value Decomposition.ipynb)
- Description: This notebook performs Singular Value Decomposition on a small toy dataset, to gain an intuition, and then on the movie lens dataset. It involvs comparison of RMSE values with and without using SVD. Finally we generate the top 10 best recommendations for a user.

## Setup

To run the notebooks and experiment with the recommendation systems in this repository, you'll need to set up your development environment. You can use Google Colab to get started.

## Usage

Feel free to explore the notebooks, modify the code, and experiment with different algorithms. These notebooks serve as educational resources and starting points for building recommendation systems for your own projects.

## Contributing

Contributions are welcome! If you have improvements, bug fixes, or additional recommendation algorithms to share, please open an issue or a pull request.
