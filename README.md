# dataScienceProject3
## Recommendations with IBM Udacity DataScience Nanodegree project

### Introduction:
The aim of this project is to analyse the interactions that users have with articles on the IBM Watson Studio platform, and to make recommendations to them about new articles they will like. All the work is included in "Recommendations_with_IBM.ipynb" and is divided into five sections.

I. Exploratory Data Analysis

Before making recommendations of any kind, data exploration is necessary. This space is used to see the data sets insights, before diving into the details of the recommendation system in the later sections.

II. Rank Based Recommendations

To get started in building recommendations, first step is to find the most popular articles simply based on the most interactions. Since there are no ratings for any of the articles, it is easy to assume the articles with the most interactions are the most popular. These are then the articles we might recommend to new users (or anyone depending on what we know about them).

III. User-User Based Collaborative Filtering

In order to build better recommendations for the users of IBM's platform, we could look at users that are similar in terms of the items they have interacted with. These items could then be recommended to the similar users. This would be a step in the right direction towards more personal recommendations for the users.

IV. Content Based Recommendations (EXTRA - NOT REQUIRED)

Skipped for now

V. Matrix Factorization

Last step is to complete a machine learning approach to building recommendations. Using the user-item interactions, a matrix decomposition is going to be build out. This will give an idea of how well new articles can be predicted for an individual. Finally, there is a test proceeded how well created recommendations are working for engaging users.

### Instructions:
Please run cells in jupyter-notebook "Recommendations_with_IBM.ipynb" in order to see the results.

### Project components:
- Recommendations_with_IBM.ipynb - jupyter-notebook file that consists main work
- projects_tests.py - python tests file, used to determine whether the code implemented in jupyter-notebook is correct
- other files, such as top_10.p, top_20.p, etc are needed to test an output from jupyter-notebook

### Software and libraries:
The project uses Python3.
Used libraries:
- numpy
- pandas
- pickle
- project_tests
- matplotlib 

### Data:
Both .csv files are provided by IBM Watson Studio company
* 'data/user-item-interactions.csv'
* 'data/articles_community.csv'

### Results:
All results are visible in the generated .pdf file