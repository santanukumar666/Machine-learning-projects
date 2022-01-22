# Netflix EDA and Recommendation System

**GOAL**: The project aims to gain insights from detailed EDA and recommend which movie to watch next.

**DATASET** : Kaggle link [here](https://www.kaggle.com/shivamb/netflix-shows)

## EXPLORATORY DATA ANALYSIS
- explored the dataset and handeled missing values in suitable manner.
- Cleaned and manipulated the data to perform Exploratory data analysis.
- Some Data visualization techniques were applied and inferences about the dataset were drawn.
- predictive models were built using some standard machine learning algorithms and built a content based predictive system.

- Simple plot(description) based Recommendation System
  
  - It recommends the top contents based on TF-IDF matrix based cosine similarity score.
  - After calculating the weighted score for every movie, based on score it recommends the movies. This Simple Recommendation system gives good results but to improve the 
  recommendation we need to build something more better.
  
- Multiple metrics(Genre,cast,director) based Recommendation System
 
  - It will compute the cosine similarity scores for all movies based on the features in our dataset.
  - cleaned the data first and used CountVectorizer() and computed cosine similarity score.
  - This improved Model gives better recommendations and can be considered.
  
  
