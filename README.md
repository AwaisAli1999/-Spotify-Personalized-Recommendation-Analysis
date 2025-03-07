# -Spotify-Personalized-Recommendation-Analysis
A comprehensive analytical report on Spotify's personalized recommendation system, exploring user segmentation, algorithm evaluation, and the impact of curated playlists on customer lifetime value (CLV).
# 🎧 Spotify Personalized Recommendation Analysis

## 🚀 Project Overview
This project analyzes Spotify's personalized recommendation feature, utilizing data collected through the Spotify API and visualized using Power BI. The goal is to understand how user preferences influence playlist recommendations and how algorithm improvements can enhance customer retention.

## 📈 Objectives
- **User Segmentation and Preference Analysis:** Understanding music taste and segmenting users accordingly.
- **Algorithm Evaluation:** Comparing Spotify’s recommendation algorithms with potential alternatives.
- **Playlist Impact on CLV:** Assessing how featured playlists and top charts affect user engagement and retention.
- **Regression Analysis:** Applying logistic regression to predict song likability based on audio features.

## 📊 Data Collection
Data was gathered using Spotify's API:
- **Liked Playlist:** 100 tracks featuring French rap, American rap, rock, and electro.
- **Disliked Playlist:** 95 tracks spanning metal, classical, and disco.

The key audio features collected:
- **Danceability**  
- **Energy**  
- **Valence**  
- **Tempo**  
- **Acousticness**  
- ... and more.

## 📈 Methodology
1. **Data Retrieval:** Used Python scripts to pull playlist data via Spotify's API.
2. **Data Processing:** Cleaned and structured data into JSON and CSV formats.
3. **Regression Analysis:** Applied logistic regression, achieving a 75% accuracy rate in predicting song likability.
4. **Data Visualization:** Created Power BI dashboards analyzing CLV impact and streaming patterns.

## 📊 Results
- **Logistic Regression:** 75% accuracy in predicting song likability.
- **CLV Impact:** Featured playlists showed a positive correlation with user retention.
- **Streaming Patterns:** Ribbon and stacked charts provided insights into track popularity.

## 📁 Files and Directories
- `data/` contains the raw data files.
- `scripts/` includes Python scripts for data retrieval and processing.
- `dashboards/` holds Power BI visualizations.
- `results/` contains outputs from the logistic regression model.

## 🚀 How to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/Spotify-Personalized-Recommendations.git
