# social-media-analysis

## Emotional Analysis of Social Media Posts and Comments

##  Overview

This project focuses on conducting emotional analysis of social media posts and their associated comments. The goal is to identify dominant emotions, analyze their distributions across various communities and political leanings, and derive insights into emotional polarization and user behavior.

## Dataset

The dataset includes:

##  Posts:

id: Unique identifier for each post.

username: Name of the user who posted the content.

leaning: Political leaning of the post (e.g., left, right, neutral).

community: Identifier for the community the user belongs to.

## Emotion probabilities:

anger

disgust

fear

joy

neutral

sadness

surprise

##  Comments:

Textual data for comments related to posts.

Emotion probabilities for each comment, using the same categories as posts.

##  Methods

Data Preprocessing:

Cleaning and organizing post and comment data.

Aggregating comment emotions and aligning them with their respective posts.

## Emotional Analysis:

Identifying the dominant emotion for each post and comment based on the highest probability.

Normalizing emotion distributions for fair comparisons.

## Comparative Analysis:

Community-wise comparisons of emotional distributions.

Analysis of emotions across political leanings.

Comparison of dominant emotions in posts versus comments.

##  Visualizations:

Bar charts and pie charts for emotion distributions.

Heatmaps to compare emotions across communities and political leanings.

Tools and Technologies

Programming Language: Python

## Libraries:

Pandas: For data manipulation.

Matplotlib and Seaborn: For data visualization.

Hugging Face Transformers: For emotion classification.

Models: Pretrained emotion analysis model from Hugging Face.

Key Findings

## Dominant emotions often align with the political leaning of the post.

Community-based analysis reveals variations in emotional expressions.

Emotional polarization is evident in comments on politically leaning posts.


