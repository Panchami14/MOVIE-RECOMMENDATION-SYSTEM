# Project Statement for the Console Movie Recommender

- Problem Statement

  In the early stages of learning data processing and filtering, there is a need for simple, demonstrable projects that showcase fundamental search and logic capabilities. This project addresses the challenge of building a lightweight system that can efficiently retrieve and filter structured data (movies) based on specific user input parameters (Genre, Actor, Year), serving as a clear foundation for more complex recommendation logic.

 - Scope of the Project

   The scope of this project is strictly limited to a basic, content-based recommendation engine operating entirely within the console environment.

 - In Scope:

    Implementation of the four core filtering functions: Genre, Actor, Year Range, and Genre Similarity.

    Case-insensitive and partial matching logic for inputs (e.g., actor names).

    Handling user input via the command line and displaying output to the console.

    Utilizing an internal, static dataset (Python list of dictionaries).

 - Out of Scope (Future Work):

    Integration with external APIs or databases (e.g., IMDb, TMDB).

    Graphical User Interface (GUI) or web application frontend.

    Machine Learning models or complex collaborative filtering algorithms.

    User ratings, personalized history, or dynamic data updates.

# Target Users
1. The primary users for this project are focused on 
   demonstration and foundational learning:

2. Developers/Students: Individuals learning Python 
   who need a simple, clear example of data filtering and object-oriented thinking.

3. Code Reviewers: Users assessing proficiency in 
   fundamental data structures and control flow.

4. Casual Users: Anyone looking for quick, 
   non-personalized movie suggestions based on basic attributes.

5. High-Level Features

6. Efficient Data Traversal: Uses iterative techniques 
   to quickly search a small dataset.

7. Modular Function Design: Separates each   
   recommendation logic into distinct, reusable Python functions.

8. Similarity Matching: Provides a basic 
   implementation of content-based similarity by matching genre keywords.