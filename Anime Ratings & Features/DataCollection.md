# 📘 Overview of `DataCollection.ipynb`

## 🎯 Main Objective
The notebook is designed to **collect anime-related data** from a website called **MyAnimeList (MAL)** using **web scraping** techniques. This dataset is likely to be used for building features like recommendations, search, or analytics in our **AnimeVerse project**.

---

## 🛠️ Key Libraries Used
- `requests`: For sending HTTP requests to MAL.
- `BeautifulSoup`: To parse and extract specific HTML elements.
- `pandas`: To store and manipulate collected data.
- `time`: For controlling request frequency (politeness delay).
- `tqdm`: To visualize progress during the scraping loop.

---

## 🔄 How It Works

### 1. **Scraping Anime Info**
- It scrapes data like:
  - **Anime title**
  - **Score**
  - **Number of members**
  - **Genres**
  - **Rank & popularity**
- Target URL structure: `"https://myanimelist.net/topanime.php?limit={offset}"`

### 2. **Looping Through Pages**
- The script loops through multiple pages (in steps of 50) to collect data from all top anime listings.

### 3. **Politeness & Progress**
- `time.sleep(2)` is used to prevent getting banned.
- `tqdm` shows a progress bar as the pages are processed.

### 4. **Storing Data**
- All the scraped info is stored in a `pandas DataFrame`.
- The dataset is then saved to a `.csv` file for future ML/data analysis tasks.

---

## 🧠 Use Case in Project
This script builds the **core dataset** for:
- **Anime ratings & popularity metrics**
- **Building a recommendation engine**
- **User preference analysis**
- **Ranking-based filters or sorting features**

---

## ✅ Output
At the end, the notebook generates a `anime.csv` file which contains the structured anime metadata collected from MyAnimeList.
