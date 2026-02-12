# movie_recyclelist-application
React application that fetches and displays movie collection data from the TMDB API. Shows movie posters, titles, and release dates in a responsive list layout.
Movie Collection List – React Application
📌 Project Overview

This project is a React-based web application that fetches and displays a list of movies from The Movie Database (TMDB) API. The application retrieves collection details using the TMDB "Get Collection Details" endpoint and presents the movies in a responsive list layout similar to a RecyclerView.

🚀 Features

Fetches movie collection data from TMDB API

Displays movie poster, title, and release date

Responsive grid layout

Clean and simple UI

Error handling for API requests

Loading state while fetching data

🛠️ Technologies Used

React (JavaScript)

HTML5

CSS3

TMDB REST API

🔗 API Used

Endpoint:
https://developers.themoviedb.org/3/collections/get-collection-details

Example:

https://api.themoviedb.org/3/collection/{collection_id}?api_key=YOUR_API_KEY

⚙️ Setup Instructions

Clone the repository:

git clone https://github.com/your-username/movie-collection-list.git


Navigate to the project folder:

cd movie-collection-list


Install dependencies:

npm install


Add your TMDB API key inside the project:

const API_KEY = "YOUR_API_KEY";


Run the application:

npm start


The app will run on:

http://localhost:5173/

📂 Project Structure
src/
 ├── components/
 │    └── MovieList.js
 ├── App.js
 ├── MovieList.css

📸 Output

Displays a scrollable list/grid of movies from the selected TMDB collection with posters and details.

📧 Contact

charumathi
mathicharu13128@gmail.com
