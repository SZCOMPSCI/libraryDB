# Library Management App

A Java-based desktop application for managing a small library database. Users can add, update, delete, and search for books and manage library members. The app connects to a MySQL database to store and retrieve data.

## Features

- **Book management**
  - Add new books
  - Update existing book details
  - Delete books
  - Search for books by title, author, or genre
- **Member management**
  - Add and remove library members
  - Track borrowed books
- Simple graphical interface using Java Swing
- Database connection and CRUD operations with MySQL

## Usage

1. Clone or download the repository.  
2. Ensure MySQL is installed and running on your machine.  
3. Import the provided SQL file (`libraryDB.sql`) into your MySQL server to create the necessary database and tables.  
4. Update the database connection settings in `LibraryApp.java` if needed (username, password, database name).  
5. Compile and run the application:
   ```bash
   javac *.java
   java LibraryApp

## Technologies Used

- Java (JDK 11+)
- Swing (Java GUI library)
- MySQL

## Skills Demonstrated

-Java GUI development using Swing
-Database design and SQL queries
-CRUD operations (Create, Read, Update, Delete)
-Connecting a Java application to a MySQL database
-Debugging and testing a desktop application

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

*Created by Saif Zagloul*
