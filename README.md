🎬 Movie Recommendation System


This is a Movie Recommendation System built using Python, Streamlit, Jupyter Notebook, and The Movie Database (TMDb) API. It recommends 5 similar movies based on the selected movie and displays their posters.

🚀 Features
Select a movie and get 5 similar movie suggestions.

Uses cosine similarity based on movie features.

Posters displayed using TMDb API.

Interactive UI with Streamlit.

Data preprocessing and modeling done in Jupyter Notebook.

🛠️ Tech Stack
Python 🐍

Pandas, NumPy

Scikit-learn (cosine similarity)

Jupyter Notebook (data preprocessing/model training)

Streamlit (front-end)

TMDb API (movie poster retrieval)

🧠 Workflow
Jupyter Notebook is used for:

Loading and preprocessing movie data.

Calculating similarity matrix.

Saving movie_dict.pkl and similarity.pkl.

Streamlit App is used for:

Taking movie input from user.

Fetching top 5 similar movies.

Displaying results with posters via TMDb API.

📦 Installation
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/movie-recommender.git
cd movie-recommender
Create a virtual environment (optional but recommended)

bash
Copy
Edit
python -m venv env
source env/bin/activate   # or `env\Scripts\activate` on Windows
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Run Jupyter Notebook (optional, if modifying or retraining)

bash
Copy
Edit
jupyter notebook
Run the Streamlit App

bash
Copy
Edit
streamlit run app.py
🔐 TMDb API Key
The poster images are fetched using TMDb API. Replace the placeholder in the code with your actual API key:

python
Copy
Edit
url = f"https://api.themoviedb.org/3/movie/{movie_id}?api_key=YOUR_API_KEY"
Get your API key here: TMDb API

📁 Files Included
bash
Copy
Edit
.
├── app.py                 # Streamlit frontend
├── movie_dict.pkl         # Movie metadata
├── similarity.pkl         # Precomputed similarity matrix
├── Movie_Recommender.ipynb # Jupyter Notebook for preprocessing
├── requirements.txt       # Python dependencies
└── README.md
📸 Sample UI
Add your screenshot here if you have one.

✅ Example Movies You Can Try
Inception

Avatar

The Dark Knight

Interstellar

Titanic

✨ Future Ideas
Add filters for genre, year, or language.

Include movie overview, rating, and runtime.

Add collaborative filtering with user-based preferences.

🧑‍💻 Author
Your Name – anandy07

📜 License
This project is licensed under the MIT License.


Website Link : https://movie-recommendation-system-i226rkr4lovu9kfe43fdjq.streamlit.app/
