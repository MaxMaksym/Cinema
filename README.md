# Cinema App 🎬

Cinema App is a back-end web application built using Spring and Hibernate frameworks. It allows users to send HTTP requests (GET, PUT, POST, DELETE) and work with JSON objects. The app was implemented following SOLID and OOP principles. It was developed using the CRUD (Create, Read, Update, Delete) methodology, providing a comprehensive solution for managing data within the application. The Cinema App has strong user authentication and authorization features to control access and ensure security.

## Project Structure 📁

Cinema App follows a standard project structure for Spring-based applications. Here is a brief overview of the structure:

- `java`: This directory contains all the Java code of the application.

  - `config`:  Configuration classes for Spring and Hibernate.

  - `controller`: Controller classes that handle the incoming requests.

  - `dao`: Classes that provide access to the database.

  - `dto`: Data transfer objects used in the application.

  - `exception`: Custom exception classes used in the application.

  - `lib`: Custom annotations used for validating input data.

  - `model`: Entity classes used in the application.

  - `service`: Service classes that provide business logic to the application.

  - `util`: Utility classes used in the application.

- `resources`: This directory contains the `db.properties` file, which has the database configuration.

## Technologies 💻
Cinema App was built using the following technologies and patterns:

- Java 17, MySql, Tomcat, Maven
- Spring Web MVC, Spring Security, Hibernate
- OOP, SOLID, Singleton

## Requirements 🛠️

To run and work with this app, you will need the following tools:

- IDE
- Tomcat v9.5
- MySql
- Postman

## Installation 🚀

Here are the steps to run this app locally:

1. Install JDK.
2. Fork this app to your repository and open it locally.
3. Add all the required configurations to db.properties file.
4. Install Tomcat.
5. Run the app.
6. You can use the email "admin@i.ua" and password "admin123" for authentication.
7. Check which links and methods are available in SecurityConfig class.
8. Enjoy! 🎉

## Contributing 🤝

If you'd like to contribute to this project, feel free to submit a pull request.
