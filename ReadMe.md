🎵 Amazon Music Clustering Using Unsupervised Machine Learning

📌 Project Overview

With over millions of tracks available on music platforms, manually classifying songs into genres or moods is nearly impossible.
This project applies Unsupervised Machine Learning (K-Means clustering) to automatically group songs based on their audio characteristics such as:

🎶 Danceability
⚡ Energy
🔊 Loudness
🎤 Speechiness
🎻 Acousticness
🥁 Instrumentalness
🎚 Tempo

The output clusters represent distinct song groups, such as:

🔵 Calm acoustic songs

🟠 Energetic pop/party songs

🟢 Vocal/spoken/live tracks

This grouped data can be used by streaming platforms for playlist generation, song recommendations, and audience behavior analysis.

📁 Project Folder Structure
AMAZON_MUSIC_CLUSTERING/
│
├── Amazon project report.docx          # Final project report (Word)
├── Amazon_Music_Clustering.ipynb       # Complete Jupyter Notebook
│
├── Original_dataset.csv                # Raw dataset
├── Data_Cluster_label.csv              # Dataset with cluster labels
├── Average_Cluster.csv                 # Cluster feature averages
├── music_with_clusters.csv             # Final processed dataset
│
├── Top_Cluster_0.csv                   # Top songs in Calm Acoustic Cluster
├── Top_Cluster_1.csv                   # Top songs in Energetic Pop Cluster
├── Top_Cluster_2.csv                   # Top songs in Vocal/Spoken Cluster
│
└── venv/                               # Virtual environment (Python)

🧠 Key Features of the Project

✔ Unsupervised Learning (K-Means)

Automatically groups 95,837 songs into three meaningful clusters.

✔ Dimensionality Reduction (PCA)

2D PCA visualization highlights clear separation between clusters.

✔ Data Visualization

Includes PCA plots, bar charts, heatmaps, violin plots and more.

✔ Cluster Interpretation

Each cluster clearly interpreted using audio patterns.

✔ Exported Outputs

Final processed dataset

Cluster summaries

Top 10 songs per cluster

Word report

🎯 Cluster Summary

🔵 Cluster 0 — Calm Acoustic

Low energy, slow tempo, high acousticness

Relaxing, chill, study & meditation type tracks

🟠 Cluster 1 — Energetic Pop / Party

High energy, loudness & valence

Workout, dance, driving playlist songs

🟢 Cluster 2 — Vocal / Spoken / Live

High speechiness & liveness

Live recordings, rap, spoken-word content

🧪 Tech Stack

| Category        | Tools                     |
| --------------- | ------------------------- |
| Programming     | Python                    |
| ML Libraries    | scikit-learn              |
| Data Processing | pandas, numpy             |
| Visualization   | matplotlib, seaborn       |
| Documentation   | Word (docx)               |
| Environment     | VS Code, Jupyter Notebook |


🚀 How the Project Works

Load Dataset

Clean & Preprocess

Feature Selection (10 audio features)

Scale using StandardScaler

Reduce dimensions using PCA

Cluster using K-Means

Evaluate with Silhouette Score

Visualize clusters

Export results and top tracks

Generate final analytical report

📝 Outputs Included

✔ music_with_clusters.csv
✔ cluster_feature_means.csv
✔ Top_Cluster_0.csv / Top_Cluster_1.csv / Top_Cluster_2.csv
✔ Full project report in Word
✔ Jupyter Notebook with code

🏆 Conclusion

This project successfully applied machine learning to real music data, enabling:

Smart playlist generation

Better user recommendations

Artist/genre insights

Audio feature-driven segmentation

It demonstrates strong skills in:

✔ Data Processing
✔ Machine Learning
✔ Data Visualization
✔ Unsupervised Learning
✔ Real-world Analytics

🤝 Credits

Developed by: Seenivasan D
Domain: Machine Learning ( Unsupervised Machine Learning )