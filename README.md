# Spotify Track Popularity Prediction Project

## Overview
This project aims to predict the popularity of Spotify tracks using various machine learning models. The notebook presents a comprehensive analysis of the Spotify dataset, including data cleaning, feature engineering, regression modeling, and classification modeling.

## Dataset
The dataset includes Spotify tracks with attributes like artist information, track features (like danceability, energy, loudness), and track popularity. The data cleaning process involves merging artist and track data, handling missing values, and preparing features for modeling.

## Models and Analysis
We've implemented and compared several models:

1. **Regression Models:**
   - Ordinary Least Squares (OLS) Regression
   - Classification and Regression Tree (CART) - Regression Tree
   - A comparison of OLS vs. Regression Tree performance

2. **Classification Models:**
   - Logistic Regression
   - CART - Classification Tree
   - A comprehensive comparison of models to predict whether a track is popular

## Features
The project involves an exploration of various features that can influence a track's popularity, such as `danceability`, `energy`, `key`, `loudness`, `mode`, `speechiness`, `acousticness`, `instrumentalness`, `liveness`, `valence`, `tempo`, `time_signature`, and artist's `followers` and `popularity`.

## Key Findings
- The regression tree model outperforms the OLS model in terms of out-of-sample R-squared and testing RSS scores.
- The logistic regression model effectively classifies tracks as popular or not based on a defined popularity threshold.
- The project illustrates the importance of feature selection and the impact of different variables on the model's performance.

## Usage
To use this project, clone the repository and open the notebook in a Python environment with necessary libraries installed. Adjust the dataset path as per your directory structure.

## Requirements
- Python 3.x
- Libraries: pandas, numpy, sklearn, statsmodels, matplotlib

## Contributing
This project welcomes contributions, bug reports, and suggestions. Feel free to fork the repo and submit pull requests.

## Authors
- Toufiq Hossain
- Luna Ragot
- Abhigyan Biswas
- Mina Baghai
- Naya Lee

## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.
