# movies-reviews-api

This directory contains the spring boot backend API for the project.

## Prerequisites

Before running this project locally, ensure that you have the following prerequisites installed:

1. **Java Development Kit (JDK)**: JDK is required to compile and run Java applications. Ensure that you have JDK installed on your system.

2. **Apache Maven**: Apache Maven is a build automation tool used for managing dependencies and building Java projects. Install Maven to build and run the backend API.

3. **MongoDB**: MongoDB is a popular NoSQL database used by the backend API. Install and configure MongoDB on your system or use a remote MongoDB service.

## How to Run This Project Locally

To run this project locally, follow these steps:

1. **Navigate to the project directory**:
### `cd movies-reviews-api`

2. **Build the project**:
### `mvn clean install`

3. **Run the application**:
### `mvn spring-boot:run`

This will start the API server on the default port `8080`.

**Note**: Make sure your MongoDB instance is running and the connection details are properly configured in the project.

## Configuring MongoDB Credentials
To connect the backend API to your own MongoDB database, follow these steps:

1. **Create a MongoDB database**: Set up a MongoDB database either locally or using a cloud-based service. Make sure you have the necessary credentials, including the MongoDB connection URL.

2. **Copy `.env.example` file**: In the `movies-reviews-api` directory, navigate to the following path: `movies-reviews-api\src\main\resources` and locate the `.env.example` file and make a copy of it. Rename the copy as `.env`. 

3. **Edit `.env` file**: Open the `.env` file in a text editor and update the details.

**Note**: Make sure not to commit this file to version control as it may contain sensitive information.
