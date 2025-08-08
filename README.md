# Google_Play_Store_Apps
This project analyzes user reviews for Google Play Store apps to understand sentiment. It begins by loading and cleaning the data, handling missing values and duplicates. The analysis explores the distribution of sentiment polarity, the sentiment breakdown for the top 10 apps, and the relationship between sentiment polarity and subjectivity. Visualizations such as histograms, countplots, boxplots, and scatterplots are used to gain insights into user opinions and app performance based on reviews.
# Dataset Description
The dataset used in this project is googleplaystore_user_reviews.csv. It contains user reviews for Google Play Store apps and includes the following columns:
1)App: The name of the application (object/string).
2)Translated_Review: The translated text of the user review (object/string).
3)Sentiment: The sentiment of the review (Positive, Negative, or Neutral) (object/string).
4)Sentiment_Polarity: A numerical score representing the polarity of the sentiment (-1.0 to 1.0, where -1.0 is negative, 0.0 is neutral, and 1.0 is positive) (float64).
5)Sentiment_Subjectivity: A numerical score representing the subjectivity of the review (0.0 to 1.0, where 0.0 is objective and 1.0 is subjective) (float64).
# Analysis Objectives
The analysis objectives of this project include:
1)Understanding the distribution of sentiment polarity across all user reviews.
2)Identifying the sentiment breakdown (Positive, Negative, Neutral) for the top 10 apps with the most reviews.
3)Exploring the relationship between sentiment category and sentiment polarity to see how polarity scores vary for positive, negative, and neutral reviews.
4)Investigating the relationship between sentiment category and sentiment subjectivity to see how subjective the reviews are within each sentiment category.
5)Visualizing the relationship between sentiment polarity and sentiment subjectivity to understand how these two metrics relate to each other for different sentiments
# Technologies Used
The technologies and libraries used in this project are primarily Python libraries for data analysis and visualization:
1)pandas: Used for data loading, cleaning, and manipulation.
2)numpy: Used for numerical operations (though not explicitly used in complex ways in the provided code, it's a fundamental library often used with pandas).
3)matplotlib.pyplot: Used for creating static, interactive, and animated visualizations.
4)seaborn: Built on top of matplotlib, it's used for creating aesthetically pleasing and informative statistical graphics.
