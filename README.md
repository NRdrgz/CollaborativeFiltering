# Movie Recommendation System using Collaborative Filtering

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Results](#results)
- [Future Work](#future-work)

## Introduction

This project implements a movie recommendation system using collaborative filtering techniques. It utilizes the MovieLens dataset to build and evaluate models that can predict user preferences and recommend movies.

## Features

- Data preprocessing and exploration of the MovieLens dataset
- Implementation of collaborative filtering models using FastAI
- Comparison of matrix factorization and neural network-based approaches
- Visualization of learned latent factors
- Handling of the cold start problem for new users
- Evaluation of model performance and prediction accuracy

## Requirements

- Python 3.7+
- FastAI
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

## Results

The project demonstrates the effectiveness of collaborative filtering in generating movie recommendations. We were able to recommend new movies to an existing or a new user, and assess the performance of the model on existing users, with a MSE of 0.74 on movie ratings. 

## Future Work

- Implement hybrid models combining collaborative and content-based filtering
- Further improve the overfitting problem
- Explore more advanced deep learning architectures
- Enhance the handling of the cold start problem
