# Netflix-movies-and-TV-shows-clustering



![image](https://user-images.githubusercontent.com/115976515/227211929-23efc81b-e1a4-4bf8-95a6-fb146cea3978.png)

# Project Summary -
Netflix, the world’s largest on-demand internet streaming media and online DVD movie rental service provider.it Founded August 29, 1997, in Los Gatos, California by Marc and Reed. It has 69 million members in over 60 countries enjoying more than 100 million hours of TV shows and movies per day Netflix is the world’s leading internet entertainment service with enjoying TV series, documentaries, and feature films across a wide variety of genres and languages. I was curious to analyze the content released in Netflix platform which led me to create these simple, interactive, and exciting visualizations and find similar groups of people.

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Fixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset. Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

One of the most significant benefits of clustering for Netflix is that it allows the platform to provide personalized recommendations to users based on their viewing history and preferences. By analyzing users' data and identifying patterns and similarities between different titles, Netflix can recommend content that is more likely to match users' interests. This approach leads to increased user engagement and satisfaction, which can ultimately lead to increased retention and company revenue.

In conclusion, Netflix Movies and TV Shows Clustering is a powerful tool that enables the platform to group its vast library of content into similar categories, providing users with personalized recommendations and improving the overall user experience. This approach is data-driven and relies on unsupervised machine learning algorithms such as k-means, hierarchical clustering, and recommender system to identify patterns and similarities between different titles. Clustering helps Netflix make informed decisions about content production and licensing and ultimately leads to increased customer retention and company revenue.


# Problem Statement

As one of the world's largest streaming platforms, Netflix offers a vast library of movies and TV shows. However, with so many options to choose from, it can be challenging for users to find content that matches their preferences.

To address this challenge, this project aims to use unsupervised learning techniques to cluster similar movies and TV shows on Netflix. By grouping titles with similar attributes, we can provide users with more targeted recommendations, and help them find new content they will enjoy.

Specifically, this project will involve analyzing a dataset of Netflix titles, including features such as genre, release year, cast, and plot summary, among others. By applying clustering algorithms such as K-Means or Hierarchical clustering, we aim to identify groups of movies and TV shows with similar attributes.

In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset.
 
Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.


# Conclusion

## CONCLUSION FROM EDA:

1) Netflix has more movies than TV shows available on the platform.

2) The majority of content on Netflix is suitable for mature audiences, with a TV-MA rating being the most common.

3) The United States is the country with the highest number of productions available on Netflix, followed by India and the United Kingdom.

4) Netflix has seen a steady increase in its content library since its inception in 2008.

5) The most common genre of content on Netflix is Dramas, followed by Comedies and Documentries.

6) The Wordcloud visualization of movie descriptions shows that some of the most common words used in Netflix movie descriptions include love, family, young, life, and world.

7) The correlation heatmap shows that there is a moderate positive correlation between the duration of a movie and its release year.

8) The pairplot shows some interesting patterns between variables such as the strong positive correlation between the number of reviews and the year of release, as well as a negative correlation between the rating and duration of a movie.

## CONCLUSION FROM MODEL IMPLEMENTATION:

1) The data was clustered based on the attributes: director, cast, country, genre, rating, and description.

2) TFIDF vectorizer was used to tokenize, preprocess, and vectorize the values in these attributes, creating a total of 20000 attributes.

3) Principal Component Analysis (PCA) was used to reduce the dimensionality of the data which captured more than 80% of the variance.

4) K-Means Clustering algorithm was used to build clusters with the optimal number of clusters being 6 based on the elbow method and Silhouette score analysis.

5) Agglomerative clustering algorithm was used to build clusters with the optimal number of clusters being 12 based on the dendrogram visualization.

6) A content-based recommender system was built using cosine similarity and will make 10 recommendations to the user based on the type of show they watched.
