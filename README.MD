## System for Library Management  with Java, Spring Boot, and PostgreSQL

### Overview:
This Library Management System utilizes Object Oriented Analysis and Design principles to create a robust and user-friendly application.

### Actors:
The system features the following key actors:
- **Student**
- **Borrower**
- **Administrator**

### Use Cases:
Identifying the tasks that each actor will perform with the system is essential. These tasks, known as use cases, represent specific functionalities that help solve the customer’s needs.

#### Student Use Cases:
- **Search for books by title.**
- **Search for books by author.**
- **Search for books by category.**
- **View details of a book.**
- **View details of an author.**
- **View details of a category.**
- **Borrow a new book.** *Books can be borrowed if available, with a return date set between the current date and three months from now.*
- **View the list of currently borrowed books.**
- **Return borrowed books.**

#### Administrator Use Cases:
- **Search for books by title.**
- **Search for books by author.**
- **Search for books by category.**
- **View details of a book.**
- **View details of an author.**
- **View details of a category.**
- **Update the available quantity of a book.**
- **Add, delete, or modify book records.**
- **Add, delete, or modify category records.**
- **Add, delete, or modify author records.**

### Technology Stack:
- **Spring Boot**
- **Spring Data JPA**
- **H2 Database**
- **Thymeleaf**
- **Bootstrap 4**
### Prospective Implementation:
- **Future updates will include integrating GraphQL to enhance the system's performance and flexibility.**