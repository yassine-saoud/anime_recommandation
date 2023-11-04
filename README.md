# Anime Recommendation System

## Overview

This project aims to develop a recommendation system for anime, using two distinct approaches: data mining and Natural Language Processing (NLP). The primary goal is to provide anime enthusiasts with personalized recommendations based on their preferences and viewing history.

## Data Collection and Preprocessing

### Data Mining Approach
- **Scraping**: i Utilized Python, requests, and BeautifulSoup to collect anime data from the famous aime site web (https://myanimelist.net/).
- **Data Fields**: to cearte the dataset i gathered information such as title, genre, type, number of episodes, description, and producers.
- **Preprocessing**: then i performed data preprocessing to clean the dataset and optimize it for analytics and machine learning.

### NLP Approach
- **Text Data**: i leveraged the anime descriptions from the dataset.
- **NLP Steps**: the i applied NLP techniques to extract meaningful information from the descriptions.
- **Word Cloud**: i try many times to visualize important words in the descriptions using word clouds and retry the process to optimize results.
- **preapare the data**: i used the tfidfVectorizer to prepare the data to be trained by ML models.

## Recommendation Systems

### Data Mining Approach 
i created 2 models serving for different purposes
- **Modeling**: i Utilized cosine_similarity models to build a recommendation system.
- **Scoring**: i created a regression model to predict the anime score on anime features.

### NLP Approach
- **Natural Language Processing**: Applied NLP techniques to prepare the data and make it ready for training.
- **Cosine Similarity**: i utilized cosine similarity model to recommend anime based on descriptions.

## Results

After implementing both approaches, a comparative analysis was performed to evaluate the performance of the recommendation systems. The NLP-based approach yielded more promising and accurate results due to the rich information available in anime descriptions.

## Project Notebooks

- [Anime Recommendation (Data Mining Approach)](https://github.com/yassine-saoud/anime_recommandation/blob/main/anime_recommandation_data_mining_approach.ipynb): Detailed notebook covering the data mining approach.
- [Anime Recommendation (NLP Approach)](https://github.com/yassine-saoud/anime_recommandation/blob/main/anime_recommandation_using_NLP.ipynb): Comprehensive notebook explaining the NLP-based recommendation system.
- [amine dataset] (https://github.com/yassine-saoud/anime_recommandation/blob/main/animes_dataset.csv)


## Author

- [Yassine Saoud](https://github.com/yassine-saoud?tab=repositories)



