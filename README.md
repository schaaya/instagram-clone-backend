# Instagram Clone Backend Project

This is a backend project for an Instagram clone developed using Spring Boot. The project provides RESTful APIs to handle various functionalities such as managing users, posts, comments, and status updates. It utilizes Maven for dependency management, MySQL for database storage, and Firebase for additional functionalities.

## Features

- **User Management:** Allows registration, authentication, and profile management for users.
- **Post Management:** Enables users to create, read, update, and delete posts.
- **Comment Management:** Supports commenting on posts.
- **Status Management:** Facilitates updating and viewing user status.
- **Integration with Firebase:** Utilizes Firebase for additional functionalities such as notifications, storage, etc.

## Technologies Used

- **Spring Boot:** Framework for creating Java-based applications.
- **Maven:** Dependency management tool.
- **MySQL:** Relational database management system.
- **Firebase:** Provides additional functionalities for the application.
- **Other dependencies:** Include Spring Security for authentication and authorization, Spring Data JPA for database operations, etc.

## Setup

1. **Clone the repository**:
    ```
    git clone <repository_url>
    ```
2. **Configure MySQL**:
    - Install MySQL if not already installed.
    - Create a database for the application.
    - Update the database configuration in `application.properties` file.
3. **Setup Firebase**:
    - Create a Firebase project if not already created.
    - Configure Firebase SDK in the project according to the application requirements.
4. **Build and Run**:
    ```
    mvn clean install
    mvn spring-boot:run
    ```

## Usage

- Once the application is running, you can use tools like Postman or any REST client to interact with the APIs.
- Explore the available endpoints for user management, post management, comment management, and status management.


Project Screenshot
![Screenshot](https://user-images.githubusercontent.com/68023949/107745731-c07ed380-6d3a-11eb-88a6-9c0fc4413763.png)
