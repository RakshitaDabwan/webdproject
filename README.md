# Movie Guide App

A simple and responsive Movie Guide Web Application built using HTML, CSS, and JavaScript. The application allows users to search for movies and view important information such as IMDb rating, genre, release date, runtime, cast, plot, and movie poster.

The application uses the **OMDb API (Open Movie Database API)** to fetch movie information dynamically based on the movie name entered by the user.

## Features

* Search for movies by entering the movie name
* Display IMDb rating
* Display movie genres
* Display release date
* Display movie runtime
* Display cast information
* Display movie plot
* Display movie poster
* Error messages for invalid or unavailable movie searches
* Responsive design for different screen sizes
* Dynamic movie information using JavaScript and API integration

## Technologies Used

* **HTML5** – Used to create the structure of the web application
* **CSS3** – Used for styling, layout, and responsive design
* **JavaScript** – Used for functionality, API requests, DOM manipulation, and error handling
* **OMDb API** – Used to fetch movie information dynamically

## API Used

This project uses the **OMDb API (Open Movie Database API)** to retrieve movie information.

The application sends a request to the API using the movie name entered by the user and receives the movie information in JSON format.

The following information is retrieved and displayed:

* Movie Title
* IMDb Rating
* Genre
* Release Date
* Runtime
* Cast
* Plot
* Movie Poster

## How It Works

1. The user enters the name of a movie in the search bar.
2. JavaScript captures the submitted movie name.
3. The application sends a request to the OMDb API using the `fetch()` function.
4. The API returns the movie information in JSON format.
5. JavaScript processes the response.
6. The movie information is dynamically displayed on the webpage.
7. If the movie cannot be found, an appropriate error message is displayed.

## JavaScript Functionality

The application uses JavaScript to handle the main functionality of the project.

### Movie Search

The search form listens for the user's submission and retrieves the movie name entered in the input field.

### API Request

The application uses JavaScript's `fetch()` function to send a request to the OMDb API and retrieve movie data.

### Dynamic Data Display

The received movie information is dynamically added to the webpage using DOM manipulation.

### Error Handling

The application displays appropriate messages when:

* The search field is empty
* A movie cannot be found
* Movie data cannot be retrieved

## Responsive Design

The application is designed to work across different screen sizes.

On larger screens, the movie poster and movie information are displayed side-by-side.

On smaller screens, the layout changes to a vertical format to provide a better viewing experience on tablets and mobile devices.

## Project Structure

```text
Movie-Guide-App/
│
├── movie.html
├── movie.css
├── movie.js
└── README.md
```

### `movie.html`

Contains the main structure of the application, including the navigation bar, search form, movie information section, and footer.

### `movie.css`

Contains the styling of the application, including the movie container, search bar, navigation bar, movie poster, movie information, genre tags, footer, and responsive layouts.

### `movie.js`

Contains the JavaScript functionality of the application, including API integration, movie searching, dynamic content generation, DOM manipulation, and error handling.

### `README.md`

Contains the documentation for the project.

## What I Learned

While building this project, I gained practical experience with:

* HTML page structure
* CSS styling
* CSS Flexbox
* Responsive web design
* Media queries
* JavaScript fundamentals
* DOM manipulation
* Event listeners
* Form handling
* User input validation
* JavaScript `fetch()`
* Working with REST APIs
* Processing JSON data
* Dynamic content rendering
* Basic error handling

## Future Improvements

Some features that can be added in future versions include:

* Add movies to a favorites/watchlist section
* Display trending and popular movies
* Add search suggestions
* Add movie reviews and ratings
* Add detailed actor and director information
* Add upcoming movie information
* Add dark mode
* Add loading animations
* Improve UI animations and interactions
* Further improve the mobile experience
* Improve API key security

## Author

**Rakshita Dabwan**
