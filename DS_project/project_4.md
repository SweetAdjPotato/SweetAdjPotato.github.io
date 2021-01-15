# Recommendation_with_IBM
Article recommendations to users on the IBM Watson Studio platform

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
5. [Licensing](#licensing)
6. [Acknowledgements](#Acknowledgements)

## Installation <a name="installation"></a>

1. Python versions 3.7
1. Library and packages: numpy, pandas, matplotlib, seaborn, sklearn

## Project Motivation<a name="motivation"></a>

For this project, I was interested in using the user article interaction data on the IBM Watson Studio platform to build out a recommendation engine using the following methods:

1. Rank based recommendation
2. User-user based Collaborative Filtering recommendation
3. Matrix Factorization using SVD


## File Descriptions <a name="files"></a>

* `Recommendations_with_IBM.ipynb` is the a jupyter notebook for the recommendation engine
* `data` folder contains the following:
  * `articles_community.csv`: csv file containing the articles
  * `user-item-interactions.csv`: csv file containing user interactions with articles
* `project_tests.py`: contains the unit tests
* `top_5.p`: pickle file to test top 5 rank based recommendations
* `top_10.p`: pickle file to test top 10 rank based recommendations
* `top_20.p`: pickle file to test top 20 rank based recommendations
* `user_item_matrix.p`: pickle file to load the user_item matrix

All the functions needed are written in the notebook along with the code.  

## License<a name="licensing"></a>

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Acknowledgements<a name="acknowledgement"></a>

Acknowledge to Udacity for the starter code, and IBM Watson Studio platform for providing the data.

Acknowledge to a few repos I studied on Github: [[1]](https://github.com/deogakofi/recommendations_IBM), [[2]](https://github.com/joshuayeung/Recommendations-with-IBM), [[3]](https://github.com/ajaySingh027/Recommendations-with-IBM).
