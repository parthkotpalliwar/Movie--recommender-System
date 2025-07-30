# Movie--recommender-System
Content- Based Movie recommender System using Tf - IDF, Cosine Similarity and Fuzzy Matching

A content-based movie recommender system built using **TF-IDF vectorization**, **Cosine Similarity**, and **Fuzzy Matching** to handle partial or misspelled titles.

> 🔍 "You type *shawshank* and it knows you meant *The Shawshank Redemption*."

---

## 🚀 Features

- 📚 Uses plot summaries to recommend similar movies
- 🔤 Accepts partial or lowercase titles (`"dark"` → *The Dark Knight*)
- 🤖 Intelligent matching with fuzzy search (typo-tolerant)
- 💡 Clean and beginner-friendly code with explanations
- 🧪 Works directly from a Jupyter Notebook

---

## 🛠️ Technologies Used

- Python
- Pandas
- Scikit-learn (TF-IDF & cosine similarity)
- Difflib (for fuzzy string matching)
- Seaborn & Matplotlib (for visualization)

---

## 📂 Files in This Repo

| File | Description |
|------|-------------|
| `movie_recommender.ipynb` | Main Jupyter notebook with code and explanations |
| `movies.csv`              | Dataset containing movie titles and plot summaries |
| `README.md`               | Project overview |

---

## 🧪 Example Use Cases

Try entering:

- ✅ `shawshank` → gets *The Shawshank Redemption*
- ✅ `dark` → gets *The Dark Knight*
- ✅ `new hope` → gets *Star Wars: A New Hope*
- ✅ `gamp` → matches *Forrest Gump*

---

## 📈 How It Works

1. **TF-IDF Vectorization**: Converts movie overviews into numeric vectors
2. **Cosine Similarity**: Measures how similar two movie plots are
3. **Fuzzy Matching**: Finds the closest actual title to what the user typed
4. **Top Recommendations**: Returns movies with highest plot similarity

---

## 📌 Future Enhancements

- 🔍 Add genre or director filters
- 🧑‍💻 Turn into a Streamlit Web App
- 📊 Use a larger movie dataset (e.g. TMDB)
- 🌐 Host demo app online

---

## 📬 Contact

Project by [Your Name Here]  
Feel free to connect on [LinkedIn](https://www.linkedin.com/in/your-profile)

---

> If you like this project, consider ⭐️ starring the repo!
