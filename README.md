# Sentiment Analysis and Visualization of Social Media Data

## Repository Overview
This repository contains a project focused on analyzing and visualizing sentiment patterns in social media data. The goal is to understand public opinion and attitudes towards specific topics or brands using sentiment analysis techniques on Twitter data.

## Files in the Repository
- **twitter_training.csv**: The dataset containing social media data, specifically tweets from Twitter, used for sentiment analysis. Each record contains a tweet along with its associated sentiment (e.g., positive, negative, neutral).
- **Task_4.ipynb**: A Jupyter Notebook that contains Python code for analyzing sentiment patterns in the Twitter data, as well as visualizing the results.

## Dataset Overview
The dataset (`twitter_training.csv`) contains the following columns:
- `tweet_id`: Unique identifier for each tweet.
- `username`: The Twitter handle of the user who posted the tweet.
- `tweet`: The text of the tweet.
- `sentiment`: The sentiment associated with the tweet (e.g., positive, negative, neutral).

### Example Dataset Structure:
| tweet_id | username     | tweet                             | sentiment |
|----------|--------------|------------------------------------|-----------|
| 12345    | @user1       | Love the new product!              | positive  |
| 12346    | @user2       | The service could be better.       | negative  |
| 12347    | @user3       | I think it's okay.                 | neutral   |
| ...      | ...          | ...                                | ...       |

### Key Information:
- The dataset contains a mix of textual data (`tweet`) and categorical data (`sentiment`).
- The goal is to analyze the sentiment expressed in each tweet and visualize the patterns of public opinion.

## Project Overview
The main objective of this project is to perform sentiment analysis on Twitter data and visualize the sentiment distribution to understand public opinion on various topics or brands. Key steps include:
1. **Data Loading**: Load the dataset using Python's `pandas` library.
2. **Data Cleaning**: Handle any missing values, text preprocessing, and data transformation (e.g., removing special characters, stopwords).
3. **Sentiment Analysis**: Analyze the sentiments expressed in the tweets, visualizing their distribution.
4. **Visualization**: Create visualizations such as bar charts and word clouds to explore sentiment patterns.

### Steps in the Notebook:
1. **Load Libraries**: Import required libraries such as `pandas`, `matplotlib`, `TextBlob`.
2. **Load Dataset**: Read the `twitter_training.csv` file into a DataFrame.
3. **Data Preprocessing**: Clean the tweet text by removing noise (e.g., URLs, special characters) and tokenize the text for analysis.
4. **Sentiment Distribution**: Analyze the distribution of sentiments (positive, negative, neutral) across the dataset.
5. **Visualization**:
   - **Bar Chart**: Create a bar chart to visualize the distribution of tweet sentiments.
   - **Word Cloud**: Generate a word cloud to visualize the most frequently used words in positive, negative, or neutral tweets.
6. **Insights**: Interpret the results and identify any patterns or trends in public opinion based on sentiment.

## How to Run the Notebook
1. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/deepjasani7/PRODIGY_DS_04
