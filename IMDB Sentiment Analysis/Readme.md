
#  IMDB Sentiment Analysis
![](https://cfml.se/img/blog/sentiment_classification/top_img.png)

**GOAL** 
- The main purpose of this project is to predict the sentiment of movie reviews on IMDB.


**WHAT I HAD DONE**
- Performed Exploratory Data Analysis on text data.
- Generated various wordclouds to know data better.
- Performed Text cleaning on the reviews text data.
- Removed stopwords, HTML strips and tags and noise from data.
- Built multiple models like LSTM, BERT, LinearSVC and compared them to get best results.


**LIBRARIES NEEDED**
- pandas
- NumPy
- matplotlib
- seaborn
- scikit-learn
- Tensorflow
- Keras
- re
- NLTK


**MODELS USED**


| Model | Train Score | Test Score |
| :---: | :---: | :---: |
| LSTM | 0.9319 | 0.8766 |
| LinearSVC | 0.9884 | 0.8952 |

## Wordclouds from movie reviews :

### Positive Reviews
![posituve](https://user-images.githubusercontent.com/60546202/153137028-ac7106e4-9522-4548-8a90-88b6e585ca54.png)

### Negative Reviews
![negative](https://user-images.githubusercontent.com/60546202/153137006-78ebb513-2850-4fb1-924f-467b5e367d63.png)


**CONCLUSION**
- Text cleaning performs major role in improvinh model performance to get better results.

