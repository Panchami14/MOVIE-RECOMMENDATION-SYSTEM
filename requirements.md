# Software Requirements Specification (SRS) for the Console Movie Recommender

    This document outlines the detailed functional and non-functional requirements for the Movie Recommendation System.

1. Functional Requirements (FR)

These requirements define the specific actions the system must perform to meet the user's needs.

1.1 Core System Functionality

FR001: The application must continuously display a main menu until the user selects the 'Exit' option.

FR002: The application must handle invalid menu choices by prompting the user to re-enter a valid option (1-5).

FR003: The application must clearly print the list of recommended movie titles for any successful query.

FR004: The application must provide a 'No movies found' message when a query yields zero results.

1.2 Recommendation Logic

FR005 (Genre Search): The function must perform a case-insensitive search for a partial match within the movie's genre string.

FR006 (Actor Search): The function must perform a case-insensitive search for a partial match within the movie's actor string.

FR007 (Year Range): The function must accept two integer inputs (start and end year) and return all movies released within that range (inclusive).

FR008 (Similar Movies): The function must identify the target movie by title (case-insensitive) and return all other movies that share at least one genre with the target.

FR009 (Exclusion): The similar movies function must ensure the target movie itself is not included in the output list.

2. Non-Functional Requirements (NFR)

These requirements specify criteria that can be used to judge the operation of the system, such as performance and maintainability.

2.1 Performance and Reliability

NFR001 (Performance): All search and filtering operations must complete and display results instantly (sub-100ms response time).

NFR002 (Error Handling): The system must gracefully handle non-integer input for year range queries without crashing.

2.2 Maintainability and Usability

NFR003 (Maintainability): The movie dataset must be easily editable and extendable by modifying the movies list at the top of the script.

NFR004 (Dependencies): The codebase must be entirely self-contained within a single Python file, with no external library dependencies.

NFR005 (Usability): The console output must be well-formatted using clear headers and simple lists to enhance readability.