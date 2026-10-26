# MUN Delegation Management System

## Project Description

The MUN Delegation Management System is a web-based application developed using Java and Spring Boot. It helps manage delegates and countries participating in a Model United Nations (MUN) event.

## Features

* Add, view, edit, and delete delegate records.
* Manage country information.
* User-friendly web interface.
* Store and manage data using an H2 database.
* Perform CRUD operations efficiently.

## Technologies Used

* Java
* Spring Boot
* Spring MVC
* Thymeleaf
* HTML and CSS
* H2 Database
* Maven
* Visual Studio Code

## Application Architecture

The application follows a layered architecture:

1. **Controller:** Handles incoming web requests.
2. **Service:** Contains application logic.
3. **Repository:** Manages database operations.
4. **Model:** Represents application data.
5. **Thymeleaf Templates:** Display the web interface.

## How to Run the Project

### Prerequisites

* Java Development Kit (JDK)
* Visual Studio Code
* Maven (or the included Maven Wrapper)

### Steps

1. Clone or download this repository.
2. Open the project folder in Visual Studio Code.
3. Run the application using the Maven Wrapper.

On Windows, open the terminal in the project directory and execute:

```bash
.\mvnw.cmd spring-boot:run
```

4. Open the local URL displayed in the terminal in your web browser.

## Database

The application uses an H2 database for storing application data. Database configuration and initialization are managed through the project configuration and SQL scripts.

## Project Purpose

This project demonstrates the development of a Java-based web application using Spring Boot, database integration, and CRUD operations.
