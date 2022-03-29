## Welcome to Taxi Service
***
### Description
This is a simple WEB application that supports register, login, logout users and other CRUD operations.
The application is built with SOLID principles and have 3-layer architecture.

### 3-layer architecture
- DAO - data access layer
- Service - logic layer
- Controller - presentation layer
### Functional
- register, login and logout drivers
- display all drivers, with the possibility to delete
- display all cars, with the possibility to delete
- display cars by the driver, who is authenticated
- display all manufacturers
- create a new car
- create a new manufacturer
- add a driver to a car
### Technologies used
- Java 11
- Maven
- Apache Tomcat
- MySQL
- Javax Servlet/JSP API
### How to start
1. It's supposed you have Ultimate IntelliJ IDEA
2. Download and configure TomСat webserver version 9
3. Download and install MySQL
4. Create Schema and tables using ```resources/init_db.sql```
5. Update fields ```URL```, ```USERNAME``` and ```PASSWORD``` in ```java/taxi/util/ConnectionUtil.java```
6. Replace ```logs/app.log``` path with absolute path to ```app.log``` file in the ```src/main/resources/log4j2.xml```
7. Configure the TomCat library path in the startup settings
8. Enjoy it
### Author's social networks
[Telegram](https://t.me/Kinn90) / [LinkedIn](https://www.linkedin.com/in/sasha-bachynskyi-242a27141/)