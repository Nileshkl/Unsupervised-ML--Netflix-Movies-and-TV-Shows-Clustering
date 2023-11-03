
# :star: Netflix Movies & TV Shows Clustering :star:
## :star: Unsupervised ML Capstone Project:star:
![Netflix Logo](https://github.com/Nileshkl/Unsupervised-ML--Netflix-Movies-and-TV-Shows-Clustering/blob/c7ca31f07a8c84abf8277d572a238b018fd95e0e/netflix-intro-netflix.gif)

This project aims to analyze the Netflix Dataset of movies and TV shows until 2019, obtained from the third-party search engine Flixable. The primary objective is to group the content into relevant clusters using NLP techniques to enhance the user experience through a recommendation system. This system will help mitigate subscriber churn for Netflix, which currently boasts over 220 million subscribers.

Moreover, this project seeks to uncover valuable insights and trends in the streaming entertainment industry by analyzing the dataset.

This dataset consists of tv shows and movies available on Netflix as of 2019. The dataset is collected from Fixable which is a third-party Netflix search engine. In 2018, they released an interesting report which shows that the number of TV shows on Netflix has nearly tripled since 2010. The streaming service’s number of movies has decreased by more than 2,000 titles since 2010, while its number of TV shows has nearly tripled. It will be interesting to explore what all other insights can be obtained from the same dataset. Integrating this dataset with other external datasets such as IMDB ratings, rotten tomatoes can also provide many interesting findings.

This dataset contains information about movies and TV shows available on Netflix. It includes the following columns:

- **show_id**: {data['show_id']}
- **type**: {data['type']}
- **title**: {data['title']}
- **director**: {data['director']}
- **cast**: {data['cast']}
- **country**: {data['country']}
- **date_added**: {data['date_added']}
- **release_year**: {data['release_year']}
- **rating**: {data['rating']}
- **duration**: {data['duration']}
- **listed_in**: {data['listed_in']}
- **description**: {data['description']}

## Project Overview

The project was carried out in the following step-by-step process:

1. **Handling Null Values:** Null values in the dataset were addressed to ensure data integrity and accuracy.

2. **Managing Nested Columns:** Columns containing nested data, such as director, cast, listed_in, and country, were processed to enable better visualization and analysis.

3. **Binning Ratings:** The rating attribute was binned into categories such as adult, children's, family-friendly, and not rated to facilitate analysis and recommendation.

4. **Exploratory Data Analysis (EDA):** EDA techniques were employed to gain insights and understand patterns and trends in the dataset, with the goal of preventing subscriber churn.

5. **Creating Clusters:** Clustering techniques were applied to group the content based on attributes like director, cast, country, genre, rating, and description. These attributes were tokenized, preprocessed, and vectorized using the TF-IDF vectorizer.

6. **Dimensionality Reduction:** The dimensionality of the dataset was reduced using Principal Component Analysis (PCA) to improve performance and eliminate noise.

7. **Clustering Algorithms:** Both K-Means Clustering and Agglomerative Hierarchical Clustering algorithms were utilized to create clusters. The optimal number of clusters was determined (4 for K-Means and 2 for hierarchical clustering) using various evaluation methods.

8. **Content-Based Recommender System:** A content-based recommender system was developed using the cosine similarity matrix to provide personalized recommendations to users. The aim was to reduce subscriber churn by offering relevant and engaging content.

The comprehensive analysis and recommendation system developed in this project are expected to enhance user satisfaction and ultimately improve subscriber retention rates for Netflix.

## Conclusion

Through the in-depth analysis of the Netflix dataset and the creation of a content-based recommendation system, this project strives to boost user satisfaction and minimize subscriber turnover for Netflix. The content clustering enhances organization, and the personalized recommendations are geared toward user preferences. The anticipated outcome is an increase in user retention rates, ultimately strengthening Netflix's position as a top streaming entertainment platform.

Start exploring the project for more details and insights!

Feel free to contribute, report issues, or ask questions. Happy coding!

[![LinkedIn Badge](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nileshkumar-lavand/)
