# ChessPersona

![ChessPersona Logo](images/logo.png)

<div style="background-image:url('images/cover.png'); color: white; text-align: center; padding: 50px;">
    <h1>Welcome to ChessPersona</h1>
    <p>Discover the art of chess play styles through advanced analysis.</p>
</div>

## Overview
ChessPersona is a sophisticated tool designed to analyze chess games and identify the distinctive playing styles of chess players. By dissecting and examining various aspects of game play, ChessPersona offers insights into a player’s tactical and strategic preferences.

## Why ChessPersona?
In the world of chess, understanding a player's style is crucial for both training and competition. Coaches can tailor their training methods to suit the player’s natural inclinations, while players can gain insights into their strengths and weaknesses. Furthermore, enthusiasts and professional analysts can use these insights for commentary, game preparation, and in-depth player study.

## What It Does
ChessPersona parses chess games provided in PGN format, extracts key gameplay features, and classifies players into distinct style categories. This classification helps in understanding how different players approach the game under various circumstances.

## Feature Extraction
ChessPersona currently plans to extract the following features for each game:

- **Center Control Score**: Measures control over key central squares.
- **Piece Activity Score**: Assesses the mobility and activity of pieces throughout the game.
- **King Safety Score**: Evaluates the safety of the king based on surrounding pieces and pawn structure.
- **Attacking Moves Score**: Quantifies the aggressiveness of play.
- **Captures Score**: Tracks the number of captures made by a player, indicating tactical sharpness.
- **Pawn Structure Stability Score**: Analyzes the stability and weakness in the pawn structure.

## Model Possibilities
The features extracted from the gameplay are used to feed various machine learning models. We have several options for modeling:

- **Supervised Learning Models**: Such as SVM, Random Forest, and Gradient Boosting Machines for classifying players into style categories.
- **Neural Networks**: Including CNNs and RNNs for more complex feature interactions and deep learning-based style prediction.
- **Ensemble Techniques**: Combining multiple models to improve prediction accuracy and robustness.


