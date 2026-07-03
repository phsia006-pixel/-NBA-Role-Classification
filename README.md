# NBA Player Role Classification

## Overview

This project uses NBA player statistics and machine learning methods to classify players into custom role archetypes. Instead of only grouping players by traditional positions such as guard, forward, or center, the project focuses on playstyle-based roles such as scorers, playmakers, slashers, defensive anchors, and stretch bigs.

The goal is to turn raw basketball statistics into meaningful player profiles that could help with scouting, player development, and lineup analysis.

## Player Archetypes

The project classifies players into custom archetypes including:

- 3-Level Scorer
- Playmaker
- Slasher
- Defensive Anchor
- Two-Way Wing
- Midrange Specialist
- 3-Point Specialist
- Stretch 5

## Dataset

The dataset contains per-36-minute NBA statistics for approximately 70 players, including 2025 rookies. The features include:

- Points
- Assists
- Blocks
- Field goal percentage
- 3-point percentage
- Free throw percentage
- Offensive rebounds
- Defensive rebounds
- Turnovers
- Steals
- Personal fouls

Using per-36-minute statistics allowed players with different playing times to be compared more fairly.

## Preprocessing

The preprocessing steps included:

- Cleaning and formatting numerical statistics
- Organizing player data into a structured CSV file
- Standardizing per-36-minute statistics
- Computing summary statistics for the dataset
- Preparing features for classification models

## Motivation

Traditional box score statistics do not always show the full picture of a player's role. Two players may have similar positions but very different playing styles. For example, one forward may mainly score from the perimeter, while another may contribute more through defense, rebounding, and cutting.

This project explores how machine learning can be used to identify player tendencies and group players into more descriptive basketball archetypes.

## Methods

This project was designed as a classification problem. The planned models included:

- k-Nearest Neighbors
- Logistic Regression / Softmax Classifier

The model is intended to output probabilities for each archetype because many NBA players fit multiple roles instead of only one category.

## Tools Used

- Python
- pandas
- NumPy
- scikit-learn
- CSV data processing
- Technical report writing
- Presentation design

## Files in This Repository

- `DataSheet.csv` — Player statistics dataset used for classification
- `EE16_Project_Report_NBA_Classification.pdf` — Final project report
- `EE016 Project Presentation` — Project presentation slides
- `README.md` — Project overview and documentation

## My Contribution

As part of this project, I contributed to organizing the dataset, defining player archetypes, analyzing relevant statistical features, and preparing the final report and presentation. The project helped me practice data preprocessing, classification concepts, and communicating technical results in a clear format.

## Skills Demonstrated

- Machine learning classification
- Data cleaning and preprocessing
- Feature selection
- Statistical analysis
- Technical writing
- Team-based project development
- Engineering presentation skills
