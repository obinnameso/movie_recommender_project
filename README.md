# Movie Recommender Project

## Project Description

In this project, we built a Movie Recommender which uses an unsupervised machine learning approach to provides personalized movie recommendations to users. There is an abundance of movie options available today and it can be overwhelming for users to decide what to watch. This project aims to solve that problem by suggesting movies based on user preferences and similarities between movies. <br>  

## Features

We used an unsupervised approach using two major types of recommender systems: Content-Based Filtering and Collaborative Filtering. In Content-Based Filtering, recommendations are made based on the similarity of movie properties and features. On the other hand, Collaborative Filtering makes recommendations based on the similarity between users with similar movie preferences. 
And made demonstration using Streamlit Web Application which Provides an interactive and user-friendly web interface for users to get movie recommendations. The system can also be used by organizations to enhance user retention and also customer satisfaction. <br> 

## Tools Used 

* Python
* Streamlit
* Scikit-learn
* GitHub
* AWS EC2
* Comet <br> 

## Installation 

1. pip install ipython 

2. Install the project dependencies including pandas, numpy, matplotlib, and scikit-learn using the following command:
pip install -U matplotlib numpy pandas scikit-learn <br> 

## Result 

Having done a thorough EDA on the dataset, we visualized the ratings in the given dataset as shown in the chart below:

<p align = 'center'>
<img src = "https://github.com/obinnameso/movie_recommender_project/blob/main/imgs/ratings_dist.png?raw=true">
</p>

We also visualized the number of movies in each movie genres as also shown in the chart below: 

<p align = 'center'>
<img src = "https://github.com/obinnameso/movie_recommender_project/blob/main/imgs/movie_count_by_genre.png?raw=true">
</p>

We trained some models for the collaborative filtering method of recommendation and the SVD (Sigular Value Decomposition) perfomred best using RSME score as a metric and was used in the streamlit app for demonstration of how the model works. We used comet to track the experiments using different models and the result is shown in the chart below: 

<p align = 'center'>
<img width = '800' height = '400' src = "https://github.com/obinnameso/movie_recommender_project/blob/main/imgs/comet_experiment.png?raw=true">
</p> <br> 

## Conclusion 

1. The unsupervised learning-based movie recommendation system has proven to be highly useful and effective in providing personalized movie suggestions to users. By leveraging collaborative filtering and matrix factorization techniques, the recommender successfully identified similar users and movies, offering tailored recommendations based on individual preferences and viewing history.

2. The recommender's utility is further evidenced by the visualizations that revealed meaningful insights into movie relationships and user preferences, reinforcing its value in enhancing user engagement and satisfaction. Its capacity to deliver relevant movie suggestions reflects its potential as a valuable tool in the movie streaming industry, catering to diverse user tastes and improving the overall viewing experience. <br> 

## Acknowledgement

I would like to also ackowledge my dynamic team of data and innovation enthusiasts, who worked together to drive positive impact through advanced data analysis and machine learning while working on the project:
* Oluwaseyi Olanike Rachael
* Musa Aliu
* Richard Sam 
* Mark Kasavuli <br> 

### Note: 
* Due to the nature of this project, code cannot be shared publicly.





