# Overview
This will provide a sample implementation of a full stack application written using `ReactJS` and `Spring Boot`. The intention of the project is to maintain the front end and back end implementations separately while build them together to produce a single `jar` or `war` file which consists of the full stack application.

Refer following repositories. [Front end](https://github.com/ugbandula/fullstack-build-frontend.git) and [Back end](https://github.com/ugbandula/fullstack-build-backend.git).

# Getting Started

## Requirements

* _Maven 3_ and _Java 1.8_
* For _Maven 2_ support take a look at the [wiki](https://github.com/eirslett/frontend-maven-plugin/wiki#maven-2).

## Building the Application
Use `mvn package` to build the application. This will compile the back end, front end and then generates the final archive after copying front end details to the back end project.

## Running the Application
The generated war/jar file can be deployed into an application server or run independently.
### Run independently
 - Command: `java -jar fullstack-test-backend-0.0.1.jar` 
 - Runs with embedded Tomcat server
 	
### Run inside an Application Server
 - Follow the standard deployment process relevant to the application server.
 	
 
## Reference Documentation
For further reference, please consider the following sections:

* [Official Apache Maven documentation](https://maven.apache.org/guides/index.html)
* [Spring Web Starter](https://docs.spring.io/spring-boot/docs/{bootVersion}/reference/htmlsingle/#boot-features-developing-web-applications)
* [frontend-maven-plugin](https://github.com/eirslett/frontend-maven-plugin)

## Guides
The following guides illustrate how to use some features concretely:

* [Building a RESTful Web Service](https://spring.io/guides/gs/rest-service/)
* [Serving Web Content with Spring MVC](https://spring.io/guides/gs/serving-web-content/)
* [Building REST services with Spring](https://spring.io/guides/tutorials/bookmarks/)

