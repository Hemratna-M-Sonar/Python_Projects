# Python_Projects
It contains 4 python projects, Random password generator, Calculator, Library management system and Typing speed test.

1. Random Password Generator
  This is a simple python project which creates a random password using 'secrets' library

2. Calculator
  A basic calculator app using Core Python and Tkinter GUI.

3. Typing Speed Test
  A typing speed test app uysing Tkinter.

4. Library management system.
  A complete library management system using Python and Tkinter.
  It has following features:
    Add a book in library.
    Delete a book.
    Issue a book.
    Return a book.
    View all books.
  
How to run Library Management system project:

  Note: You need to have MySQL downloaded in your system.

  Execute the following commad to install all required packages:
    pip install -r requirements.txt
    
  
  Create a Database:
    create database db;
   
  create tables for books and books issued:
    create table books(bid varchar(20) primary key, title varchar(30), author varchar(30), status varchar(30));
    create table books_issued(bid varchar(20) primary key, issuedto varchar(30));

  Replace your myswl password in all files.
  
  Then Execute following command:
     python main.py
