Role-Based Authentication System

This project implements a Role-Based Authentication (RBAC) system where users are assigned specific roles, and access to resources is restricted based on the role assigned to the user. It allows for secure management of user permissions and access control.

Features

User Registration & Login: Users can sign up, log in, and maintain sessions.
RBAC Implementation: Roles such as Admin, Manager, and User are defined, each with different access permissions.
Middleware for Access Control: Routes are protected, ensuring users can only access resources they are permitted to.

Technologies Used

Java
Spring Boot
Spring Security
JPA/Hibernate (for database interaction)
MySQL/PostgreSQL (or any preferred RDBMS)
Thymeleaf (for web interface)

Clone the Repository:

Navigate to the project directory
cd RoleBasedAuthentication

Setup Database:
Create a database in your preferred RDBMS (MySQL, PostgreSQL, etc.).
Configure the database connection in application.properties (found in src/main/resources).

Build the Project(Maven)
mvn clean install


Run the Application:
mvn spring-boot:run





Testing RBAC

Admin Role: Full access to all the features, can manage users, and assign roles.
Manager Role: Limited access to manage specific resources.
User Role: Basic access to resources, unable to modify sensitive data.
Access Control Test:
Log in as an Admin to access and manage all routes.
Log in as a Manager to see restricted resources.
Log in as a User to access only user-specific data.
"# VRV_Assignment" 
