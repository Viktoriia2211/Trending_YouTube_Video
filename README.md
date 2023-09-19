# Trending YouTube Video

 The purpose of this project is to clean and transform data into a format that is suitable for machine learning models, and to identify the top 10 most popular products in a video dataset.
  Data was taken from here: https://www.kaggle.com/datasets/datasnaek/youtube-new?resource=download&select=USvideos.csv
  The results of the project are the top 10 most popular product IDs in the video dataset. This information can be used by e-commerce companies to improve product placement on the website, develop new marketing campaigns, and make better business decisions.
   
   The following steps were performed:

1. The video data was read into a Pandas DataFrame.
2. The DataFrame was cleaned and preprocessed.
3. The video IDs were extracted from the DataFrame.
4. The number of times each video ID appeared in the DataFrame was counted.
5. The product IDs were sorted by count, in descending order.
6. The top 10 most popular product IDs were printed to the console.
