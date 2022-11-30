# MiniShoppingApp

- It is a REST API application of a Mini Online Shopping Website where the basic crud operations can be performed 
- Developed as an invidual mini project in 2 weeks.

## Tech Stack
<img align="left" src="https://1000logos.net/wp-content/uploads/2020/09/Java-Logo.png" alt="drawing" width="100"/>
<img align="left"  src="https://download.logo.wine/logo/Spring_Framework/Spring_Framework-Logo.wine.png" alt="drawing" width="100"/>
<img src="https://download.logo.wine/logo/MySQL/MySQL-Logo.wine.png" alt="drawing" width="100"/>
<img align = "left" src="https://www.dariawan.com/media/images/tech-spring-boot.width-1024.png" alt="drawing" width="100"/>
<img align="left"  src="https://upload.wikimedia.org/wikipedia/commons/2/22/Hibernate_logo_a.png" alt="drawing" width="100"/>
<img  align="left" src="https://miro.medium.com/max/818/1*zc-LgogGtr7fFHF9e1M8wA.png" alt="drawing" width="100"/>
<img src="https://maven.apache.org/images/maven-logo-white-on-black.purevec.svg" alt="drawing" width="100"/>
<img src="https://zooz.github.io/predator/images/restapi.png" alt="drawing" width="100"/>

## Modules
- User can register/login
- View products
- Find products by category
- Add to cart
- Edit the cart
- Place Order

### User Features:
* Registering themselves with application, and logging in to get the valid session token
* Viewing list of products, by category, by name etc...
* Only logged in user can access his orders, profile updation and other features.

## Installation & Run
 - Before running the API server, you should update the database config inside the application.properties file.
 - Update the port number, username and password as per your local database configuration.
 - For current application we have used the below properties.
```
    server.port=8882

    spring.datasource.url=jdbc:mysql://localhost:3306/minionlineapp;
    spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
    spring.datasource.username=root
    spring.datasource.password=arun@mysql
```
