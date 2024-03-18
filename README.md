# Recommendations with IBM

## Project Overview
This project focuses on analyzing interactions between users and articles on the IBM Watson Studio platform to make personalized article recommendations. Utilizing user behavior and article content, we implemented several recommendation strategies including rank-based, user-user based collaborative filtering, and matrix factorization.

## Installation
The code was developed using Python 3.8. To run this project, the following libraries are needed:
- Pandas
- Numpy
- Matplotlib
- Seaborn
- Scikit-learn

You can install these packages using pip:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```
## Project Structure
Recommendations_with_IBM.ipynb: Jupyter notebook containing all the analysis and recommendation system implementation.

data/: Folder containing data files used for the analysis.

articles_community.csv: Dataset containing information about articles on the IBM platform.

user-item-interactions.csv: Dataset containing user interactions with articles.

README.md: This file, providing an overview of the project, instructions on how to install dependencies, and how to run the notebook.

## Results
The project explores different recommendation strategies:

Rank-Based Recommendations: Identifies the most popular articles based on user interactions.

User-User Collaborative Filtering: Recommends articles to a user that similar users have interacted with.

Matrix Factorization: Implements a machine learning approach to predict user-article interactions and make recommendations.

Through the analysis, we observed that the accuracy of predictions increases with the number of latent features for the training set, indicating potential overfitting issues when too many latent features are used.

## Conclusion
This project demonstrates the application of various recommendation techniques to personalize article recommendations for users of the IBM Watson Studio platform. Future work could explore more advanced recommendation methods, such as content-based filtering and hybrid models, to further improve recommendation quality.
