# Cricket Player Performance Clustering Using K-Means

## Overview

This project applies the K-Means Clustering algorithm to analyze and group cricket players based on their performance statistics. The objective is to identify different categories of players such as elite batters, elite bowlers, and emerging players using unsupervised machine learning techniques.

## Project Objectives

* Perform exploratory data analysis on cricket player statistics.
* Preprocess and scale numerical features.
* Determine the optimal number of clusters using the Elbow Method.
* Train a K-Means clustering model.
* Visualize player clusters.
* Save the trained model for future predictions.

## Technologies Used

* Python
* Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Scikit-learn
* Pickle

## Dataset Features

The dataset contains the following attributes:

* Player Name
* Matches
* Runs
* Strike Rate
* Average
* Wickets
* Economy Rate

## Machine Learning Workflow

### 1. Data Loading

Load the cricket player dataset into a Pandas DataFrame.

### 2. Data Exploration

Analyze dataset structure, statistics, and missing values.

### 3. Feature Selection

Select relevant numerical features for clustering.

### 4. Feature Scaling

Apply StandardScaler to normalize feature values.

### 5. Elbow Method

Determine the optimal value of K for clustering.

### 6. Model Training

Train the K-Means clustering model.

### 7. Cluster Analysis

Interpret clusters based on player performance metrics.

### 8. Model Persistence

Save the trained K-Means model and scaler using Pickle.

## Project Structure

Cricket-Player-Clustering/

├── cricket_players.xlsx

├── cricket_player_clustering.ipynb

├── kmeans_model.pkl

├── scaler.pkl

├── clustered_players.csv

└── README.md

## Results

The K-Means algorithm successfully groups players into performance-based clusters. These clusters can be interpreted as:

* Cluster 0 – Elite Batters
* Cluster 1 – Elite Bowlers
* Cluster 2 – Emerging Players

The exact interpretation may vary depending on the dataset used.

## Model Saving

The trained model and scaler are saved as:

* kmeans_model.pkl
* scaler.pkl

These files can be loaded later to classify new player statistics into existing clusters.

## Future Enhancements

* Use real IPL and international cricket datasets.
* Apply PCA for advanced cluster visualization.
* Build a Streamlit web application.
* Deploy the model using Docker and Azure.
* Automate retraining using MLOps practices.

## Author

Dineshkarthick

