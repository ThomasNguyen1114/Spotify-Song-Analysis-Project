# 🎵 Spotify Song Analysis Project

This project analyzes how popular music has evolved over the past two decades using Spotify's audio features. By exploring genre trends from 2000 to 2019, it reveals how characteristics like **danceability**, **energy**, **valence**, **tempo**, and **speechiness** have shifted — and how each genre develops its own "audio fingerprint."

**Full blog post on Medium:**  
[Read it here]([https://medium.com/@thomascena/how-music-has-changed-a-spotify-genre-analysis-2000-2019-YOUR-POST](https://medium.com/@thomascena9/spotify-song-analysis-writing-and-summary-280084db0c74])

---

## 🔍 Key Questions Explored

- What features define a genre?
- Which audio features show the strongest correlations with each other?
- How do genres evolve over time?
- Can we define a genre by its average sound?
- What are the biggest contrasts between genres?

---

## What’s in the Analysis

### Exploratory Data Analysis
- Correlation heatmap of audio features
- Distribution of features like tempo, acousticness, and valence

### Trends Over Time
- How energy, valence, and danceability have changed across genres
- Tempo evolution and mood shifts (e.g., pop becoming less danceable)

### Genre Fingerprints
- Comparing genres using median feature values
- Danceability vs. energy vs. acousticness across hip hop, rock, pop, and EDM

### Insights & Takeaways
- Hip hop is rhythm-driven and high in speechiness
- Rock is fast but less danceable
- Pop blends electronic and acoustic traits
- Genres are measurable and evolving — the data proves it

---

## Tools Used

- **Python**
- **Pandas** for data wrangling  
- **Seaborn** and **Matplotlib** for static visualizations  
- **Plotly** for interactive exploration  
- **Google Colab** for development  
- **GitHub** for version control and sharing

---

## How to Run the Project

1. Clone the repository or open the notebook `01_data_setup_and_eda.ipynb` in Google Colab.
2. Ensure the dataset file `songs_normalize.csv` is located in the `data/` folder of your Google Drive.
3. Mount Google Drive in the notebook:
   ```
   from google.colab import drive
   drive.mount('/content/drive')
   ```
4. Install required libraries (if needed):

  ```
  !pip install seaborn plotly
  ```
5. Run the notebook cells to explore the dataset and generate visual insights.

## Author
Thomas Nguyen

---

