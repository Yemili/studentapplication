
# School Management System 
## Technologies: Java, Springboot, Thymeleaf, Mysql, Docker, Git
## Dependencies  
### For Spring boot dependencies
- spring-boot-starter-data-jpa: which is used for managing and accessing data between java objects and database.
- spring-boot-starter-web: It allows to create web controllers, Handel requests and return responses.
- spring-boot-starter-test: Testing libraries help to write unit test, integration tests and end-to-end tests for spring boot applications.
- spring-boot-starter-jdbc: It provides necessary libraries and configurations to use jdbc in springboot application make it easy to connect database and execute sql queries.

## For Database dependencies
- mysql-connector-java: connecting springboot application to the MySQL database.

## For Thymeleaf dependencies
- spring-boot-starter-thymeleaf: for integrating thymeleaf template into springboot application for rendering views in web browser.


## Functionalities
- Login
  - Session Management: WIP 
- View Profile
- View Academic Details
- Edit Profile

## Docker
- Install the docker
- Create docker file
- Build docker image:docker build -t your-app-name
- Run docker container:docker run -p 8080:8080 your-app-name
## GitPackages
-Instead of pushing docker inmages in git,we can push it in gitpackages.
## GitHub Actions
-The project includes a GitHub Actions workflow for CI/CD automation: 
-Builds the application
-Runs tests
-Deploys the Docker image 
  -Workflow File: .github/workflows/ci-cd.yml
##How to Contribute
-Fork the repository
-Create a feature branch
-Commit your changes
-Open a pull request
