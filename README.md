# LmsDevaney
Robert Devaney 
CEN-3024C-15339

This program is a Library Management System (LMS) for managing a collection of books. The system is implemented in Java.

    Display All Books: Displays a list of all books currently in the system.
    Remove a Book: Allows the removal of a book from the system using its unique ID. 
    Add a Book: Users can input details about a book, including its unique ID, title, and author.   

Usage

When you run the application, a main menu will be displayed, allowing you to choose from the following options:

    1: Display All Books
    2: Remove a Book by ID
    3: Add a Book
    4: Exit
    
Input the relevant information as prompted by the dialog boxes for each option. The application will validate the input to ensure that it meets the expected criteria (unique ID, and title). Use the summary option to view an overview of the library’s holdings.

Requirements

    Java Development Kit 
    IntelliJ IDEA for development

Classes

    Main: Handles the main menu and controls the flow of the application.
    Book: Represents a book with attributes such as unique ID, title, and author.
    Library: Manages the collection of books and operations such as adding or removing books.
    FileHandler: Handles the input and output operations for books via text files.
