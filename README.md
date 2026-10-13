# Library Management System

A simple menu-driven Library Management System developed using Python. This project helps manage library books and their availability.

## Features

* Add books
* Search books by Book ID
* Issue books to students
* Return books
* Display available books
* Display all books
* Save library records

## Technologies Used

* Python
* JSON
* File Handling

## How to Run

1. Install Python on your computer.
2. Download or clone this repository.
3. Open the project folder in a terminal.
4. Run the following command:

```bash
python library_management.py
```

## Example

The program displays the following menu:

```text
======================================
       LIBRARY MANAGEMENT SYSTEM
======================================
1. Add Book
2. Search Book
3. Issue Book
4. Return Book
5. Display Available Books
6. Display All Books
7. Save Records
8. Exit
======================================
```

## Example Book Record

* **Book ID:** B101
* **Title:** Introduction to Statistics
* **Author:** S. C. Gupta
* **Status:** Available

## Data Storage

The book records are stored in a JSON file named `library.json`. The program saves the records when the user selects Save Records or Exit.

## Project Structure

```text
Library-Management-System/
├── library_management.py
├── library.json
└── README.md
```

## Author

Sukanya
