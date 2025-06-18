# 🎵 Spotify Song Analysis Project

This project analyzes top Spotify songs and their audio features using Python. It investigates how attributes like danceability, energy, and tempo have changed over time and how they relate to popularity, using statistical methods and visualizations.

---

## 📌 Project Features

- **Data Cleaning**: Cleaned and standardized column names for consistency.
- **Descriptive Statistics**: Summarized key numeric features such as tempo, energy, and valence.
- **Correlation Analysis**: Explored relationships between features like popularity and energy using correlation coefficients.
- **Data Visualization**: Created plots (histograms, scatterplots, line graphs) to show trends over time and across features.

---

## 🛠 Technologies Used

- Python (with libraries: `pandas`, `numpy`, `seaborn`, `plotly`, `matplotlib`)
- Google Colab (for development)
- Google Drive (for storage and data access)

---

## ▶️ How to Run the Project

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

## 📬 Author
Thomas Nguyen

---

