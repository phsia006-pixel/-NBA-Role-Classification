# Homework-File

 NBA Archetype Classification (EE016 Project)
Overview

Modern NBA teams analyze advanced metrics to understand player strengths, but traditional box score stats do not capture the full picture.
This project builds a machine learning model that classifies NBA players into custom archetypes such as:

3-Level Scorer

Playmaker

Slasher

Defensive Anchor (Paint)

Two-Way Wing

Midrange Specialist

3-Point Specialist

Stretch 5

The goal is to turn raw numerical statistics into meaningful player profiles that NBA teams can use for scouting, development, and lineup optimization.

 Dataset

Our dataset contains per-36-minute NBA statistics for ~70 players, including 2025 rookies.
Features include:

Points

Assists

Blocks

FG%, 3P%, FT%

Offensive & Defensive Rebounds

Turnovers

Steals

Personal Fouls

Preprocessing steps included:

Cleaning and formatting numerical features

Standardizing per-36 statistics


Computing dataset summary statistics

 Motivation

Teams often categorize players using subjective observations, but advanced analytics reveal deeper patterns.
Our objective is to:

Use machine learning to identify playstyles

Quantify how players fit certain archetypes

Help teams understand how a player fits into their system

Methods

This is a classification project. Planned models include:

k-Nearest Neighbors (k-NN)

Logistic Regression / Softmax Classifier

The model outputs probabilities for each archetype, since most NBA players exhibit multiple tendencies.

