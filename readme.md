# MovieApi

This project is a backend REST API developed using Java Spring Boot and Maven with CORS configuration. It provides endpoints for interacting with a MongoDB database, allowing users to perform CRUD operations on resources. The API follows RESTful principles and is designed to be scalable and efficient. It serves as a foundation for building web applications that require a robust and reliable backend infrastructure.

## Technologies Used

- Java
- Spring Boot
- Maven
- MongoDB

## Prerequisites

- Java 8 or higher
- Maven
- MongoDB

## Getting Started

1. **Clone the repository:**

   ```bash
   git clone https://github.com/kushalv238/MovieApi.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd MovieApi
   ```

3. **Build the project using Maven:**

   ```bash
   mvn clean install
   ```

4. **Run the application:**

   ```bash
   java -jar target/MovieApi-0.0.1-SNAPSHOT.jar
   ```

5. **Access the application:**

   The application should now be running and accessible at `http://localhost:8080`.

## API Endpoints

1. **`GET /api/v1/movies`**
   - Get all the movies information.

1. **`GET /api/v1/movies/{imdbId}`**
   - Get a particular movie using it's IMDBb id.

3. **`POST /api/v1/reviews/{imdbId}`**
   - Add a review with rating to a movie using it's IMDb id.

## Database Configuration

Create an mongoDB project and collection and add the mongoURI to env

## Author

[Kushal Vadodaria](https://github.com/kushalv238)