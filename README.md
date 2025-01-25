# Content of the README file for the Movie Recommendation System repository.


# Movie Recommendation System

This repository contains the implementation of a Movie Recommendation System. The system utilizes various machine learning techniques to recommend movies to users based on their preferences, either through collaborative filtering or content-based methods.

![image alt](https://github.com/vinutmaradur/Movie_Recommendation_System/blob/main/Screenshot%201.png?raw=true)

## Features

- **Interactive User Interface**: The user can input their preferences and get personalized movie recommendations.
- **Data Processing**: The project uses movie datasets to build recommendation models.
- **Machine Learning Models**: Utilizes collaborative filtering and/or content-based recommendation algorithms.
- **Visualization**: Displays relevant movie information, including poster images, ratings, genres, etc.


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

## Project Structure

```
movie-recommendation-system/
│
├── app.py                # Streamlit app file
├── recommendation_model/ # Folder containing the machine learning model code
│   ├── collaborative_filtering.py
│   └── content_based_filtering.py
├── data/                 # Folder containing datasets (e.g., movie data, ratings data)
│   └── movies.csv
│   └── ratings.csv
├── notebooks/            # Folder containing Jupyter Notebooks for data exploration and model building
│   └── Netflix Movie Recommendation System - Content Based Filtering.ipynb
├── requirements.txt      # File with project dependencies
└── README.md             # Project readme (this file)

```

# Example Data:

Example Movie Data:

| Movie Title |	Genre	| Release Date	| Popularity |	Vote Average |	Vote Count |
| :- | :- | :- | :- | :- | :- |
| The Dark Knight |	Action | 2008-07-18 | 47.55 | 8.5 |	2226 |
| Inception |	Action | 2010-07-16 |	38.74 |	8.2 |	1489 |
| Fight Club	| Drama	| 1999-10-15	| 35.99	| 8.4	| 1994 |

Dataset Link:
You can access the TMDB 5000 Movie Dataset on Kaggle here.



## Requirements

The project requires the following libraries to be installed:

- Streamlit
- pandas
- numpy
- scikit-learn


You can install the dependencies by running the following command:

```
pip install -r requirements.txt

```

## Setup and Run

1. Clone this repository:

```
git clone https://github.com/your-username/movie-recommendation-system.git
```

2. Install the required dependencies:

```
pip install -r requirements.txt
```

3. Run the Streamlit app:

```
streamlit run app.py
```

## Example

After running the system, you will get movie recommendations like the following:

```bash
Recommended Movies:
1. Movie Title 1
2. Movie Title 2
3. Movie Title 3
```

4. The app will be available in your browser at `http://localhost:8501`.

## Jupyter Notebooks

You can explore the data and build the recommendation models using the Jupyter Notebooks available in the `notebooks/` folder. 

### Notebooks Included:
- **data_exploration.ipynb**: This notebook explores the movie datasets and performs initial data cleaning and preprocessing.
- **model_building.ipynb**: This notebook demonstrates how the recommendation models are built and tested.

## License

This project is licensed under the MIT License.

## Acknowledgments

- Movie dataset sourced from [kaggle](https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata)
- Streamlit for interactive web app development
- scikit-learn for machine learning algorithms
  
The file for similarity.pkl is provided below download 
[Download File](https://drive.google.com/file/d/1G9dQO6tn1rrNJgi5LZyXpanJdBQlGyVk/view?usp=sharing)
