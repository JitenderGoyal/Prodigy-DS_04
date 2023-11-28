# Twitter Sentiment Analysis - EDA

This repository contains a Python script for performing a comprehensive Exploratory Data Analysis (EDA) on Twitter data. The script focuses on analyzing sentiments expressed in tweets about various topics or brands, providing insights into public opinion and trends.

## Overview

The script conducts a detailed analysis of a Twitter dataset, which includes sentiment labels for each tweet. It covers a range of visualizations and analyses to explore the sentiments, topics, and characteristics of the tweets.

## Features

- **Sentiment Distribution Visualization**: Analyzes the overall distribution of sentiments (Positive, Negative, etc.) in the dataset.
- **Topic-Based Sentiment Analysis**: Examines how sentiments are distributed across different topics.
- **Top Topics Visualization**: Identifies and visualizes the most frequently discussed topics.
- **Tweet Length Analysis**: Explores the distribution of tweet lengths and how they vary with sentiment.
- **N-Gram Analysis**: Discovers common bi-grams in the tweets.
- **Sentiment Intensity Analysis**: Utilizes NLTK's VADER tool to analyze the intensity of sentiments.
- **Pie Chart Visualization**: Shows the proportion of each sentiment category in the dataset.
- **Word Frequency Analysis**: Identifies and visualizes the most common words in the tweets.

## Data

The dataset used in this script should be in CSV format and contain the following columns:

- **ID**: A unique identifier for each tweet.
- **Topic**: The topic or brand each tweet is related to.
- **Sentiment**: The sentiment label for each tweet (e.g., Positive, Negative).
- **Tweet**: The text of the tweet.

## Dependencies

- Python 3
- Pandas
- Matplotlib
- Seaborn
- NLTK
- Scikit-learn

Ensure these libraries are installed to run the script successfully.

## Usage

1. Clone the repository.
2. Place your Twitter dataset in the specified format in the 'Dataset' folder.
3. Run the script to perform EDA on your data.

The script will generate various plots and visualizations, which will be displayed during execution.

## Contributing

Contributions, issues, and feature requests are welcome. Feel free to check [issues page](#) if you want to contribute.

## License

Distributed under the MIT License. See `LICENSE` for more information.
