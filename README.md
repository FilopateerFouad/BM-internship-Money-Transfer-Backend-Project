#Money Transfer Application

This is a Money Transfer application developed using Java Spring Boot. The application handles user registration, login, logout, and JWT authentication. Each customer can create an account, manage their account details, transfer money between accounts, and view transaction history.

##Features

1.User Registration

2.Login with Email and Password

3.Logout (Destroy JWT Token)

4.Create Account (One Account per Customer)

5.Get Customer by ID

6.Get Account by Account Number

7.Session Management (Token Valid for 5 Minutes)

8.Transfer Money Between Accounts

9.Update Account Info

10.Change Password (Old and New Password)

11.Add Account to Favourites

12.View Transaction History (Sorted by Date)

##Requirements

.Java 11 or higher

.Maven 3.6.0 or higher

.Postgres or any other relational database

##Setup
#####Clone the repository:
git clone https://github.com/FilopateerFouad/BM-internship-Money-Transfer-Backend-Project
cd money-transfer-app

#####configure the database:
properties
'spring.datasource.url=jdbc:mysql://localhost:3306/money_transfer_db'
'spring.datasource.username=your_db_username'
'spring.datasource.password=your_db_password'
'spring.jpa.hibernate.ddl-auto=update'

#####Install dependencies and build the project:
'mvn clean install'

#####Run the application:
'mvn spring-boot:run'

#####Access Swagger UI for API Documentation:
Open your browser and navigate to http://localhost:8080/swagger-ui.html


