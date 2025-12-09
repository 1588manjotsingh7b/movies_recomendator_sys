# 🎬 Movie Recommender System

![Python Version](https://img.shields.io/badge/python-3.12+-blue)
![License](https://img.shields.io/badge/license-Educational-green)
![Streamlit](https://img.shields.io/badge/streamlit-v1.30-orange)

A **Streamlit-based movie recommendation app** that suggests movies similar to your favorite selection using actors, directors, and scriptwriters metadata.

---

## 🌟 Features

- Recommend movies based on your selected movie
- Display movie posters, titles, genres, and release year
- Fast recommendations using a **precomputed similarity matrix (`similarity.pkl`)**
- Works with a dataset of **50,00+ movies**

---

## 🧠 How It Works

1. User selects a movie they like.
2. App checks the **metadata dataset** (actors, directors, writers) to find similar movies.
3. Movies are ranked by similarity using a **precomputed similarity matrix**.
4. Recommended movies are displayed with title, poster, and genre from the **movie details dataset**.

---

## ⚡ Setup Instructions

### 1. Clone the repository
```bash
git clone https://github.com/1588manjotsingh7b/movies_recomendator_sys.git
cd movies_recomendator_sys
```

### 2. Create and activate virtual environment
```bash
python -m venv .venv
source .venv/bin/activate   # On Windows: .venv\Scripts\activate
```

### 3. Install dependencies
```bash
pip install -r requirements.txt
```

### 4. Run the app
```bash
streamlit run app.py
```

---

## Note
### similarity.pkl is stored using Git LFS (~185 MB). Make sure Git LFS is installed.

---

## 🛠 Dependencies
- Python
- Streamlit
- Pandas
- NumPy

---

## 📦 Dataset
- tmbd_5000_credits.csv
- tmbd_5000_credits.csv
- link = https://www.kaggle.com/datasets/tmdb/tmdb-movie-metadata

---

## 💡 Pro Tips
- Ensure Git LFS is installed: https://git-lfs.github.com
- Large files like .pkl are automatically handled by LFS
- You can extend the app by adding more metadata like ratings or reviews

---

## 📜 License
- Educational / Personal Project

---

## 🎨 Optional Enhancements

- Add top-N recommendations filters  
- Include genre-specific suggestions  
- Display movie trailers or links

