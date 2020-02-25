# movies-api
movie API checklist

User should be able to see all movies in the database
“movies/“ GET

User should be able to add a movie
“movies/addmovie” POST

User should be able to search for a movie and see the information (on the same page)
“movies/findmovie” GET

User should be able to update information about the move, but NOT the unique values or the id (only in postman not using an ejs page)
“movies/updatemovie” PUT

User should be able to delete a word from the database (this should work only in postman not on a page)
“movies/deletemovie” DELETE

*The database should hold all strings:
the title of the movie
rating (PG, R, PG-13)
synopsis
release year
genre (if there are many genre options only choose one)
director
box office
At least one of the values in the db must be unique

dependencies: mongoose, dotenv
