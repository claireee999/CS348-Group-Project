# CS348 Group Project

This application is based on datasets of movies and TV shows, and allows movie and TV show fans to search, view, rate and leave comments for each movie and TV show.

# Installation
1. In the MySQL server, run the initial.sql by `source initial.sql;`.  This will create a new database called `CS348_Movie_DB` and all the tables needed and create a user with name 'user1' and password 'Password0!'.

# Instruction on MySQL
In the same MySQL server as in installation:
1. Type `sample-data.sql`. This will insert some sample data into the tables.
2. Type `test-sample.sql`. This will show the output for the 5 functionalities we have so far.

# Funcionalties of MySQL
1. View information about the movie selected based on the name. (ex. `The Matrix`)
2. Find all movies with rating in a specific range. (ex. `> 7.0/10.0`)
3. Find all movies directed by a specific director. (ex. `Hiner Saleem`)
4. Find movies with `top-n` ratings. (ps. now only support `n <= 4`)
5. Leave both a rate and a comment on a specific movie.

# Instruction on data-driven application
1. Go to the `back-end` folder and type `python3 main.py` in to start.
2. Go to the `front-end` folder and type `npm install`.
3. In the same folder, type `npm start`, and this will display a webpage.

# Funcionalties of database-driven application
1. View information about the movie selected based on the name. (ex. `The Matrix`)

# Members
Claire Sheng

Ganlin Feng

Junyi Liu

Yuming Long

