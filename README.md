# movie-recommendation system
This project is a Movie Recommendation System built using collaborative filtering techniques. It suggests movies to users based on their ratings and viewing history.
# Overview
The Movie Recommendation System analyzes user ratings to suggest movies that users might like. It uses collaborative filtering to find similarities between users and movies, generating personalized recommendations.
Libraries Used
Pandas: Data manipulation and analysis
NumPy: Numerical computations
SciPy: Sparse matrix operations
Scikit-learn: Machine learning algorithms
Surprise: Building and analyzing recommender systems
Matplotlib and Seaborn: Data visualization
IPython: Display and notebook support
Functions and Methods
pd.read_csv(): Load datasets
pivot_table(): Reshape data for collaborative filtering
train_test_split(): Split data for model training and testing
SVD(): Singular Value Decomposition for collaborative filtering
accuracy.rmse(): Calculate Root Mean Squared Error for model evaluation
plt.hist(), sns.barplot(): Visualize data distributions
