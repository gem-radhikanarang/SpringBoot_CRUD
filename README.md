# Student Management System

 

This Student Management System is a simple Spring Boot Rest API project that manages a collection of operations, the CRUD operations - Create, Read, Update and Delete. It allows us to manage student records and perform CRUD operations on student records. 

 

## Requirements

 

- Java 8 or higher
- MySQL server 8.0.31 or higher

 

## Getting started

 

1. Clone the repository to your local machine.
   ```
   git clone https://github.com/yourusername/student-management-system.git
   ```
2. Import the project into your preferred IDE (such as Eclipse or IntelliJ) as a Maven project.
3. Update the `application.properties` file in the `src/main/resources` directory with your MySQL database configuration.
4. Build and run the application using Maven. From the command line, navigate to the project directory and run:
   ```
   mvn spring-boot:run
   ```
5. Access the application by visiting `http://localhost:9111` in your web browser.

 

## Usage

 

Once the application is running, you can perform CRUD operations on student records via the REST API.

 
 

### REST API

 

The REST API provides programmatic access to the application's functionality. The API supports the following endpoints:

 

- `GET /api/subjects`: Returns a list of all student records in the database.
- `POST /api/subjects`: Creates a new student record in the database.
- `GET /api/subjects/{id}`: Returns the student record with the specified ID.
- `PUT /api/subjects/{id}`: Updates the student record with the specified ID.
- `DELETE /api/subjects/{id}`: Deletes the student record with the specified ID.

 

All endpoints return JSON data.

 

## Contributing

 

If you find a bug or have a new idea, feel free to open an issue or submit a pull request. Contributions are always welcome.

 

## License

 

This project is licensed under the MIT License. See the `LICENSE` file for details.

has context menu
