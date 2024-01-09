# Neo4j Actor Network API

## Overview
CinemaGraph API leverages the Neo4j graph database to map and analyze connections in the film industry. Focused on revealing the "Six Degrees of Kevin Bacon," it enables adding and querying actors and movies, establishing their relationships, and discovering the shortest paths within the cinematic network.
## Features
- **Actor and Movie Management**: Add actors and movies to the Neo4j database.
- **Relationship Mapping**: Create 'ACTED_IN' relationships between actors and movies.
- **Data Retrieval**: Fetch detailed information about actors and movies, including their relationships.
- **Path Calculation**: Compute the shortest path between any actor and Kevin Bacon, highlighting the interconnected nature of the film industry.
- **REST API Design**: Implements RESTful principles for a scalable and easy-to-use service.

## Endpoints
- `PUT /api/v1/addActor`: Add an actor to the database.
- `PUT /api/v1/addMovie`: Add a movie to the database.
- `PUT /api/v1/addRelationship`: Create an 'ACTED_IN' relationship between an actor and a movie.
- `GET /api/v1/getActor`: Retrieve information about an actor.
- `GET /api/v1/getMovie`: Fetch details of a movie.
- `GET /api/v1/hasRelationship`: Check if a relationship exists between an actor and a movie.
- `GET /api/v1/computeBaconNumber`: Find the Bacon Number for an actor.
- `GET /api/v1/computeBaconPath`: Compute the shortest path from any actor to Kevin Bacon.

## Technology Stack
- Java 1.8
- Neo4j Graph Database
- Maven for build automation

## Setup and Installation
1. **Clone the repository**:

git clone https://github.com/Bilalabdali1/CinemaGraph-API.git



## Running the Application
- **Compile**: `mvn compile`
- **Execute**: `mvn exec:java`

## Testing
The application includes comprehensive tests for each endpoint, ensuring functionality and reliability. 
