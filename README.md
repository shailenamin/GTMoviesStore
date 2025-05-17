# GT MovieStore 🎬

GT MovieStore is a Django-based web application designed to showcase movie listings, allow users to manage watchlists, and explore detailed film information. Built as a class project, the app simulates a digital storefront experience tailored to movie fans and students learning full-stack development.

🔗 **Live Demo:** [https://shailenamin.github.io/GTMoviesStore](https://shailenamin.github.io/GTMoviesStore)  
🛠️ **Tech Stack:** Django · HTML/CSS · Bootstrap · PostgreSQL · JavaScript

## Features
- Movie catalog with search and filter functionality  
- Add/remove movies from personalized watchlists  
- Dynamic movie detail pages with descriptions, images, and metadata  
- User authentication (login/register/logout)  
- Admin panel for adding or editing movie entries  
- Clean, responsive UI using Bootstrap  

## My Contributions
- Developed the watchlist functionality including models, views, and templates  
- Designed and implemented the movie detail page layout  
- Refactored the base template and navigation for consistency across pages  
- Built the admin interface for managing movie content  
- Wrote Django queries for filtering and searching the movie catalog  

## Installation (Local Setup)
```bash
# Clone the repo
git clone https://github.com/shailenamin/GTMoviesStore.git

# Set up backend
cd GTMoviesStore
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
