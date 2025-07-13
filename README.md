# FilmFinder: A Hidden Gems Movie Recommender

**FilmFinder** is a personalized film discovery tool that helps users find *hidden gem* movies based on genre, platform availability, and quality metrics — using real-time data from The Movie Database (TMDb). Whether you're a casual viewer or a movie buff, FilmFinder uncovers lesser-known films that are truly worth watching.

---

## Project Motivation

Many streaming platforms are saturated with overly promoted or mainstream content. As a film enthusiast, I built FilmFinder to surface high-quality, under-the-radar titles that are available to stream, using data analytics and recommendation logic. This project also serves as an end-to-end demonstration of my data wrangling, API integration, and visualization skills.

---

## Features

- **Real-Time API Access**: Pulls live data from TMDb via `/discover/movie`
- **Hidden Gem Filtering**: Filters by user-defined criteria
- **Custom Recommendation Logic**: Scores and ranks movies using rating, genre match, and popularity
- **Streaming Filter (Optional)**: Recommends only movies available on platforms like Netflix or Hulu (region-aware)
- **Interactive Dashboard** *(Planned)*: Visualize movies by genre, score, or platform

---

## 🛠️ Tech Stack

| Component      | Tool/Library            |
|----------------|--------------------------|
| Data Source    | [TMDb API](https://developer.themoviedb.org/) |
| Programming    | Python (requests, pandas, datetime) |
| Data Storage   | SQLite / Pandas DataFrames |
| Frontend       | Streamlit *(in progress)* |
| Version Control| Git & GitHub |
