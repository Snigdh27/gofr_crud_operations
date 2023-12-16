# gofr_crud_operations
# CRUD Movies Go

CRUD Movies Go is a simple Go web application that provides endpoints to perform CRUD (Create, Read, Update, Delete) operations on a collection of movies. It uses the Gorilla Mux router for handling HTTP requests.

## Table of Contents

- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Endpoints](#endpoints)
- [Sample Requests](#sample-requests)
- [License](#license)

## Features

- **Get all movies:** Retrieve a list of all movies.
- **Get movie by ID:** Retrieve details of a specific movie by its ID.
- **Create a movie:** Add a new movie to the collection.
- **Update a movie:** Modify details of an existing movie.
- **Delete a movie:** Remove a movie from the collection.

## Prerequisites

Before running the application, ensure you have the following installed:

- Go (version 1.16 or higher)
- Gorilla Mux (`go get -u github.com/gorilla/mux`)

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/CRUD-Movies-Go.git

2. Change into project directory :
   cd CRUD-Movies-Go
3. Install dependencies
   go mod tidy

## Usage
1. Run the application :
   go run main.go
2. The server will start at http://localhost:8000.

## Endpoints
 1. GET /movies: Get a list of all movies.
 2. GET /movies/{id}: Get details of a specific movie by ID.
 3. POST /movies: Create a new movie.
 4. PUT /movies/{id}: Update details of a movie by ID.
 5. DELETE /movies/{id}: Delete a movie by ID.

POSTMAN API LINK - https://api.postman.com/collections/31368503-c0c26eab-d729-4e13-b0af-e3d03b280c2c?access_key=PMAT-01HHS8C0HAT1B8GMFXE0PGR5JM
