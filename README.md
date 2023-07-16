# Movie Similarity from Plot Summaries


This repository contains a project that utilizes natural language processing (NLP) techniques to find the degree of similarity between movies based on their plot summaries obtained from IMDb and Wikipedia.

## Problem Statement

The goal of this project is to develop a system that can identify and quantify the similarities between movies by analyzing their plot summaries. By employing NLP techniques, the project aims to assist movie enthusiasts, researchers, and industry professionals in discovering related movies and identifying patterns within the plot descriptions.

## Dataset

The dataset used for this project is loaded from the `movies.csv` file. It contains information about 100 movies, including their titles, Wikipedia plot summaries, IMDb plot summaries, and other relevant details.

## Installation

To run this project locally, follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/movie-similarity.git
   ```

2. Navigate to the project directory:

   ```bash
   cd movie-similarity
   ```

3. Install the required dependencies. It is recommended to set up a virtual environment before installing the dependencies. Use a package manager of your choice (e.g., pip or conda) to install the necessary packages listed in the `requirements.txt` file:

   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Activate your virtual environment, if you set one up.

2. Open the Jupyter notebook `movie_similarity.ipynb`. This notebook contains the code for preprocessing the data, performing tokenization, stemming, converting text data into numeric representation, applying K-means clustering, calculating similarity, and plotting dendrograms.

3. Customize the analysis as needed. Feel free to modify the parameters, such as the number of clusters or the feature extraction techniques, to enhance the movie similarity results.

4. Save the preprocessed data and the trained model using the provided pickle files, `movie_plot.pkl` and `movie_plot_model.pkl`, respectively.

## Results

Upon executing the notebook, you will obtain the following outcomes:

- Movie Clustering: The notebook applies K-means clustering to group movies into clusters based on their plot summaries. Each movie is assigned to a specific cluster.

- Similar Movie Identification: By inputting the name of a movie, the system identifies the most similar movie within the same cluster. It returns the title of the most similar movie.

- Dendrogram Plot: The notebook generates a dendrogram, visually representing the hierarchical clustering of movies based on their similarity distances.

## Contributing

Contributions to this project are welcome. If you have any suggestions, bug reports, or feature requests, please open an issue on the GitHub repository.

## Contact

For any questions or inquiries, please contact (mailto:your-ayeshaf2529@gmail.com).

**Happy exploring movies!**
