<h1>
  <img src="images/logo.png" alt="ChessPersona Logo" width="50" style="vertical-align:middle"> ChessPersona
</h1>

## Welcome to ChessPersona
Discover the art of chess play styles through advanced analysis.
![ChessPersona Cover](images/cover.png)
# ChessPersona

Discover the art of chess play styles through advanced analysis.

## Welcome to ChessPersona

ChessPersona is a sophisticated tool designed to analyze chess games and identify the distinctive playing styles of chess players. By dissecting and examining various aspects of gameplay, ChessPersona offers insights into a player’s tactical and strategic preferences.

## Overview

ChessPersona leverages unsupervised learning techniques to group chess games by similar play styles. This approach helps uncover distinct patterns and strategies used by different players, providing a deeper understanding of chess dynamics without the need for predefined labels.

## Why ChessPersona?

In the world of chess, recognizing and understanding various playing styles is crucial for training, competition, and commentary. Coaches can better understand the natural play styles of players and tailor training accordingly. Players gain insights into their own strengths and weaknesses, while analysts and enthusiasts can deepen their understanding of strategic approaches across different levels of play.

## What It Does

ChessPersona parses chess games provided in PGN format, extracts key gameplay features, and clusters games into distinct style categories using advanced clustering algorithms. This helps identify common strategies and tactics among groups of players, enhancing our understanding of chess play dynamics.

## Feature Extraction

ChessPersona plans to extract the following features for each game, which are instrumental for the clustering process:

- **Center Control Score**: Measures control over key central squares.
- **Piece Activity Score**: Assesses the mobility and activity of pieces throughout the game.
- **King Safety Score**: Evaluates the safety of the king based on surrounding pieces and pawn structure.
- **Attacking Moves Score**: Quantifies the aggressiveness of play.
- **Captures Score**: Tracks the number of captures made by a player, indicating tactical sharpness.
- **Pawn Structure Stability Score**: Analyzes the stability and weakness in the pawn structure.

## Modeling Approaches

The extracted features are used to feed various unsupervised machine learning models to identify distinct clusters of playing styles:

- **K-means Clustering**: A popular clustering method that groups data based on feature similarity.
- **Hierarchical Clustering**: This technique builds a tree of clusters and is particularly useful for understanding the nested relationships between different playing styles.
- **DBSCAN**: Useful for identifying clusters of arbitrary shape and for handling noise and outliers in the dataset.

By employing these models, ChessPersona aims to reveal nuanced insights into the diverse strategies employed by chess players around the world.


