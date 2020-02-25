# Getting Started
# Spring Boot - Cloud Config Server
### This project developed using Spring Cloud Config Server. 
* This config server holds information about all **distributed configuration** across multiple applications.
* Every Micro service(movie-catalog, movie-info, movie-rating, discovery-server) configurations will be stored under **Git** version control
* The server is embeddable in a Spring Boot application, by using the **@EnableConfigServer** annotation. 
* the **config server** default **port** changed to **8085**

# Prerequisite  
Please follow the details before you start downloading the project.  
### Readme:  
[https://github.com/rajs24/sbt-ms-movie-catalog/blob/master/README.md](https://github.com/rajs24/sbt-ms-movie-catalog/blob/master/README.md)


# Download Spring Boot Discovery Server Project
Clone the **spring cloud config server** project  
Git Clone: [https://github.com/rajs24/sbt-cloud-config-service.git](https://github.com/rajs24/sbt-cloud-config-service.git)  

# Start the Server
Start the **spring cloud config server** project

# Endpoint Details
Microservice specific yml and properties files in the git repository
```
http://localhost:8085/movie-catalog-service/default
http://localhost:8085/movie-rating-service/default
http://localhost:8085/movie-info-service/default
http://localhost:8085/discovery-server/default
```


