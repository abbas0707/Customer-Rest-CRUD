# Customer-Rest-CRUD
Microservice CRUD example using Rest
The application is related to a Customer data and exposes it 4 operation i,e CREATE, UPDATE, DELETE, ListCustomers
Only one operation /listCustomers is exposes via Rest achitecture using springboot implementations.
Future release will have rest of the operations as well

Instructions to the application

Pre requisite

1- Java 8

2- Maven version greater than 3, envionment variable must be configure for maven

Running the application

1- Download the source code

2- open command line and cd to the home directory Customer-Rest-CRUD

3- Run "mvn install" on command line

4- After successfull resutls from mvn install run below command to deploy the application on build tomcate

mvn spring-boot:run

5- The rest API deployed on default port of springboot 8080, it can be accessed as 

http://localhost:8080/listCustomers

6- /listCustomer getting the data from JSON file under Resources/data folder, There is only one default record is there,


