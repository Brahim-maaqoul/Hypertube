<h1>Hypertube</h1>

Hypertube is a web application developed as part of the curriculum at 42 Network School. It allows users to search for movies, stream them, and interact with other users through comments and ratings. The application combines features of various streaming platforms, offering a unique and user-friendly experience.

<h2>Table of Contents</h2>

<h3>Features</h3>
<ul>
  <li>User authentication and registration</li>
  <li>Search for movies by title</li>
  <li>Stream movies directly in the browser</li>
  <li>Browse and filter movies by genre, year, and rating</li>
  <li>Commenting system for users to interact with each other</li>
  <li>Rating system for users to rate movies</li>
  <li>User profile page to view personal information and activity</li>
</ul>

<h3>Technologies Used</h3>
<ul>
  <li><h4>Frontend:</h4></li>
  <ul>
  <li>Angular</li>
  <li>Angular Material for UI components</li>
  <li>Angular Router for routing</li>
  <li>RxJS for handling asynchronous operations</li>
  <li>TypeScript for static typing</li>
  </ul>
  <li><h4>Backend:</h4></li>
  <ul>
  <li>Django</li>
  <li>Django REST Framework for building APIs</li>
  <li>Django ORM for database operations</li>
  <li>Django Rest Auth for authentication</li>
  <li>Django Channels for WebSocket communication</li>
  <li>PostgreSQL for database storage</li>
  <li>TMDB API for movie data</li>
  </ul>
</ul>
<h3>Installation</h3>
<ol>
  <li>Clone the repository:</li>
  
    git clone https://github.com/Brahim-maaqoul/hypertube.git
    cd hypertube
    
  <li>Install dependencies for both frontend and backend:</li>
  
    cd frontend
    npm install
    cd ../backend
    pip install -r requirements.txt
  
  <li>Set up backend environment variables:</li>
  <p>Create a '.env' file in the backend directory and add the following:</p>
  
    SECRET_KEY=your_django_secret_key
    DEBUG=True
    ALLOWED_HOSTS=localhost,127.0.0.1
    DATABASE_URL=your_postgresql_database_uri
    TMDB_API_KEY=your_tmdb_api_key
    
  <li>Apply migrations and create a superuser:</li>
  
    cd backend
    python manage.py makemigrations
    python manage.py migrate
    python manage.py createsuperuser
    
  <li>Seed database (optional):</li>
  
    python manage.py seed
  
  <li>Start the development servers:</li>
  
    cd frontend
    ng serve
    cd ../backend
    python manage.py runserver
  
</ol>

  Visit http://localhost:4200 in your browser to access the Angular frontend.
  <br>
  <h3>Usage</h3>
  <ul>
    <li>Register an account or login if you already have one.</li>
    <li>Search for movies using the search bar or browse through categories.</li>
    <li>Click on a movie to view details and start streaming.</li>
    <li>Leave comments and ratings on movies.</li>
    <li>Explore user profiles and their activity.</li>
  </ul>

  <h3>Contributing</h3>
    Contributions are welcome! Feel free to open issues or pull requests for any improvements or bug fixes.

  
