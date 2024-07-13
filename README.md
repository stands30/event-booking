## README

### Event Booking Service

**Overview**

This Go application provides a basic event booking service.

**Dependencies**

* `github.com/gin-gonic/gin`
* `example.com/event-booking/db`
* `example.com/event-booking/routes`

**Installation**

1. Ensure you have Go installed.
2. Clone this repository.
3. Install dependencies using `go mod tidy`.

**Usage**

1. Run the application using `go run main.go`.
2. The application will start a web server on port 8080.

**Structure**

* `main.go`: The main entry point of the application.
  * Initializes the database connection (`db.InitDB`).
  * Creates a Gin router instance.
  * Registers routes (`routes.RegisterRoutes`).
  * Starts the HTTP server.
* `db`: Package for database interactions.
* `routes`: Package for defining API routes.

**Database**

The database configuration and interactions are handled within the `db` package. Ensure the necessary database configurations are provided.

**API Endpoints**

The available API endpoints are defined in the `routes` package. The specific endpoints and their functionalities are not provided in the given code snippet.
