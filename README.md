# 🎬 Movie Recommendation System
### 📌 Overview
- A content-based movie recommendation system built using Machine Learning.
- Recommends similar movies based on user-selected preferences.
- Uses TF-IDF Vectorization and Cosine Similarity for accurate recommendations.
- Built with Flask for an interactive web interface.

### 🚀 Features
- 🎥 Select movies and get similar recommendations
- 📊 Content-based filtering using ML algorithms
- ➕ Add new movies dynamically
- 🔄 Automatic model retraining after adding new data
- 🌐 Web interface using Flask
- 🖼️ Displays movie images from local folder
  
### 🛠️ Tech Stack
- Python
- Flask
- Pandas
- Scikit-learn
- TF-IDF Vectorizer
- Cosine Similarity
- HTML/CSS (Frontend)
  
### 📂 Project Structure
```
├── recommender.py
├── Cleaned_Movies.csv
├── similarity.pkl
├── templates/
│   ├── index.html
│   ├── add_movie.html
├── images/
```

### ⚙️ How It Works
- Combines movie features like:
  - Overview
  - Genre
  - Keywords
  - Cast
  - Crew
- Converts text data into numerical vectors using TF-IDF
- Calculates similarity between movies using Cosine Similarity
- Returns top 5 similar movies as recommendations

### 📈 Future Improvements
- 🎯 Add collaborative filtering
- 📡 Deploy on cloud (Render / AWS / Streamlit Cloud)
- 🎨 Improve UI/UX
- ⭐ Add movie ratings & user login system
