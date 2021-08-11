# Next Level Technologies Application

* The application is able to easily import hard-formatted data from json and
  xml files and support functionality for exporting the imported data. 
  The exported data will be displayed using Rest service and visualized in the browser. 

## Requirements

* Java JDK 11 or later version
* Maven 3.8.1 or later version
* IntelliJ IDEA or Eclipse
* MySQL Server 8.0 or later version
* MySQL Workbench 8.0 or later version

## Tech

The application uses the following dependencies:

* Spring Boot
* MySql database
* Spring Boot Web
* Spring Data JPA
* Thymeleaf
* Model Mapper
* JAXB
* GSON

## How to run

* Clone the code on your local machine
* Open MySQL Workbench and connect to `localhost:3306` with username: root, password: 12345678
* Open `DemoWebApplication` in your IDE(IntelliJ IDEA or Eclipse)
* Run the application


## End points

*	Home page before logging in importing anything (route "/"):
*	Register page (route "/users/register"):
*	Login page (route "/users/login"):
*	Home page after login (route "/home"):
*	Import XML page before importing anything (route = "/import"):
*	Import Companies first (route = "/import/companies"):
*	Import Projects second (route = "/import/projects"):
*	Import Employees last (route = "/import/employees"):
*	Import XML page after importing the given data (route = "/import"):
*	Home page after successful imports (route ="/home"):
*	Export Finished projects (route = "/export/projects-if-finished"):
*	Export Employees with age above 25 (route = "/export/employees-above-25"):
