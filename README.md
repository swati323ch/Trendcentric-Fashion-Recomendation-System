# Trend-Centric Recommendation System 

Welcome to the Trend-Centric Recommendation project! This repository contains the implementation of a sophisticated recommendation system designed to deliver personalized product suggestions based on users' past purchases, browsing behavior, saved items, and preferences. 

This project also demonstrates a virtual try-on feature using computer vision techniques. Users can try on different virtual shirts overlaid on their live video feed from a webcam or recorded video.

"Visualization is the new trend, bringing digital experiences closer to reality."

## Features Of The Virtual Try-on
1. Overlay virtual shirts on detected poses in real-time video.
2. Navigate through a collection of shirts using interactive buttons.
3. Seamless resizing and positioning of shirts based on pose landmarks.

## Requirements For The Try-On
1. Python 3.x
2. OpenCV
3. cvzone (a Python library for computer vision tasks)
4. Pandas
5.scikit-learn

## Dataset Description for Recommendation System

### 1. Product Data
The product data contains detailed information about various products, such as unique identifiers, names, images, prices, ratings, brand names, and other attributes that help in making informed recommendations.

### 2. User Data
The user data includes information about users' interactions and preferences, including their purchase history, browsing behavior, saved items, and specific preferences, which are crucial for personalizing recommendations.

## Loading the Dataset and Preprocessing

We utilize the Pandas library to load and preprocess the datasets. This includes removing any missing values to ensure data integrity. Here's an overview of the process:

1. Load the product and user data from CSV files.
2. Drop any rows with missing values to maintain clean datasets.
3. Display the first few rows of the datasets for initial inspection and verification.

## Recommendation Methods

### Collaborative Filtering Method
1.This method makes recommendations based on users' purchase history and browsing behavior by identifying similar users and suggesting products that those users have interacted with but the current user has not.

### Content-Based Filtering
2.Content-based filtering recommends products based on user preferences and product attributes. It matches user preferences with product features to suggest items that align with the user's tastes.

### Hybrid Recommendation System
3.The hybrid recommendation system combines collaborative and content-based filtering methods to leverage the strengths of both approaches, providing more accurate and comprehensive recommendations.

## Evaluation

To evaluate the effectiveness of the recommendation system, we employ metrics such as accuracy. The evaluation process involves:
1. Comparing the recommended products against the actual products interacted with by the users.
2. Calculating the accuracy of the recommendations to determine the system's performance.

## Results

Below is an example of the recommended products for a user, displayed with images and product details.

![Recommended Products](img1.png)

![Recommended Products](website.png)

##

