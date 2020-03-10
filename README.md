# spring-boot-postgres-flyway

[![keep growing logo](readme-images/logo_250x60.png)](https://keepgrowing.in)

spring-boot-postgres-flyway is a scaffolding for a web application.
It can be built into a single jar file using Maven.

If you want to build a project like this check out the following articles:
* [Set up a PostgreSQL database with Docker](https://keepgrowing.in/tools/set-up-a-postgresql-database-with-docker/)
* [Add a PostgreSQL database to your Spring Boot project](https://keepgrowing.in/java/springboot/add-a-postgresql-database-to-your-spring-boot-project/)

## Overview and technical features

* One endpoint enabling saving baked goods data.
* PostgreSQL database run from a Docker container.
* Hibernate DDL schema is saved in a file.
* Database schema is created automatically on the application startup.

## Getting Started

To clone this repository, execute the following in the command line:
```bash
$ git clone https://github.com/little-pinecone/spring-boot-postgres-flyway.git
```

You can build the application with:
```bash
$ mvn clean install
```

You can run tests for the application with:
```bash
$ mvn test
```

You can send a request from Postman

![add-cookie-postman-screenshot](readme-images/add-cookie-postman-screenshot.png)

## Built With

* [Spring Boot 2.2.5](https://start.spring.io/)
* [Maven](https://maven.apache.org/)
* [PostgreSQL docker image](https://hub.docker.com/_/postgres)

## License

This project is licensed under the MIT License - see the [license details](https://opensource.org/licenses/MIT).
