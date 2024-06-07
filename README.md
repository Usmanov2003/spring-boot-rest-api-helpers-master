Spring Boot REST API Helpers



Introduction
The Spring Boot REST API Helpers library provides utility classes and methods to streamline the development of RESTful APIs in Spring Boot applications. It includes functionalities for request and response handling, error handling, pagination, sorting, and more.

Features
Request and response utilities for handling common tasks.
Error handling mechanisms for consistent error responses.
Pagination and sorting helpers for data retrieval endpoints.
JWT (JSON Web Token) utilities for authentication and authorization.
Validation helpers for request payload validation.
Prerequisites
Before you begin, ensure you have the following installed on your local machine:

Java Development Kit (JDK) 8 or later
Maven 3.6.0 or later
An IDE like IntelliJ IDEA or Eclipse
Git
Installation
To use the Spring Boot REST API Helpers library in your project, add the following dependency to your pom.xml file:

xml
Copy code
<dependency>
    <groupId>com.example</groupId>
    <artifactId>spring-boot-rest-api-helpers</artifactId>
    <version>1.0.0</version>
</dependency>
Usage
Request and Response Helpers
Use RequestHelper for extracting request parameters and headers.
Use ResponseHelper for constructing standardized response entities.
Error Handling
Implement custom exception classes extending ApiException.
Use ExceptionHandler to handle exceptions and generate appropriate error responses.
Pagination and Sorting
Use PaginationHelper for paginating lists of data.
Use SortHelper for sorting lists of data based on specific fields.
JWT Utilities
Use JwtTokenProvider for generating and validating JWT tokens.
Validation Helpers
Use ValidationHelper for validating request payloads using Bean Validation annotations.
Contributing
Contributions are welcome! Please follow these steps to contribute:

Fork the repository.
Create a new branch:
sh
Copy code
git checkout -b feature-name
Make your changes and commit them:
sh
Copy code
git commit -m 'Add some feature'
Push to the branch:
sh
Copy code
git push origin feature-name
Open a pull request.
License
This project is licensed under the MIT License - see the LICENSE file for details.
