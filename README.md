# Machine Learning Homework (Week 21 HW) - Exoplanet Exploration

![PlanetsImage](https://physicsworld.com/wp-content/uploads/2018/02/2018-02-13-trappist.jpg)

#### Background
Over a period of nine years in deep space, the NASA Kepler space telescope has been out on a planet-hunting mission to discover hidden planets outside of our solar system. The purpose of this project was to create machine learning models capable of classifying candidate exoplanets from a raw dataset.

Data From: https://www.kaggle.com/nasa/kepler-exoplanet-search-results

##### Project Requirements:
Preprocess the raw data \
Tune the models \
Compare two or more models

##### Process:
Preprocessed the raw data \
Scaled numerical data \
Separated the data into training and testing \
Used GridSearch to hypertune some models \
Tune and compare models/classifiers

### Final Analysis
Deep Learning Model: Loss = 0.23553 Accuracy = 0.90503 \
KNN (K Nearest Neighbors) Model: Training Data Score = 0.84818 Testing Data Score = 0.82952 (k=13) \
Logistic Regression Model: Training Data Score = 0.84703 Testing Data Score = 0.86156 

Of the three models I have created for this data all three look good. Technically I would say any of these models could be used, however, as the Deep Learning Model has the highest accuracy I would say that one is the best method to use.
