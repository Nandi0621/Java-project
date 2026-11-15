# Java-project
A short beginner java project that was designed to display a library management system for a local community library
# Library Management System (LMS)

## 📚 About the Project

The Library Management System (LMS) is a console-based Java application developed to help a community library manage its books, registered members and borrowing activities.

The system provides separate functionality for librarians and library members. Librarians can manage books and members, while members can search for books, borrow available books and return borrowed books.

This project demonstrates the application of core Java programming concepts and Object-Oriented Programming (OOP) principles.

## 🎯 Project Objectives

- Develop a fully object-oriented Java application.
- Manage library books and member information.
- Allow members to borrow and return books.
- Implement role-based login functionality.
- Apply encapsulation, inheritance, abstraction and polymorphism.
- Practise Java collections, methods and exception handling.

## 🛠️ Technologies Used

- **Programming Language:** Java
- **IDE:** Apache NetBeans
- **Data Structures:** Arrays and ArrayLists
- **Date and Time:** Java LocalDate API
- **String Handling:** String and StringBuilder
- **Application Type:** Console-based application

## ✨ System Features

### 1. Book Management
- Add new books to the library.
- Display all available and borrowed books.
- Search for books by title or author.
- Track the availability status of each book.

### 2. Member Management
- Register new library members.
- Store member identification and personal information.
- Record member joining dates using LocalDate.
- Display registered members and their borrowed books.

### 3. Borrowing and Returning Books
- Allow members to borrow available books.
- Automatically update book availability when borrowed.
- Allow members to return borrowed books.
- Handle unavailable book requests using a custom exception called `BookNotAvailableException`.

### 4. Login and User Roles
The system supports two user types:

- **Librarian:** Accesses book management, member registration and library management functions.
- **Member:** Accesses book searching, borrowing and returning functions.

Members can log out when they have finished using the system.

## 💻 Java Concepts Demonstrated

This project demonstrates the following Java concepts:

| Java Concept | Application |
|---|---|
| Classes and Objects | Book, User, Librarian and Member classes |
| Encapsulation | Private fields and controlled access through methods |
| Inheritance | Librarian and Member extend User |
| Abstract Classes | User serves as an abstract parent class |
| Polymorphism | Different implementations of getRole() |
| ArrayLists | Storing books and members |
| Arrays | Practising basic data storage |
| Methods | Organising system functionality |
| Strings | Handling book titles, authors and names |
| StringBuilder | Formatting book information |
| LocalDate | Recording member joining dates |
| Exception Handling | Handling invalid input and unavailable books |

## 📂 Project Structure

The application is organised around the following classes:

LibraryManagementSystem/
│
├── src/
│   ├── Book.java
│   ├── User.java
│   ├── Librarian.java
│   ├── Member.java
│   ├── BookNotAvailableException.java
│   └── LibraryManagementSystem.java
│
└── README.md

*Note: Adjust the file structure above to match your actual Java project.*

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Open Apache NetBeans.
3. Select **File → Open Project**.
4. Locate and open the Library Management System project.
5. Run the main Java class.
6. Follow the console menu instructions to use the system.

## 🎓 Learning Outcomes

Through this project, I developed my understanding of:

- Object-Oriented Programming principles.
- Java classes, objects and inheritance.
- Managing data using ArrayLists.
- Implementing custom exception handling.
- Working with dates and times.
- Developing menu-driven console applications.
- Organising code into reusable methods and classes.

## 👩‍💻 Author

**Nandipha Ngqulana**

Bachelor of Science in Information Technology  
Eduvos

This project was developed as part of my academic coursework in Java programming and software development.
