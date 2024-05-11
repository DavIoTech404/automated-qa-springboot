# Automated QA SpringBoot

## Overview

This repository contains the Spring Boot application with a comprehensive automated testing setup using GitHub Actions. It includes unit tests, integration tests, and end-to-end tests to ensure the application's reliability and robustness.

## Technologies

- Spring Boot
- GitHub Actions
- JUnit and Mockito for unit testing
- SpringBootTest for integration testing
- Checkstyle and SpotBugs for linting

## Getting Started

### Prerequisites

- Java JDK 11 or newer
- Gradle
- An IDE of your choice (e.g., IntelliJ IDEA, Eclipse)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/DavIoTech404/automated-qa-springboot.git
   cd automated-qa-springboot

2. Build the project:
   ```bash
   gradle build

3. Running the Application:
   ```bash
   java -jar target/automated-qa-springboot-1.0.0.jar

4. Running Tests:
   ```bash
   gradle test
