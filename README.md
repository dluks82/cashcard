# CashCard Application

Reproduced from the course 'Building a REST API with Spring Boot' by Spring Academy

## Overview

The CashCard Application is a simple demonstration project showcasing the implementation of a REST API using Java and various Spring projects. The application utilizes the H2 in-memory database and includes features such as web security, data access, and testing.

## Technologies Used

- Java
- Spring Boot
- Spring Web
- Spring Security
- Spring Data JDBC
- Spring Test
- H2 Database

## Getting Started

### Prerequisites

- Java 11 or higher
- Maven

### Installation

1. Clone the repository:

    ```bash
    git clone git@github.com:dluks82/cashcard.git
    ```

2. Navigate to the project directory:

    ```bash
    cd cashcard
    ```

3. Build the project:

    ```bash
    mvn clean install
    ```

4. Run the application:

    ```bash
    mvn spring-boot:run
    ```

### Accessing the Application

The application will be running at `http://localhost:8080`.

### Using H2 Database Console

The H2 database console can be accessed at `http://localhost:8080/h2-console`. Use the following credentials:

- **JDBC URL:** `jdbc:h2:mem:testdb`
- **Username:** `sa`
- **Password:** *(leave blank)*

## Endpoints

### CashCard Endpoints

- `GET /cashcards` - Retrieve a list of all cash cards
- `GET /cashcards/{id}` - Retrieve a specific cash card by ID
- `POST /cashcards` - Create a new cash card
- `PUT /cashcards/{id}` - Update an existing cash card
- `DELETE /cashcards/{id}` - Delete a cash card

### Authentication

This application uses basic authentication. Include the appropriate `Authorization` header with your requests.

## Running Tests

To run the tests, execute:

```bash
mvn test
```

### Contributing

Contributions are welcome! Please fork the repository and submit pull requests.

## License

This project is licensed under the MIT License.

## Contact Information

**Developer:** Diogo Lucas de Oliveira  
**Email:** [dluks82@gmail.com](mailto:dluks82@gmail.com)  
**LinkedIn:** [Diogo Lucas de Oliveira](https://www.linkedin.com/in/diogo-lucas-de-oliveira/)