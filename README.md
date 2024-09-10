# Library System Full Stack Assignment
- This University assignment uses PostgreSQL, Java and JavaFX
- The University provided the template for the assignment, they have indicated which parts I will need to code myslef by marking specific parts //TO BE COMPLETED.
- This assignment involves developing a 3 tier TCP-based networking multi-threaded client-server application to consult a database about books.
- The server consists of 2 classes; one is the main server which attends to requests as they arrive on an infinite loop. The other is the server's service provider which connects to the database using JDBC (Java Database Connectivity), this class retrieves the outcome of the query and sends back the outcome to the client.
- The service provided is a fixed but parametrizable query; given the author's family name and a library's city, the query must retrieve the list of books available from the author at the indicated library.
- For each title available, the query will retrieve, the book's title, the publisher, the genre, the recommended retailer's price and the number of copies available for that title at the library. Books from the author that are not available in the library will not be listed.

## Retrieving Data from the Database
- The database provided contained multiple tables. I had to analyse the different tables and create an SQL query to retrieve the required information.
- The SQL query I made includes parameters that the user must input into the system.

![SQL code](https://github.com/ElairaP/Library-system-assignment/blob/main/A4%20sql%20screenshot.png)

## Example Outputs
![Example output](https://github.com/ElairaP/Library-system-assignment/blob/main/A4%20example%20output%201.png)
