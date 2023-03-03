![my badge\](https://badgen.net/github/stars/vercel/next.js "twitter")



## Movie API
- This is a RESTful API for managing movie records. It is built using Go and the Gorilla mux package.

## Endpoints
### GET /movies
- Returns a JSON array of all movies in the database.

### GET /movies/{id}
- Returns a JSON object for a specific movie, identified by {id}.

### POST /movies
- Creates a new movie record based on the JSON object in the request body.

### PUT /movies/{id}
- Updates an existing movie record identified by {id}, based on the JSON object in the request body.

#### DELETE /movies/{id}
- Deletes an existing movie record identified by {id}.

## Data Model
Each movie record consists of the following fields:

id (string): A unique identifier for the movie record.
isbn (string): The International Standard Book Number (ISBN) for the movie.
title (string): The title of the movie.
director (object): An object containing the first and last name of the director of the movie.
Usage
To run the application, run the following command:

## RUN:

```
go run main.go
```
This will start the server at http://localhost:8000/.

You can test the endpoints using a tool like [Postman](https://github.com/ichdamola/movie-crud/blob/main/movie-crud.postman_collection.json).
