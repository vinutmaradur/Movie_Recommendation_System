# Content of the README file for the Movie Recommendation System repository.


# Movie Recommendation System

This repository contains the implementation of a Movie Recommendation System. The system utilizes various machine learning techniques to recommend movies to users based on their preferences, either through collaborative filtering or content-based methods.

## Features

- **Collaborative Filtering**: Recommends movies based on the ratings of other users.
- **Content-based Filtering**: Recommends movies based on the similarity of the movie's attributes (genres, director, actors, etc.) to movies the user has liked.
- **Hybrid Approach**: Combines both collaborative and content-based filtering methods to generate better recommendations.
- **Data Visualization**: Includes visualizations to analyze the movie ratings, distribution, and recommendations.

## About Dataset

TMDB 5000 Movie Dataset
The TMDB 5000 Movie Dataset is a dataset available on Kaggle, containing detailed information about 5,000 movies from The Movie Database (TMDb). This dataset is widely used in machine learning, data science, and movie recommendation projects.

Dataset Overview:
- **Source**: The dataset is sourced from The Movie Database (TMDb), a popular community-driven movie database.
- **Size**: The dataset contains data for 5,000 movies.
- **Content**: The dataset includes a variety of features related to movies, such as:
- **Movie Title**: Name of the movie.
- **Overview**: A brief description of the movie.
- **Genres**: A list of genres associated with each movie (e.g., Action, Comedy, Drama).
- **Release Date**: The release date of the movie.
- **Popularity**: A measure of how popular the movie is.
- **Vote Average**: The average rating for the movie.
- **Vote Count**: The number of votes the movie received.
- **Budget**: The budget allocated for the movie.
- **Revenue**: The revenue earned by the movie.
- **Production Companies**: The companies involved in producing the movie.
- **Cast and Crew**: Information about the actors, directors, and other key personnel.
  
Dataset Usage:
The TMDB 5000 Movie Dataset is used for various tasks, such as:

- **Movie Recommendation**: Using features like genres, votes, and popularity to recommend movies to users.
- **Predictive Analysis**: Building models to predict movie success based on budget, genre, and cast.
- **Data Visualization**: Analyzing and visualizing data trends, such as the distribution of movie genres, revenue, or ratings over time.

Example Data:

# Example Movie Data:

| Movie Title |	Genre	| Release Date	| Popularity |	Vote Average |	Vote Count |
| :- | :- | :- | :- | :- | :- |
| The Dark Knight |	Action | 2008-07-18 | 47.55 | 8.5 |	2226 |
| Inception |	Action | 2010-07-16 |	38.74 |	8.2 |	1489 |
| Fight Club	| Drama	| 1999-10-15	| 35.99	| 8.4	| 1994 |

Dataset Link:
You can access the TMDB 5000 Movie Dataset on Kaggle here.



## Requirements

Before running the Movie Recommendation System, make sure you have the following libraries installed:

- Python 3.x
- pandas
- numpy
- scikit-learn


You can install the necessary libraries using pip:

```bash
pip install -r requirements.txt
## Dataset

This system uses the [Kaggle dataset]([https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata?select=tmdb_5000_credits.csv]) which contains movie ratings and information about movies such as genre, title, and tags. Make sure to download and prepare the dataset before running the system.

## How to Use

1. Clone the repository:

```bash
git clone https://github.com/yourusername/movie-recommendation-system.git
```

2. Navigate to the project directory:

```bash
cd movie-recommendation-system
```

3. Run the main script to start the recommendation process:

```bash
python recommend_movies.py
```

4. The system will prompt you for user input, such as rating or movie preferences. Based on this input, the system will generate personalized movie recommendations.

## Example

After running the system, you will get movie recommendations like the following:

```bash
Recommended Movies:
1. Movie Title 1
2. Movie Title 2
3. Movie Title 3
```

## Contributing

Contributions are welcome! If you have any suggestions or improvements, feel free to fork this repository and create a pull request. Please make sure to follow the code of conduct and adhere to the project's coding standards.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements

- The kaggle dataset is provided by GroupLens Research.
- The system leverages several libraries for data science, machine learning, and web development.

The file for similarity.pkl is provided below download 
[Download File](https://drive.google.com/file/d/1G9dQO6tn1rrNJgi5LZyXpanJdBQlGyVk/view?usp=sharing)
