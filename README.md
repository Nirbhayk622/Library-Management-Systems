# Library-Management-Systems
A simple Java-based Library Management System built using Object-Oriented Programming (OOP) concepts.
This project demonstrates fundamental Java principles such as Encapsulation, Abstraction, and Collections, implemented in a console-based environment.
Developed using Notepad and Command Prompt, and uploaded to GitHub to showcase strong Java coding skills without IDE dependency.

✨ Features

➕ Add new books to the library

🔍 Search books by title or author

❌ Delete books from the collection

👥 Manage users (basic structure for members and borrowing)

🖥️ Console-based interface for simple and direct interaction

💾 Uses ArrayList to store and manage data in runtime

🧱 Project Architecture
Library-Management-System/
│
├── Book.java        # Defines the Book class with book details and methods
├── Library.java     # Manages the book list: add, delete, search, display
├── User.java        # Represents library users with basic information
├── Main.java        # Entry point; handles user input and menu-driven system
└── README.md        # Project documentation

🧩 Class Overview
Book.java

Represents individual books in the library.

Contains attributes like title, author, and isbn.

Includes methods to get/set book details and to display book information.

User.java

Defines basic information about a library user such as name and userId.

Can be extended to include borrowing or returning functionality in the future.

Library.java

Core class that manages the library’s collection of books.

Provides methods for:

addBook()

searchBook()

deleteBook()

displayBooks()

Internally uses an ArrayList to store Book objects.

Main.java

Contains the main() method.

Acts as the entry point for the program.

Provides a menu-driven console interface for user interaction (Add, Delete, Search, Display, Exit).

🚀 How to Run

Clone or download this repository:

git clone https://github.com/yourusername/Library-Management-System.git


Open terminal / command prompt in the project directory.

Compile all Java files:

javac *.java


Run the main program:

java Main


Follow the on-screen menu to add, delete, or search books in the library.

🧠 Concepts Used

> Object-Oriented Programming (OOP)

> Encapsulation & Abstraction

> ArrayList (Java Collections)

> User Input Handling (Scanner class)

> Control Flow (if-else, switch, loops)

> Modular Code Design

🛠️ Technologies
Component	Technology Used
Language	Java
Paradigm	Object-Oriented Programming
Interface	Console-based
Tools Used	Notepad, Command Prompt, GitHub
💡 Future Enhancements

🗂️ Add file handling for saving and loading data

🔑 Implement user login and authentication (Admin/User)

🧾 Add book issue/return system

🪄 Build a GUI version using JavaFX or Swing

🛢️ Connect with MySQL database for permanent storage

👨‍💻 Author

Nirbhay Kumar
📧 nirbhayk622@gmail.com

💻 GitHub Profile
