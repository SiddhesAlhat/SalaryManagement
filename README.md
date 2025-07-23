# Salary Management Application

A web-based application built with Spring Boot to manage employee records, including CRUD operations for employee data (ID, Name, Designation, Salary). The app uses Spring Data JPA for database interactions, MySQL for storage, Thymeleaf for server-side rendering, and Bootstrap for a responsive UI.

## Features
- **Add Employee**: Submit a form to add a new employee.
- **View Employees**: Display all employees in a table.
- **Update Employee**: Edit existing employee details.
- **Delete Employee**: Remove an employee from the database.
- **Responsive Design**: Built with Bootstrap for a modern, user-friendly interface.

## Tech Stack
- **Backend**: Spring Boot 3.4.0, Spring Data JPA, Java 17
- **Database**: MySQL
- **Frontend**: Thymeleaf, Bootstrap 5.3.3
- **Build Tool**: Maven

## Project Structure

com.one.project/
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── com.one.project/
│   │   │   │   ├── DAO/
│   │   │   │   │   └── EmployeeRepo.java
│   │   │   │   ├── Employee/
│   │   │   │   │   └── Employee.java
│   │   │   │   ├── MyController/
│   │   │   │   │   └── MyController.java
│   │   │   │   └── SalaryManagementApplication.java
│   │   ├── resources/
│   │   │   ├── static/
│   │   │   │   └── salary_6847787.png (logo)
│   │   │   ├── templates/
│   │   │   │   ├── employee.html
│   │   │   │   └── update.html
│   │   │   └── application.properties.template
├── pom.xml
└── README.md


## Prerequisites
- Java 17
- Maven
- MySQL (with a database named `salary`)
- IDE (e.g., IntelliJ IDEA, Eclipse)

## Setup Instructions
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/Salary-Management-App.git
   cd Salary-Management-App
Configure Database:Create a MySQL database named salary.
Copy application.properties.template to application.properties and update with your MySQL 

credentials:properties

spring.datasource.username=[YOUR_USERNAME]
spring.datasource.password=[YOUR_PASSWORD]

Access the Application:
Open a browser and navigate to http://localhost:8080/index.



