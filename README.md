# CRUD-API
This is a simple CRUD (Create, Read, Update, Delete) API written in Go language using the Gorilla Mux router. The API allows you to create, read, update, and delete movies from a collection of movies.

The program defines two structs, Movie and Director. The Movie struct contains an ID, ISBN, title, and director. The Director struct contains a first name and last name.

The program defines five HTTP request handlers for handling different requests:

    getMovies - Handles GET requests to get all movies from the collection.
    getMovie - Handles GET requests to get a specific movie from the collection.
    createMovie - Handles POST requests to create a new movie and add it to the collection.
    updateMovie - Handles PUT requests to update an existing movie in the collection.
    deleteMovie - Handles DELETE requests to delete an existing movie from the collection.

The program initializes a collection of two movies and registers the request handlers with the Gorilla Mux router. Finally, the program starts an HTTP server on port 8080 and logs any errors that occur.

Note that this program is for educational purposes only and is not intended to be used in production environments. It lacks proper error handling, authentication, and other security features that are necessary for production-ready APIs.
