# Movies Record Tracking System

*Project Description:* Movie Search and Display System

This project involves creating a movie search and display system that allows users to search for movies based on their genres. The system reads movie data from a file, stores it in an array of structures, and provides a user interface for searching and displaying movies based on user input.

*TechStack:*
- C++ (Object Oriented Approach) Programming Language

*Main Program (w1p1.cpp):*
The main function serves as the entry point of the program.
It initializes an array of structures (Movie) to store movie information.
The program loads movie data from a file ("movies.dat") using functions defined in the "File.h" and "File.cpp" files.
Users can repeatedly enter a movie genre, and the program displays movies that match the entered genre.
The user can choose to perform another search or exit the program.

*Movie Structure (Movie.h and Movie.cpp):*
The Movie structure represents a movie and contains fields such as title, year, rating, duration, genres, and consumer rating.
The "Movie.cpp" file defines functions for loading movies from a file, checking if a movie has a specific genre, displaying movie information, and displaying movies with a given genre.

*File Operations (File.h and File.cpp):*
The "File.h" file declares functions for file operations, such as opening and closing the data file, and reading various attributes of a movie from the file.
The "File.cpp" file implements these functions using file I/O operations.

*Utility Functions (main.cpp and Movie.cpp):*
The program includes utility functions like flushkeys() to clear the keyboard buffer and yes() to get user confirmation.
The hasGenre function in "Movie.cpp" checks if a movie has a specific genre.

*User Interface:*
The user is prompted to enter a movie genre for the search.
The program displays movies that match the entered genre.
The user can choose to perform another search or exit the program.

*Error Handling:*
The program handles errors in file operations and ensures that the file is successfully opened before attempting to read movie data.

*Project Structure:*
The project is organized into multiple files, promoting modularity and code separation.
Namespaces (sdds) are used to encapsulate related functions and structures.
This movie search and display system provides a simple and interactive way for users to explore a collection of top movies based on their genres.

*How to RUN this project?*
```
Set up your development environment:
Make sure you have a C++ compiler installed on your system. You can use an integrated development environment
(IDE) like Visual Studio, Code::Blocks, or any other C++ compiler.

Download or clone the project:
Download the source code files for your project, or clone the repository if it's hosted on a version control platform like GitHub.

Open the project in your C++ IDE:
Open the main project file, typically named main.cpp or a file specified as the entry point, in your C++ IDE.

Build the project:
Build the project to compile the source code. This process may involve clicking a "Build" or "Compile" button in your IDE.

Run the executable:
After successfully building the project, locate the generated executable file. The name of the executable file is usually
the same as the project name or as specified in your IDE.
Run the executable by double-clicking on it or executing it from the command line.

Provide input during execution:
Follow the prompts in the console or command line interface to enter a movie genre for the search.
The program will display movies matching the entered genre and ask if you want to perform another search.

Interact with the program:
Continue entering genres and exploring the movies until you choose to exit the program.

Review the output:
The program will display relevant information about the movies that match the entered genre.

Exit the program:
When you are done exploring, choose to exit the program when prompted.

Check for errors:
If any errors occur during execution, review the error messages in the console or command line to identify and address the issues.
Remember that the specific steps may vary based on the C++ IDE you are using.
```
