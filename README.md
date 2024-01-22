# How to Develop a Spring Boot Java Application

This guide provides step-by-step instructions for setting up a Spring Boot Java application development environment.

## Prerequisites
Before starting the development, ensure that the following tools are installed:

1. **Java Development Kit (JDK):**
   - Download and install JDK from [Oracle](https://www.oracle.com/java/technologies/downloads/#jdk21-windows) or [OpenJDK](https://www.tutorialspoint.com/springbootcli/springbootcli_environment.htm) (all versions).
   - Set the `JAVA_HOME` environment variable to the JDK installation directory.

2. **Spring Boot CLI:**
   - Follow the manual installation guide [here](https://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#getting-started.installing.cli.manual-installation).
   - Alternatively, refer to [INSTALL.txt](https://raw.githubusercontent.com/spring-projects/spring-boot/v3.2.2/spring-boot-project/spring-boot-tools/spring-boot-cli/src/main/content/INSTALL.txt) for detailed instructions.

3. **Maven:**
   - Download Maven from [here](https://maven.apache.org/download.cgi) and follow the installation instructions.
   - Add the Maven `bin` directory to your system's `PATH` variable.

4. **Gradle:**
   - Download Gradle from [here](https://docs.gradle.org/current/userguide/installation.html) and follow the installation instructions.
   - Add the Gradle `bin` directory to your system's `PATH` variable.

## Verify Installations
After installation, verify the installations by running the following commands in the terminal:

```bash
java --version
spring --version
spring init --list
mvn --version
gradle -v
```

## Getting Started with Spring Boot

### 1. Start a Project
- Follow the [official Spring Boot quickstart guide](https://spring.io/quickstart/) to create a sample Spring Boot application.

### 2. Additional Resources
- For a step-by-step guide, refer to [this YouTube video](https://www.youtube.com/watch?v=rsr6X5M6-6M).

## Visual Studio Code Setup
Install the following extensions in VS Code:

- **Extension Pack for Java**
- **Lombok**

## Package Management
Use Maven for package management:

- Clean and install dependencies: `mvn clean install`
- Install new dependencies: `mvn install`

## Run the Spring Application
Run the Spring Boot application using Maven:

```bash
mvn spring-boot:run
```

## Access the Application
View the application in your browser:

- [http://localhost:8080/hello](http://localhost:8080/hello)
- [http://localhost:8080/hello?name=Spring](http://localhost:8080/hello?name=Spring)

Happy coding!