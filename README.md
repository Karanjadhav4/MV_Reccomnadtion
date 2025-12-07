# 🍿🎬Movie Recommendation System

✨ Your personal AI-powered movie suggester!

This project uses Machine Learning + NLP to recommend movies based on similarity.
Fast, smart, and perfect for movie lovers! 🎥❤️

🚀✨ Features

🔍 Search any movie and get similar recommendations

🤖 ML-powered content-based filtering

⚡ Super-fast results using Cosine Similarity

📊 Easy-to-run Streamlit UI

🧠 Model built using TF-IDF Vectorizer

💾 Save & load models with Pickle

🛠️⚙️ Tech Stack
Tool	Purpose
🐍 Python	Programming
📚 Pandas, NumPy	Data handling
🤖 Scikit-Learn	ML model
🌐 Streamlit	Web UI
💾 Pickle	Model storage
📁📂 Project Structure
📦 Movie-Recommendation-System
├── 🎯 app.py                  # Streamlit app (optional UI)
├── 📘 model.ipynb             # Notebook for training
├── 🎞️ movies.csv              # Dataset
├── 💾 similarity.pkl          # Cosine similarity matrix
├── 💾 movie_list.pkl          # Movie titles list
└── 📄 README.md               # Documentation

📦📥 Installation
1️⃣ Clone the repo
git clone https://github.com/Karanjadhav4/movie_reccomandation_system
cd movie-recommendation-system

2️⃣ Install dependencies
pip install -r requirements.txt

▶️🎬 Run the Project
🔹 Run Notebook

Open in Jupyter / VS Code:

model.ipynb

🔹 Run Streamlit App
streamlit run app.py

🧠💡 How It Works
⭐ Step 1 — Load Dataset

movies.csv contains movie metadata like:
🎭 Genre | 📝 Overview | 🎬 Cast | 🎥 Crew | 🔑 Keywords

⭐ Step 2 — Combine Important Features
combined = genre + overview + keywords + cast + crew

⭐ Step 3 — Convert Text → Numbers

Using TF-IDF Vectorizer 📐

⭐ Step 4 — Find Similarity

Using Cosine Similarity 🔗

⭐ Step 5 — Recommend Movies 🎯

Pick top 5 movies closest to input movie.

🎥✨ Example Output

Input: Spider-man3
Recommended Movies:
1️⃣ spider-man
2️⃣ Spider-man2
3️⃣ Amazing spider-man
4️⃣ Amazing spider-man2
5️⃣ Arachnophobia

![reccomndation](https://github.com/Karanjadhav4/MV_Reccomnadtion/blob/main/Snapshot%20of%20the%20reccomndation%20system.png)

🔥 Looks clean and accurate!

🎨🌐 Streamlit UI Preview

🎛️ Dropdown to select movie

🎬 Shows 5 similar movies instantly

⚡ Fast & interactive

📄⚙️ Requirements
streamlit
pandas
numpy
scikit-learn

🤝💬 Contributing

✨ PRs and feedback are always welcome!
If you want to improve the model or UI, go ahead!




