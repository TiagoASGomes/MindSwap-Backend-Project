# MindSwap-Backend-Project
Group project for backend during mindswap bootcamp

## Project Description
This project is a backend for a travel agency. It is a RESTful API that allows users to book flights and hotels. It also allows users to view their booking history and cancel bookings.

## Technologies Used
- Java
- Spring Boot
- Quarkus
- PostgreSQL
- MongoDB
- MySQL
- Maven

## Running the Application
To run the application, simply run the following commands:

    1. Clone the repository with:
        git clone --recurse-submodules https://github.com/TiagoASGomes/MindSwap-Backend-Project.git
    2. In the root folder:
        run docker-compose up

This will start all the services required for the application to run.
The application will be running on `localhost:8080`.
The flight service will be running on `localhost:8081`.
The hotel service will be running on `localhost:9000`.

## Endpoints
### Travel Agency
For a full list of endpoints, please run the program and refer to the [API Documentation](localhost:8080/swagger-ui/index.html#/).

### Flight Service
For a full list of endpoints, please run the program and refer to the [API Documentation](localhost:8081/swagger-ui/index.html#/).

### Hotel Service
For a full list of endpoints, please run the program and refer to the [API Documentation](localhost:8082/swagger-ui/index.html#/).