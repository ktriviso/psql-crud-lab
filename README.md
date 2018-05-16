# SQL 64

![n64](https://i.giphy.com/KMrye8vZpv6py.gif)

## PSQL and CRUD

You will be using what you know about Postgres to implement CRUD functionality through a series of queries.

**What is CRUD?**

Good question! It is the basic functions of persistent storage. Basically how you can interact with data. These functions are:
* **C** - Create or add new entries
* **R** - Read, retrieve, search, or view existing entries
* **U** - Update or edit existing entries
* **D** - Delete, destroy, or remove existing entries

## Setup

Work in the `n64_psql.sql` file. Some SQL has been provided for you to create and seed a base database. Run `psql -f n64_psql.sql` after each step to check your work!


## Queries

Use SQL queries to complete parts 1 - 4. 

### Part 1 - Create
1. Add the the game 'F-Zero X', released in 1998, made by 'Nintendo EAD', and with the genre 'Racing'.
2. Add the the game 'The Legend of Zelda: The Ocarina of Time', released in 1998, made by 'Hudson Soft', and with the genre 'Action-Adventure'.

### Part 2 - Read
1. Select the title of all games
2. Show the title of each game made by 'Rare'.
3. Select all games that were made before 1998.
4. Find the average release year of all games made by 'Nintendo EAD'
5. Show the developer names of each game, in alphabetical order.
6. Show all the game titles in descending order of their release year.

### Part 3 - Update
1. Oops! 'The Legend of Zelda: The Ocarina of Time' was actually made by 'Nintendo EAD'. Update the database to have the correct information.
2. Nintendo 64 was released in 1995 but some of the games say they were released in 1995! Update the 1995 games to have the year of 1996
    * *BONUS: Return the names of all the games you updated HINT: look up `RETURNING`*

### Part 4 - Delete
1. Remove all games made by 'Lucas Arts'.
2. Remove all games made in 1999 or after.

### BONUS - 
1. Show the average release year for games that were made by Rare or have the title 'Tony Hawks Pro Skater'
2. Show the id and title and genre of all games that were either:
    * Made before 1997,
    * Made by Hal Laboratory,
    * or, have the genre Platforming AND are made by Rare.
3. Show the title and genre for all games that have 'Mario' in their name.
    * *HINT: look up `LIKE`*
4. Show the genre and the average year of each of the genres
    * *HINT: look up `GROUP BY`*
    
    
    
 ## Submission

Homework is due by **11:00 tonight**! Remember to work with each other and go to TAs when you need it, but follow the [guidelines](https://github.com/teikmeout/gracehopper) for queuing. Follow the normal [rules for homework submission], remember to include a link to your **repo**.
