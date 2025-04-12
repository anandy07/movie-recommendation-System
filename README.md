🎬 Movie Recommendation System


This is a Movie Recommendation System built using Streamlit, Python, and The Movie Database (TMDb) API. It suggests 5 similar movies based on the one you select from a dropdown.

🚀 Features
Pick any movie from the list and get 5 similar movie recommendations.

Uses cosine similarity for recommendations.

Displays movie posters using TMDb API.

Interactive UI powered by Streamlit.

🛠️ Tech Stack
Python 🐍

Pandas

Scikit-learn (for similarity computation)

Streamlit

TMDb API (for movie posters)

🧠 How It Works
The system loads a precomputed similarity matrix.

When a user selects a movie, it finds the top 5 similar movies.

Posters for these movies are fetched from TMDb API.

Recommendations are displayed with titles and images.

📦 Installation
Clone the repository

bash
Copy
Edit
git clone https://github.com/your-username/movie-recommender.git
cd movie-recommender
Install dependencies

bash
Copy
Edit
pip install -r requirements.txt
Ensure these files are in your directory:

movie_dict.pkl – contains movie metadata.

similarity.pkl – contains the similarity matrix.

Run the Streamlit app

bash
Copy
Edit
streamlit run app.py
🔐 TMDb API Key
Make sure your TMDb API key is working and inserted correctly in the fetch_poster() function:

python
Copy
Edit
url = f"https://api.themoviedb.org/3/movie/{movie_id}?api_key=YOUR_API_KEY"
Replace YOUR_API_KEY with your actual TMDb API key. You can get your API key here.

📸 Sample UI

Note: Add your own screenshot here.

📁 Project Structure
Copy
Edit
.
├── app.py
├── movie_dict.pkl
├── similarity.pkl
├── requirements.txt
└── README.md
✨ Future Improvements
Add movie genres, ratings, and overviews.

Allow users to search movies using keywords.

Add collaborative filtering for personalized recommendations.

🧑‍💻 Author
Your Name – anandy07

📜 License
This project is licensed under the MIT License.


Website Link : https://movie-recommendation-system-i226rkr4lovu9kfe43fdjq.streamlit.app/
