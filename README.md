# EN3350-TransTrack

EN3350-TransTrack is a full-stack platform for managing transformer data and thermal images.

## Project Structure
- **transtrack_backend_EN3350/** – Spring Boot backend built with Java 21 and Maven. It exposes a REST API using Spring Web, Spring Data JPA and validation utilities.
- **frontend/** – React + TypeScript single-page application built with Vite.

## Getting Started

### Backend
1. Install JDK 21 and Maven.
2. Navigate to `transtrack_backend_EN3350`.
3. Configure database credentials in the environment or application properties.
4. Run `./mvnw spring-boot:run` to start the API server.

### Frontend
1. Install Node.js and npm.
2. Navigate to `frontend`.
3. Run `npm install` to install dependencies.
4. Run `npm run dev` to launch the development server.

## Tests
- Backend: `./mvnw test`
- Frontend: `npm test` (no test script provided yet)

## License
This project is licensed under the [Apache License 2.0](LICENSE).
