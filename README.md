# Analyzing Spotify Music

This project explores Spotify music data using exploratory data analysis
(EDA) techniques. It was developed in Google Colab as part of a data
science learning exercise.

## 📊 Project Overview

The main goals of this project are to: - Perform data cleaning and
preprocessing - Explore the structure of the Spotify dataset - Visualize
key audio features (e.g., danceability, energy, valence, loudness,
tempo) - Identify patterns and relationships across tracks, artists, and
genres - Draw insights into what factors might influence music
popularity

## 🛠️ Tools & Libraries

The project is built in **Python** using: - `pandas` for data
manipulation - `numpy` for numerical operations - `matplotlib` &
`seaborn` for visualization - `plotly` for interactive plots -
`scikit-learn` (if applied) for scaling or modeling

## 📂 Project Structure

-   `Project1_EDA.ipynb` -- Jupyter Notebook with full analysis
-   `data/` -- dataset files (if included, otherwise specify source)
-   `images/` -- exported plots and charts (optional)

## 🚀 Getting Started

1.  Clone the repository:

    ``` bash
    git clone https://github.com/yourusername/spotify-eda.git
    cd spotify-eda
    ```

2.  Open the notebook in Google Colab or Jupyter:

    -   Upload `EDA.ipynb` to [Google
        Colab](https://colab.research.google.com/)
    -   Or run locally with Jupyter Notebook

3.  Install dependencies (if running locally):

    ``` bash
    pip install -r requirements.txt
    ```
4.  Download Spotify Dataset
    - Create Kaggle Account
    - Under Retrieving Dataset title in the EDA.ipynb file, change the value of "user" to your username
    - EX: user = "mwsama"
    - Then retrieve your token key and put it in key (Here is a resource to show how to get the key! https://christianjmills.com/posts/kaggle-obtain-api-key-tutorial/)
    - EX: key = "123987192873"

## 📈 Sample Insights

-   Distribution of tracks across years shows trends in music release
    over time
-   Features like **energy** and **danceability** cluster strongly in
    popular tracks
-   Correlation analysis highlights how tempo, loudness, and valence
    interact

## 🔮 Future Work

-   Build predictive models for song popularity
-   Expand analysis across playlists and regions
-   Apply clustering to group songs by audio similarity

## 🙌 Acknowledgments

-   Dataset source: Spotify (via Kaggle or API)
-   Project inspired by exploratory data analysis practices
