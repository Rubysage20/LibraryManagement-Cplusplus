This project implements a Library Management System in C++ that helps manage books, members, and transactions in a library. It allows for the addition of books, registration of members, borrowing and returning books, and tracking of transactions.

Features
Book Management:

Add new books

Display all books

Search books by title, author, or ISBN

Update book details

Member Management:

Register new library members

Update member information

Display all registered members

Transaction Management:

Borrow books

Return books

Display all transactions

Track overdue books

Reports:

Generate reports for all books, members, and transactions

Project Structure:

LibraryManagement

This class manages the library's books, members, and transactions.

addBook: Adds a new book to the library.

updateBookInfo: Updates the information of a book (e.g., ISBN, author).

displayAvailableBooks: Displays all available books in the library.

registerMember: Registers a new library member.

updateMemberInfo: Updates member information (e.g., contact info).

displayRegisteredMembers: Displays a list of all registered members.

borrowBook: Allows a member to borrow a book and sets a due date.

returnBook: Marks a book as returned.

displayBorrowedBooks: Displays all borrowed books.

displayOverdueBooks: Displays a list of overdue books.

searchBooksByTitle/Author/ISBN: Allows searching for books based on their title, author, or ISBN.

generateReport: Generates a report for all books, members, and transactions.

Library:
This class handles the operations such as adding books, registering members, and processing transactions.

addBook: Adds a book by title, author, and ISBN.

displayAllBooks: Displays details of all books.

registerMember: Registers a new member with name and contact information.


displayAllMembers: Displays details of all registered members.


borrowBook: Allows a member to borrow a book by index and sets a due date.


displayAllTransactions: Displays details of all transactions (book borrowings).


Book:This class represents a book with attributes such as title, author, and ISBN.


displayBookDetails: Displays the details of the book.


Member:This class represents a library member with attributes such as name and contact information.


displayMemberDetails: Displays the details of the member.


Transaction: This class represents a borrowing transaction between a book and a member, including a due date.


displayTransactionDetails: Displays the details of the transaction

Usage: 
Adding Books: You can add books to the library with a title, author, and ISBN.

Registering Members: Members can be registered with their name and contact details.

Borrowing Books: Members can borrow books from the library. Each borrowing transaction records the book, member, and due date.

Displaying Information: You can display all books, members, and transactions at any point.

Updating Information: Books and members can have their information updated as needed.
