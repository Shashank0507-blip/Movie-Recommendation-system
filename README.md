## **General Introduction**:
This project implements a Movie Recommendation System using K-Means Clustering to group movies based on their genres and suggest similar movies to users. The project is built using Python and utilizes libraries such as pandas, NumPy, scikit-learn (for clustering), and Matplotlib & Seaborn (for visualization).

## **Features:**
* Uses K-Means Clustering to group movies based on genre similarity.
* Provides personalized movie recommendations by finding similar films within the same cluster.
* Displays the recommended movie titles along with their directors.
* Simple and efficient implementation using One-Hot Encoding for categorical data.
* Built using Python with industry-standard libraries for data science and machine learning.

## **How the Code works:**
* The dataset is preprocessed, keeping only Series_Title, Genre, and Director.
* The Genre column is one-hot encoded for clustering.
* The K-Means algorithm is applied to group similar movies.
* The user enters a movie title, and the system suggests similar movies from the same cluster.

Once clustering is complete, users can input a movie title, and the system will identify its cluster and recommend other movies from the same group. These recommendations include the movie title and director's name, making it easier for users to discover films with similar themes or creative styles. The project is implemented using Python, leveraging libraries such as pandas and NumPy for data handling, scikit-learn for clustering, and Matplotlib & Seaborn for visualization.

**Link to download the dataset: https://www.kaggle.com/datasets/harshitshankhdhar/imdb-dataset-of-top-1000-movies-and-tv-shows**
