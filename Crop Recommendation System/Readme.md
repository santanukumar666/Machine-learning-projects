# Crop Recommendation System
Data mining is the practice of examining and deriving purposeful information from the data. Data mining finds its application in various fields like finance, retail, medicine, agriculture etc. Data mining in agriculture is used for analyzing the various biotic and abiotic factors. Agriculture in India plays a predominant role in economy and employment. The common problem existing among the Indian farmers are they don't choose the right crop based on their soil requirements. Due to this they face a serious setback in productivity. This problem of the farmers has been addressed through precision agriculture. Precision agriculture is a modern farming technique that uses research data of soil characteristics, soil types, crop yield data collection and suggests the farmers the right crop based on their site-specific parameters. This reduces the wrong choice on a crop and increase in productivity. In this paper, this problem is solved by proposing a recommendation system through an ensemble model with majority voting technique using Random tree, CHAID, K-Nearest Neighbor and Naive Bayes as learners to recommend a crop for the site specific parameters with high accuracy and efficiency.

![crop1](https://user-images.githubusercontent.com/60546202/153705775-a64f0b85-df82-4709-bc31-3569a18f9921.jpg)

## Goal
The Goal of this project is to build the recommendation model using the crop recommendation dataset.

## Dataset
The dataset which is used in this project, is collected from Kaggle,[here](https://www.kaggle.com/atharvaingle/crop-recommendation-dataset)

## What have I done

2. Importing the dataset in the Jupyter Notebook.
3. After that I have divided the project in two halves -
	- Part A :: Exploratory Data Analysis
		- Visualizing the Ratio of Nitrogen and Phosphorous in the soil
		- Visualizing the Ratio of Potassium and Temperature in the soil
		- Visualizing the Humidity and pH in the soil
		- Visualizing the Rainfall
		- Introducing Label Encoder
	- Part B :: Prediction Models
		- Training and Testing Dataset Spliting using the train_test_split
		- K-Nearest Neighbour Algorithm
   		- Decision Tree Classifier
		- Random Forest Classifier
		- Gausian NB Algorithm
		- Logistic Regression
		- Support Vector Machine
		- Artificial Neural Network
4. Conclusion


## Libraries used
1. Numpy
2. Pandas
3. Matplotlib
4. sklearn
5. seaborn

## Visualization
- Visualizing the Ratio of Nitrogen and Phosphorous in the soil
![crop21](https://user-images.githubusercontent.com/60546202/153705776-90e8cbd1-c21b-42d6-956c-0dbff64ecd1d.png)

- Visualizing the Ratio of Potassium and Temperature in the soil
![crop3](https://user-images.githubusercontent.com/60546202/153705777-74b55299-b8cd-44b7-847c-170e3e04bdd2.png)


- Visualizing the Humidity and pH in the soil
![crop4](https://user-images.githubusercontent.com/60546202/153705783-6b3fd3a2-52ee-40ae-9002-028e465e1d21.png)

- Visualizing the Rainfall

![crop5](https://user-images.githubusercontent.com/60546202/153705787-6149e7b0-0bf9-4436-9e50-ba5a0a7860c4.png)

## Model Comparison
We have deployed seven machine learning algorithms and every algorithm is deployed successfully without any hesitation. We have checked the accuracy of the models based on the accuracy score of each of the models. Now let's take a look at the scores of each models.

|Name of the Model|Accuracy Score|
|:---:|:---:|
|Logistic Regression|97.5|
|Decision Tree Classifier|98.4|
|Random Forest Classifier|99.3|
|Naive Bayes Algorithm|99.5|
|KNN Algorithm|97.0|
|Support Vector Machine Algorithm|96.1|
|Artificial Neural Network|94.5|

## Conclusion
**Comparing all those scores scored by the machine learning algorithms, it is clear that Naive Bayes Algorithm is having the upper hand in case of this dataset and after this, we can use Logistic Regression, Random Forest Classifier, SVM, which are also having good score as compared to the other deployed algorithms**

Best Fitted Models ranking - 
1. Gausian Naive Bayes
2. Random Forest Classifier
3. Decision Tree Classifier
4. Logistic Regression
5. K-Nearest Neighbours
6. Support Vector Machine
7. Artificial Neural Network


