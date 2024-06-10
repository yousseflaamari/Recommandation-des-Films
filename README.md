# Movie Recommendation System

This repository contains various implementations of movie recommendation systems, including collaborative filtering (user-based, item-based, model-based) and content-based filtering. The project leverages the MovieLens dataset to develop and evaluate these recommendation models.

## Authors

- Laamari Youssef
## Supervisor

- Prof. Hdiioud Ferdouss

## Overview

In the era of information overload, recommendation systems play a crucial role in helping users make informed decisions by filtering and suggesting relevant items. This project explores different recommendation techniques to provide personalized movie suggestions.

## Table of Contents

1. [Introduction](#introduction)
2. [General Idea](#general-idea)
3. [MovieLens Dataset](#movielens-dataset)
4. [Data Exploration](#data-exploration)
5. [Data Visualization](#data-visualization)
6. [Recommendation Filters](#recommendation-filters)
    - [Content-Based Filtering](#content-based-filtering)
    - [Collaborative Filtering](#collaborative-filtering)
        - [Item-Based](#item-based)
        - [User-Based](#user-based)
        - [Model-Based (SVD)](#model-based-svd)
7. [Examples of Execution](#examples-of-execution)
8. [Conclusion](#conclusion)

## Introduction

Recommendation systems (RS) are information processing systems that actively collect various types of data to create suggestions. These systems aim to reduce information overload, improve product discovery, personalize user experiences, increase customer satisfaction, and optimize user decisions.

## General Idea

The main goal of this project is to filter information to a limited quantity based on user preferences, thereby assisting users in making informed decisions.

## MovieLens Dataset

The MovieLens 20M dataset, available on Kaggle, is widely used in recommendation system research. It includes:

- `ratings.csv`: User ratings for movies.
- `movies.csv`: Information about movies.

## Data Exploration

Exploratory data analysis is performed on the dataset to understand its structure and contents, such as checking for missing or duplicate values.

## Data Visualization

Visualizations help to understand the distribution of ratings, genre correlations, and other patterns within the dataset.

## Recommendation Filters

### Content-Based Filtering

Content-based filtering recommends items similar to those the user has liked in the past based on item features like genres or release year.

### Collaborative Filtering

Collaborative filtering provides personalized suggestions based on user interactions.

#### Item-Based

Identifies items similar to those the user has liked.

#### User-Based

Finds users with similar preferences to provide recommendations.

#### Model-Based (SVD)

Uses Singular Value Decomposition to understand complex user-item interactions and generate recommendations.

## Examples of Execution

- **Content-Based Filtering:** Recommendations based on movie genres and release year.
- **Collaborative Filtering:** KNN and SVD models are used for generating recommendations.

## Conclusion

The developed models demonstrate the effectiveness of various recommendation techniques in providing personalized movie suggestions. These systems help users navigate the vast amount of information available and make better decisions based on their preferences.
