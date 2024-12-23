# **Movie Recommendation System**

**Objective:**<br>
Recommender System is a system that seeks to predict or filter preferences according to the user's choices. Recommender systems are utilized in a variety of areas including movies, music, books, research articles, search queries, social tags and products in general. Recommender systems produce a list of recommendations in any of two ways:

*   **Collaborative filtering:** Collaborative filtering approaches build a model from the user's past behavior as well as similar decisions made by other users. This model then used to predict items that users may have an interst in.
*   **Content-based filtering:** Content-based filtering approaches uses a series of discrete characteristics of an item in order to recommend additional items with similar properties. This methods are totally based on a description of the item and a profile of user's preferences. It recommends items based on user's past preferences.

This project suggests movies based on your favorite movie. The model uses a dataset of movies and their genres to predict the types of movies you might like and recommends movies based on those genres.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Features](#features)
- [Model](#model)
- [Results](#results)

## Introduction

The Movie Recommendation System is designed to help you find movies similar to your favorites. By analyzing the genres of your favorite movies, the system suggests other movies you are likely to enjoy.

## Dataset

The dataset used in this project contains a collection of movies along with their genres. This dataset is used to find similarities between movies and make recommendations.

## Features

- **Movie Title**: The name of the movie.
- **Genres**: The genres associated with each movie.

## Model

The model uses a simple recommendation algorithm based on the genres of the movies. By comparing the genres of the user's favorite movie with the genres of other movies in the dataset, it identifies and recommends similar movies.

## Results

The recommendation system provides a list of movies that are similar to the user's favorite movie based on genre similarity.
