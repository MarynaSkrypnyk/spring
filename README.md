# Spring Boot(Rest-API)



### Overview

This Java-based web application provides a RESTful API with a focus on security and performance. This provides user authentication and authorization using JWT tokens, user verification using activation codes, access control based on user roles, and relational databases for persistent data storage. The application is designed with a simple architecture that separates tasks into repository, service and controller levels, configuration files and utilities.


### Features

- user authentication and authorization using JWT (JSON web tokens);
- user verification using an activation code, which the user receives by email upon registration;
- receiving data from open api;
- CRUD operations for user data, menus, orders;
- secure REST API endpoints;
- data caching;
- strict data validation;

Project structure:
- repository: data access layer for interacting with the database.
- service: Contains business logic and data processing.
- util: utility classes and general functions.
- controller: REST controllers for processing API requests.
- API endpoints
- configuration: configuration files:
- entities: definition of entities:
- security: responsible for authorization and auto-identification;
- model: defining the data that comes from the endpoint
- resources: dbchangelog - master.xml for word with db

## Prerequisites

- JDK 17 or later
- Maven
- a relational database (e.g., MySQL, PostgreSQL)
- Setup

Clone the repository to your local machine.
Configure the database connection in src/main/resources/application.properties.
Run the database migration scripts located in src/main/resources/db/migration to set up your database schema.
Build the project using Maven: mvn clean install.
Run the application: java -jar target/your-application.jar. (+ openweather map api key and security related things (token secret and duration))
Usage

After starting the application, you can interact with the API using tools like Postman or Curl



## ## Parameters and Body Details


<img width="1271" alt="Снимок экрана 2024-04-02 в 13 16 25" src="https://github.com/MarynaSkrypnyk/Spring-boot-project-Rest-API-/assets/148319011/a1a8a4a8-673e-4f49-977f-6ec9536a6a37">

<img width="1257" alt="Снимок экрана 2024-04-02 в 13 22 50" src="https://github.com/MarynaSkrypnyk/Spring-boot-project-Rest-API-/assets/148319011/ed6e420d-78f6-4e36-9543-c8d3be69b623">

<img width="1257" alt="Снимок экрана 2024-04-02 в 13 23 45" src="https://github.com/MarynaSkrypnyk/Spring-boot-project-Rest-API-/assets/148319011/204c812e-0c99-460e-8067-ff46814b8416">

<img width="1257" alt="Снимок экрана 2024-04-02 в 13 22 03" src="https://github.com/MarynaSkrypnyk/Spring-boot-project-Rest-API-/assets/148319011/12a742a3-3739-4b6f-92d1-2bb04f5fcde4">

<img width="1257" alt="Снимок экрана 2024-04-02 в 13 23 20" src="https://github.com/MarynaSkrypnyk/Spring-boot-project-Rest-API-/assets/148319011/e2ba40f5-b481-41bd-9229-7fa4f323f889">

<img width="1257" alt="Снимок экрана 2024-04-02 в 13 23 05" src="https://github.com/MarynaSkrypnyk/Spring-boot-project-Rest-API-/assets/148319011/aede6f35-6967-4636-8d6c-93d512fb4231">

