# OpenCart Hybrid Framework

This repository contains an **OpenCart** project designed using a **Hybrid Framework** for automation testing. It integrates the best features of both **Data-Driven** and **Keyword-Driven** approaches, combined with **Page Object Model (POM)** to structure the tests efficiently.

## Key Features:
- **Hybrid Automation Framework**: The framework is a combination of data-driven and keyword-driven approaches, allowing flexibility in test automation.
- **Page Object Model (POM)**: Separation of test logic from the UI interactions, improving maintainability and scalability.
- **TestNG**: Integrated with TestNG for managing test execution, annotations, and generating test reports.
- **Grid Support**: Supports execution on Selenium Grid, with configurations provided for running tests in parallel across different browsers and platforms.
- **Cross-browser Testing**: The framework is designed to run on different browsers, such as Chrome, Firefox, and Edge.
- **Logging and Reporting**: Uses Extent Reports to generate detailed and interactive reports, and Log4j for logging.
- **Docker Support**: Docker is integrated for executing tests in isolated environments, with configurations available for running tests on Selenium Grid in Docker containers.
- **Parallel Testing**: Supports parallel test execution through TestNG, enhancing efficiency by reducing test execution time.

## Project Structure:
OpenCart_HybridFramework

├── src/test/              : Contains test scripts and test data

├── testData/              : Excel or CSV files for data-driven tests

├── test-output/           : TestNG output

├── reports/               : Test reports generated by ExtentReports

├── pom.xml                : Maven POM file for managing dependencies

├── Grid Docker.xml        : Selenium Grid Docker configuration

├── Master.xml             : TestNG master configuration file

├── ParallelTesting.xml    : TestNG configuration for parallel execution

├── GroupTesting.xml       : TestNG configuration for grouping execution

├── docker-compose.yml     : Docker Compose configuration for running Selenium Grid


## Prerequisites:
* Java 8+: The project is built using Java, so ensure you have Java installed.
* Maven: Maven is used for dependency management.
* TestNG: Testing framework integrated within the project.
* Selenium: WebDriver-based testing framework.
* Extent Reports: For generating test reports.
* Log4j: For logging application and test activities.
* Docker: To run tests on Docker containers, ensure Docker is installed if you plan to use Grid and Docker support.

## How to Use:
**Clone the repository**: git clone https://github.com/the-himanshu69/OpenCart_HybridFramework.git

**Navigate to the project directory**: cd OpenCart_HybridFramework

**Run tests using Maven**: mvn clean test

**Run tests using TestNG**: Import the project into your IDE and run tests using the TestNG configuration files such as Master.xml or ParallelTesting.xml.

**Run tests on Selenium Grid** : To run tests in parallel using Docker and Selenium Grid, use the docker-compose.yml and Grid Docker.xml configurations.

## Reports:
After test execution, the reports will be available under the reports/ directory.
