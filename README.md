# 🎬 Movie Recommender System

A content-based movie recommendation system that suggests similar movies based on user-selected titles. Built using Python, Pandas, scikit-learn, and Streamlit for an interactive and responsive web interface.

---

## 🚀 Features

- 📽️ Recommends top 5 similar movies based on plot, genre, cast, crew, and keywords
- 🔍 Uses **cosine similarity** over combined textual features
- 🖼️ Displays movie posters using **TMDb API**
- 🌐 Web app built with **Streamlit** for easy deployment and interaction

---

## 📁 Project Structure

```
movie-recommender-system/
├── .ipynb_checkpoints/              # Jupyter notebook checkpoints
├── .idea/                           # IDE project settings
├── similarity.pkl                   # Precomputed similarity matrix (Git LFS)
├── movie-recommender-system.ipynb  # Main notebook with EDA & model
├── tmdb_5000_credits.csv            # Credits dataset
├── tmdb_5000_movies.csv             # Movies dataset
├── setup.sh                         # Shell script for setup
├── app.py                           # Streamlit web app
└── README.md                        # Project documentation
```


---

## 📦 Installation

### ⚙️ Requirements
- Python 3.7+
- `pandas`, `scikit-learn`, `nltk`, `streamlit`, `requests`
- Git LFS (for `similarity.pkl`)

### 🔧 Setup Instructions

```bash
# Clone the repo
git clone https://github.com/faizulhaq7/Movie-Recommender-System.git
cd Movie-Recommender-System

# Install dependencies
pip install -r requirements.txt

# Run the app
streamlit run app.py
