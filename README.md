# Library Management System

## Overview
This Android application serves as a comprehensive Library Management System, allowing users to borrow, return, and search for books. Users can access these functions by logging in with a username and password.

## Features
- **Login:** Users can log in with their credentials to access the system.
- **Borrow Books:** Users can borrow books by providing necessary details such as Book Title, Author Name, ISBN No, Borrower Name, and borrow date.
- **Return Books:** Users can return borrowed books, specifying borrower details and updating the database accordingly.
- **Search Books:** Users can search for books, whether they are borrowed or not.

## Behind the Scenes
Behind the scenes, the application uses an SQLite database to efficiently store and manage all library data. The database consists of tables for Borrow details, return details, and users' details, ensuring a well-organized and structured data management system.

## User Experience
To enhance user experience, the application includes error handling features to ensure data integrity and proper functioning. It provides error messages for incomplete form submissions and failed database operations, ensuring a smooth user experience.
