# ⭐ AnimeVerse: Anime Ratings & Metrics – ML Pipeline 🎌

> 🎯 **Project Moto:**  
> *This project predicts anime ratings and classifies their success using data from the MyAnimeList API. It applies regression and classification models to explore key influencing factors.*

---

## 🌐 Overview

The **Anime Ratings & Metrics** feature of AnimeVerse leverages machine learning to analyze and predict how well an anime performs based on various attributes and user interactions.

---

## 🔁 ML Pipeline Stages

1. 📥 **Data Collection** *(Current Focus)*
2. 🧹 Data Preprocessing
3. 📊 Exploratory Data Analysis (EDA)
4. 🧠 Model Building
   - Regression (for rating prediction)
   - Classification (for success category)
5. 🚀 Model Deployment
   - API integration with AnimeVerse
   - Real-time prediction dashboard

---

## 📥 Phase 1: Data Collection

### 🎯 Goal:  
Collect diverse and reliable data from **MyAnimeList (MAL)** using the **Jikan API** to power the rating prediction and success classification models.

---

### 📦 Data Sources

| Source Type            | Description                                 | Examples                          |
|------------------------|---------------------------------------------|-----------------------------------|
| 🔌 API Access          | Fetch anime metadata & stats via Jikan API | [Jikan API](https://jikan.moe/)   |
| 🌐 Web Scraping        | Supplementary content from user reviews     | MyAnimeList, AniList              |
| 📁 Public Datasets     | External sources for benchmarking           | Kaggle Anime Datasets             |
| 👥 User Interaction    | In-app watchlist, ratings (future)          | AnimeVerse user logs              |
| 📄 Comments & Reviews  | User feedback for sentiment analysis        | Reddit, MAL, Twitter              |

---

### 🔍 Key Features to Collect

- `anime_id`, `title`, `synopsis`
- `genre(s)`, `studio`, `type` (TV, Movie, OVA)
- `episodes`, `duration`, `airing_date`
- `score`, `scored_by`, `popularity`, `favorites`
- `members`, `watching`, `completed`, `dropped`
- User `reviews`, `ratings`, and `tags`

---

### 🛠 Tools & Libraries

- 🔧 `requests`, `JikanPy` – API integration
- 🧪 `pandas`, `json` – data manipulation & storage

---

## 🧠 Next Steps

- [ ] Normalize and clean raw JSON responses
- [ ] Begin exploratory data analysis (EDA)

---

## 📅 Daily Log

📌 **14th April**  
✅ Started work on **data collection**  
✅ Explored Jikan API and sample queries  
✅ Drafted README and ML pipeline outline

---

📢 **Coming Up:**  
➡ Data Cleaning + Schema Design  
➡ EDA Visualizations + Correlation Checks

---

👨‍💻 Developed by: **Abhi** & **Shree**  
🚀 Part of the **AnimeVerse** Project 🌸

