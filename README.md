# Trending YouTube Video

The purpose of this project is to clean and transform data into a format that is suitable for machine learning models, and to identify the top 10 most popular products in a video dataset.

The data was taken from a Kaggle dataset of YouTube videos: https://www.kaggle.com/datasets/datasnaek/youtube-new?resource=download&select=USvideos.csv

The results of the project are the top 10 most popular product IDs in the video dataset. This information can be used by e-commerce companies to improve product placement on the website, develop new marketing campaigns, and make better business decisions.

## Steps:

1. Read the video data into a Pandas DataFrame.
2. Clean and preprocess the DataFrame.
3. Extract the video IDs from the DataFrame.
4. Count the number of times each video ID appears in the DataFrame.
5. Sort the product IDs by count, in descending order.
6. Print the top 10 most popular product IDs to the console.
