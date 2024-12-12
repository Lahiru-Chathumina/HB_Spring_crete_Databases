# Hibernate with Spring Boot

This project demonstrates the integration of Hibernate with Spring Boot for managing a shopping database.

## Features
- User entity to manage user details such as ID, name, price, and cloth name.
- MySQL database integration with Hibernate for data persistence.
- Configuration via `application.yml` file.

## Prerequisites

Before running the project, ensure you have the following:

- Java 11 or higher
- MySQL database
- Maven build tool
- An IDE with Git and Spring Boot support

## Configuration

1. Update the database credentials in `application.yml`:
   ```yaml
   spring:
     datasource:
       url: jdbc:mysql://localhost:3306/DB_Shoping
       username: <your-username>
       password: <your-password>
   ```
2. Ensure the database `DB_Shoping` exists in MySQL.

## Running the Project

1. Clone this repository:
   ```bash
   git clone <repository-url>
   ```
2. Navigate to the project directory:
   ```bash
   cd Hibernate-with-Spring-Boot
   ```
3. Build the project using Maven:
   ```bash
   mvn clean install
   ```
4. Run the application:
   ```bash
   mvn spring-boot:run
   ```

## Entity Details

The `user` entity contains the following fields:
- `userId`: Unique identifier for the user (Primary Key).
- `userName`: Name of the user (Required).
- `price`: Price associated with the user.
- `clothName`: Name of the cloth.

## Technologies Used

- **Spring Boot**: Framework for building Java applications.
- **Hibernate**: ORM tool for database interaction.
- **MySQL**: Database for data storage.

## Contributing

Feel free to fork this project and submit pull requests. Contributions are welcome!

## License

This project is licensed under the MIT License. See the LICENSE file for details.
