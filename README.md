# Spotify Music Analysis in Indonesia

This project focuses on scraping data from Spotify and performing audio feature analysis to understand the preferences of listeners in Indonesia. Below is an explanation of the two main notebooks in this project:

## 1. Scraping Spotify Top 50 Indonesia Dataset (`Scraping Dataset API SPOTIFY TOP 50 Indonesia.ipynb`)

This notebook is used to scrape the Top 50 songs on Spotify Indonesia. The data collected includes information such as song name, artist, and various metrics provided by the Spotify API.

### Main Processes:
- Accessing the Spotify API to retrieve song data.
- Saving the scraped data into a CSV file (`dataset_top_50_music_daily_spotify_id_scraping_2024.csv`).
- Data validation and cleaning to ensure its integrity.

## 2. Segmentation of Spotify Listeners' Preferences in Indonesia Based on Audio Feature Analysis (`Segmentasi_Preferensi_Pendengar_Lagu_Spotify_di_Indonesia_Berdasarkan_Analisis_Fitur_Audio.ipynb`)

This notebook focuses on analyzing the scraped data. Using various audio features provided by the Spotify API, this notebook performs segmentation to understand the preferences of listeners in Indonesia.

### Main Processes:
- Loading the scraped data from the CSV file.
- Performing data exploration to understand the distribution of audio features.
- Applying segmentation methods (e.g., clustering) to identify groups of listener preferences.
- Visualizing the analysis results for easier interpretation.

## Project Structure

- `dataset_top_50_music_daily_spotify_id_scraping_2024.csv`: The dataset scraped from the Spotify API.
- `Scraping Dataset API SPOTIFY TOP 50 Indonesia.ipynb`: Notebook for scraping Spotify data.
- `Segmentasi_Preferensi_Pendengar_Lagu_Spotify_di_Indonesia_Berdasarkan_Analisis_Fitur_Audio.ipynb`: Notebook for audio feature analysis and listener preference segmentation.

## Installation Instructions

To run this project on your local machine, follow these steps:

1. **Download the Project**:
    - Click the green "Code" button on the GitHub repository page.
    - Select "Download ZIP".
    - Extract the ZIP file to your desired location.

2. **Open the Project in Jupyter Notebook**:
    - Open Jupyter Notebook on your local machine.
    - Navigate to the folder where you extracted the ZIP file.
    - Open the following notebooks:
      - `Scraping Dataset API SPOTIFY TOP 50 Indonesia.ipynb`
      - `Segmentasi_Preferensi_Pendengar_Lagu_Spotify_di_Indonesia_Berdasarkan_Analisis_Fitur_Audio.ipynb`
    - Run the cells in each notebook to execute the code.

## Contact
If you have any questions or suggestions, feel free to reach out to me via [Email](mailto:devin7swijaya@gmail.com) or through my [GitHub profile](https://github.com/paradox77x).