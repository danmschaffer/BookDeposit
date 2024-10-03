# BooksVault


**BookVault** is a simple yet effective command-line application designed to manage a personal book collection. The application allows users to add new books, list all books, mark books as read, and delete entries. It offers a minimalistic interface to perform essential operations for organizing a book library.

**Features:**

**Add a New Book –** Users can input a book's name and author to store it in the collection.

**List All Books –** Displays a list of all stored books, along with their read status.

**Mark as Read –** Users can update a book's status once they’ve completed reading it.
**Delete a Book –** Allows removal of a book from the collection.

**Persistent Storage –** The app uses a local database for persistent book data, ensuring that the collection is maintained even after closing the program.

**Code Structure:** The app follows a modular approach to ensure clean separation between user interaction and data handling:

**User Interface:** A simple command-line interface guides users with options to perform different actions.
**Database Layer:** The database module (from utils) handles all data operations, such as creating the book table, adding entries, updating the read status, and deleting records.

**Technologies Used:**

__Python –__ Core programming language.

__SQLite (via database module) –__ Manages persistent storage of book data.

**Potential Enhancements:**

**Add support for book genres, ratings, or reviews.

**Implement a graphical user interface (GUI) for a more user-friendly experience.

**Expand to include search and sorting features to better manage larger collections.

**Introduce cloud-based storage for accessibility across multiple devices.
