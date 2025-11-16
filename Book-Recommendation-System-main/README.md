A simple yet effective Book Recommendation System built with Flask, Pandas, and Pickle. This project recommends similar books based on user input using a content-based filtering approach.# Book-Recommendation-System
 
📂 Project Structure
.
├── app.py                  # Main Flask app
├── templates/
│   ├── index.html          # Homepage showing popular books
│   └── recommend.html      # Recommendation input & output page
├── popular.pkl             # Pre-processed data of popular books
├── pt.pkl                  # Pivot table (Book-Title × Users)
├── books.pkl               # Original books dataset with metadata
├── similarity_scores.pkl   # Similarity matrix for recommendations
└── README.md               # Project documentation

🧠 How It Works
The system loads precomputed data:
popular.pkl contains top-rated books with metadata.
pt.pkl is a pivot table of books and user ratings.
books.pkl contains detailed metadata of all books.
similarity_scores.pkl holds similarity values between books.
A user inputs a book title.
The system finds similar books using the similarity score matrix.
Recommended books (title, author, image) are displayed on the result page.

📦 Requirements
1]Install required libraries using:
pip install -r requirements.txt
2]requirements.txt (you can create this file):
flask
numpy
pandas
3] download this dataset:
https://www.kaggle.com/datasets/sinatavakoli/books-dataset-for-nlp-and-recommendation-systems

💻 Running the App:
1]Ensure popular.pkl, pt.pkl, books.pkl, and similarity_scores.pkl are in the root folder.
2]Run the Flask app:
    python app.py
4]Visit http://127.0.0.1:5000/ in your browser.

🌟 Features
Recommends books similar to the one the user inputs.
Shows book title, author, and image.
Displays popular books on the homepage.

🛠️ To-Do / Improvements
Add search suggestions/autocomplete.
Handle invalid inputs gracefully.
Add user login and personalized recommendations.
Deploy to Heroku, Render, or Vercel.

 Author
Atharva Gole
Feel free to contribute or raise issues!
