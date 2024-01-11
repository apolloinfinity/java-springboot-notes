# Notes on Java Spring Boot and Maven

## What is Spring Boot?
Springbook is an open-source Java-based framework used to create standalone production grade Spring based applications. It is widely used to build enterprise-level applications. 

## **Core Features of Springboot**
1. **Autoconfiguration:**
	- Springboot will automatically configure your application based on its dependencies. 
2. **Standalone:**
	- Spring Boot applications don't require an external server to run. They include an embedded server like Tomcat, Jetty, or Undertow, making it easy to deploy and test web applications. 
3. **Opionated Defaults:**
	- Spring Boot provides a set of default configurations to quick start new applications. You can run the application with default settings or customize them as needed. 
4. **Spring Ecosystem Integration:**
	- Spring Boot is designed to work within the Spring ecosystem. It can easily integrate with other Spring frameworks such as Spring Data, Spring Security, etc., providing a cohesive experience for developers. 
5. **Microservices Ready:**
	- Because of Spring Boot's fast startup, embedded server, and easy configuration, it is well suited for building microservices. 
6. **Minimal Configuration:** 
	- The framework reduces the need for specifying boilerplate configuration by leveraging Spring's dependancy injection and autoconfiguration.
7. **Easy Dependancy Management:**
	- To simplify the Maven and Gradle build files, Spring Boot manages dependencies and their compatible versions via its starter POMs.
8. **Actuator:**
	- Spring Boot Actuator provides production-ready features like monitoring and managing your application when it's pushed into production. 
9. **Developer Tools:**
	- Spring Boot has built-in tools like automatic restarts, live reload, and quick diagnostics, enhancing the developer experience and productivity. 

## Use Cases for Spring Boot
- **Creating RESTful Web Services:** Easily create RESTful services with minimal configuration. 
- **Microservices:** Ideal for building and deploying microservices.
- **Rapid Application Development:** Speeds up development process for enterprise applications. 
- **Cloud-native Applications:** Suitable for developing cloud-native applications which are scalable and robust. 



### What is Maven?
Maven is a build automation tool use primarly for Java projects and it allows developers to build and document the lifecycle framework. It is developed by the Apache Group.
### Core Features of Maven
1. Project Build automation
2. Dependancy Management
3. Project Object Model(expand more on this)
4. Standardized Project Structure
5. Plugins and lifecycle
6. Repository Management

### Uses of Maven
- Enterprise Java Development.
- Continous Integration/Continous Deployment.
- Multi-module Projects. 

### Common Maven Commands