🎬 Console-Based Movie Recommendation System

# Overview of the Project

        This is a simple, command-line interface (CLI) application developed in Python to provide movie recommendations from a predefined, static dataset. The system supports various content-based filtering methods, allowing users to search for movies by genre, actor, year range, and find similar titles based on genre overlap. The project serves as a clear demonstration of fundamental Python programming concepts, including list and dictionary manipulation, function design, and basic user input handling.

# Features

        - Recommend by Genre: Filters the movie list to display all titles matching a user-specified genre keyword (e.g., "Drama").

        - Recommend by Actor: Searches for all movies featuring a specific actor, supporting partial name matching.

        - Recommend by Year Range: Filters movies released between a user-defined start year and end year.

        - Recommend Similar Movies: Finds other movies that share at least one genre with a selected movie title.

        - Interactive CLI Menu: Provides a simple, numbered menu for user navigation and selection.

# Technologies/Tools Used

We utilized the following tools and technologies to build the system:

Language: Python 3.x (Core programming language for all logic and CLI implementation).

Data Storage: Python List and Dictionaries (Used for the hardcoded, static dataset of movie records).

Environment: Command Line Interface (CLI) (Used for all user interaction and output display).

Version Control: Git / GitHub (Standard source code management).


# Steps to Install & Run the Project

This project uses only core Python functionality, requiring no external libraries.

1. Requirements

Ensure you have Python 3.x installed on your operating system.

2. File Setup

Clone this repository or download the Python script (movie_recommender.py).

Open your terminal or command prompt.

Navigate to the directory where the file is saved.

3. Run the Application

Execute the script directly using the Python interpreter:

python movie_recommender.py


4. Interactive Usage

Once running, the main menu will appear. Enter the number corresponding to the recommendation option you wish to use (1-4) or '5' to exit.

# Instructions for Testing (Manual)

 - To test the application, run the script and 
   manually check the following scenarios:

 - Test Genre Filter (Option 1):

 - Input: Sci-Fi -> Expected Output: Koi Mil Gaya, 
   Inception, Avatar.

 - Input: Horror -> Expected Output: The Conjuring.

 - Input: Fantasy -> Expected Output: Baahubali.

Test Actor Filter (Option 2):

 - Input: Leo -> Expected Output: Inception, Titanic 
   (tests partial match).

 - Input: Aamir Khan -> Expected Output: 3 Idiots, 
   Dangal.

 - Test Year Range (Option 3):

 - Input Start: 2015, End: 2019 -> Expected Output: 
   Dangal, Baahubali, Gully Boy, KGF Chapter 1, Drishyam, Avengers Endgame.

 - Test Similar Movies (Option 4):

- Input: 3 Idiots (Genre: Comedy, Drama) -> Expected 
  Output: Dangal, Gully Boy, Kantara, Titanic (all share 'Drama').

- Input: Inception (Genre: Sci-Fi, Thriller) -> 
  Expected Output: Koi Mil Gaya, Avatar, Drishyam, The Dark Knight.