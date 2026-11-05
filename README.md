# Smart Movie Recommender

IS6752 Data Extraction Techniques – Group 4 project (NTU).

A Streamlit web app that recommends films from a dataset scraped from English Wikipedia (2015–2024 American film lists) and enriched with IMDb ratings and posters through the OMDb API. Users set genre, release-year, popularity and mood-keyword preferences; the engine ranks films with TF-IDF cosine similarity and a weighted score, and shows a reason tag for each recommendation.

Live app: https://movie-recommender6752.streamlit.app/

## Files
- `script.py` – Streamlit interface (main file)
- `engine.py` – TF-IDF and weighted scoring engine
- `movies_enriched.csv` – cleaned and enriched dataset
- `requirements.txt` – dependencies

## Run locally
```
pip install -r requirements.txt
streamlit run script.py
```
