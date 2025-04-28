# automated-playlist-generation
# Spotify Playlist Clustering

This project focuses on generating automated playlists based on the audio features of songs, using K-Means clustering and PCA for dimensionality reduction.

## Project Structure

- **Creating Playlist (MinMax).ipynb**:  
  Preprocessing with MinMaxScaler and clustering songs using K-Means.

- **Creating Playlist (SC & PCA).ipynb**:  
  Preprocessing with StandardScaler, dimensionality reduction with PCA, and then clustering.

## Main Steps

1. Data cleaning and feature selection
2. Feature scaling (MinMaxScaler or StandardScaler)
3. Dimensionality reduction (PCA)
4. K-Means clustering to group similar songs
5. Playlist generation using Spotify API

## Techniques Used

- K-Means Clustering
- PCA (Principal Component Analysis)
- Silhouette Score and Elbow Method for selecting K
- Heatmaps, Radar Charts, and Boxplots for analysis

## Goals

- Create playlists that are internally consistent and musically coherent
- Group songs based on meaningful audio characteristics
- Visualize and evaluate clustering quality
🚀 How to Use
Clone the repository:

bash
Copy
Edit
git clone https://github.com/Afsaneh-Esmautomated-playlist-generation.git
Open the Jupyter Notebooks locally.

## 🎯 Presentation

You can view the project slides here:  
👉 [Project Presentation (Canva)](https://www.canva.com/design/DAGldQ_P6IY/9ClJmL64GgdtCD9zIcsXDw/edit?utm_content=DAGldQ_P6IY&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## Open Questions

- How does PCA impact cluster separability?
- What features would improve playlist generation beyond audio features?

## Tools

- Python
- Pandas, Scikit-Learn, Matplotlib, Seaborn, Plotly
- Spotify Web API

---

🐵 Feel free to explore the notebooks, and feedback is welcome!
