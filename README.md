# Book-Management-System

Overview
The Book Catalog Management System is a Java project designed to facilitate the organization and testing of a collection of books. This system provides classes for individual books (Book) and a catalog of books (BookCatalog). The primary functionalities include adding books to the catalog, retrieving books by title or author, and calculating word counts.

Features

Book Class:

The Book class represents individual books and contains methods for extracting information about the books.
Each book has attributes such as title, author, and lines containing the content of the book.
The Book class includes methods to get the title, author, total word count, unique word count, and specific word count in a book.
The class also has a constructor that takes a list of lines to initialize a book.
BookCatalog Class:

The BookCatalog class serves as a catalog or collection of books.
It has methods for adding books to the catalog and retrieving books by title or author.
The catalog is implemented using a map, where the keys are book titles, and the values are Book objects.
The BookCatalog class includes a method to get the entire book catalog in the form of a map.
BookFileReader:

This class, not explicitly provided, is likely used for reading and parsing book files. It is referenced in the test setup to load and parse book files.
Testing:

The project includes comprehensive unit tests in the BookCatalogTest and BookTest classes.
Test cases cover various aspects of the functionality, including adding books to the catalog, retrieving books by title or author, and calculating word counts.
The tests are annotated with JUnit annotations (@Test, @BeforeEach) and include assertions to verify that the actual results match the expected results.


