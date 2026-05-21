# Library Management System in C

A console-based Library Management System developed using the C programming language to manage books, records, and library operations efficiently.

## Project Overview

This project demonstrates file handling, structures, functions, and data management concepts in C programming.

The system allows users to:

* Add books
* Search books
* Delete records
* Issue and return books
* Manage library inventory

---

# Features

* Book record management
* Search functionality
* File handling using CSV/Text files
* Console-based interface
* Structured programming approach
* Data storage and retrieval

---

# Technologies Used

* C Programming
* File Handling
* Structures
* Functions
* Visual Studio 2022

---

# Core Concepts Implemented

## Structures

```c id="g7n2x4"
struct Book {
    int id;
    char title[50];
    char author[50];
};
```

## File Handling

```c id="b9m4k8"
FILE *fp;
fp = fopen("library.csv", "r");
```

## Functions

* Add Book
* Delete Book
* Search Book
* Display Records

---

# Future Improvements

* Add graphical user interface
* Add user authentication
* Implement database integration
* Add overdue fine calculations
* Convert to web-based application

---

# Learning Outcomes

This project helped improve understanding of:

* File handling in C
* Data structures
* Menu-driven applications
* Real-world problem solving
* Modular programming

---

# Author

Daksh Patel

*Enhanced and customized library management system project using C programming and file handling concepts.*
