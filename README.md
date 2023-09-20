# Eureka-server

## Microservices(AT)

### Table of Contents

#### 1. Introduction
    - 1.1 Purpose
    - 1.2 Technologies Used

#### 2. Business Scenario
    - 2.1 Problem Statement
    - 2.2 Objectives

#### 3. System Architecture
    - 3.1 High-Level Overview
    - 3.2 Components
    - 3.3 Data Flow

#### 4. Implementation Steps
    - 5.1 Setting up Oracle Server
    - 5.2 Creating a Microservices using Spring Boot
    - 5.3 Configuring JPA
    - 5.4 Implementing Student Microservice, Course Microservice and eureka discovery server

##### 1. Introduction

###### 1.1 Purpose

The purpose of this case study is to demonstrate the creation of Microservices, establish communication between them and discover them using Eureka Server. Entire application needs to be put into docker container.

###### 1.2 Technologies Used

- Java 8+
- Spring Boot 2.7.12
- Maven or Gradle for dependency management
- IDE of choice (e.g., IntelliJ, Eclipse)

##### 2. Business Scenario

###### 2.1 Problem Statement

The assignment is based on a Creating two microservices and establish communication between them using Feign Client , discover them using Eureka server and put all the services in docker container.

##### 3. System Architecture

###### 3.1 High-Level Overview

The system will follow a typical three-tier architecture:

1. Presentation Layer: Handles incoming HTTP requests and returns responses to clients.
2. Business Logic Layer: Contains application logic and coordinates data access.
3. Data Access Layer (Repository): Manages interaction with the Oracle database.

###### 3.2 Components

The major components of the system include:

- Controller Layer:  Exposes Webservice endpoints for user data management.
- Service Layer:  Implements business logic and interacts with the Data Access Layer.
- Data Access Layer:  Communicates with the Oracle database.

###### 3.3 Data Flow

The data flow within the system is as follows:

1. Clients send HTTP requests to the API endpoints.
2. The Controller Layer receives the requests and validates the inputs.
3. The Service Layer processes the requests, performs business logic, and communicates with the Repository Layer for data retrieval or storage.
4. The JPA Repository Layer interacts with the Oracle database to store or retrieve data.
5. Responses are sent back through the Controller Layer to the clients.

##### 4. Features

The web application will offer the following features:

###### 4.1 CRUD Operations

- Implement Create, Read, Update, and Delete operations using Spring Boot and Oracle.

##### 5. Implementation Steps – To be filled and submitted by the learner

###### 5.1 Setting up Oracle Server

- [x] Create a spring boot project using https://start.spring.io/ for student service,course service and eureka server.
- [x] Go to server in the debug window in the bottom of the eclipse

###### 5.2 Configuring JAVA and Oracle Integration

<<Instructions on adding the required dependencies and configuration to JAVA with Oracle.>>


