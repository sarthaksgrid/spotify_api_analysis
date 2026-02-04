Spotify Genre Paradox: Data Analysis

This project explores the relationship between Spotify's categorical labels (Happy vs. Sad) and the actual musical attributes (Energy, Valence, Loudness) of the tracks.
1. Requirements

Ensure you have Python installed. You can install all necessary libraries by running:

pip install requirements.txt

2. Project Structure & Code Snippets

The project is divided into 7 Jupyter notebooks. To maintain data integrity, run them in the following numerical order:

01_data_cleaning.ipynb: Cleans the raw Spotify dataset and standardizes column names to lowercase (e.g., energy, valence) to ensure compatibility across all notebooks.

02_happy.ipynb: Analyzes the "Happy" genre. It generates the Mood Mountain (Valence distribution) and the Happy Fingerprint (High Energy/Low Valence cluster).

03_sad.ipynb: Focuses on the "Sad" genre. It identifies the Low-Intensity/Low-Mood Zone and creates the corresponding density contour plots.

04_dancibility.ipynb: Examines the relationship between energy and danceability scores across various genres.

05_loudness.ipynb: Investigates decibel levels and dynamic range, correlating physical volume with emotional valence.

06_musical_keys.ipynb: Analyzes the prevalence of Major vs. Minor keys and how they impact the algorithmic Valence score.

07_correlation.ipynb: The final summary notebook. It generates a correlation matrix and the Evidence Profile (merged boxplots) showing the paradox between Energy and Valence.