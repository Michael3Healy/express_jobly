# Jobly Backend

**Jobly** is a comprehensive job searching application built with a backend using Node, Express, and PostgreSQL, and a frontend using React. This application allows users to search for job postings and companies, as well as apply for jobs, using an intuitive interface. This is the repository for the backend. The frontend repository can be found here: [Jobly Frontend](https://github.com/Michael3Healy/jobly_frontend)

## Backend Features

### Authentication & Authorization

- Utilizes JWT tokens for secure access to API endpoints.
- Implements role-based permissions to control access levels.

### Companies & Jobs

- Supports CRUD operations for managing companies and job postings.
- Provides advanced filtering and search functionalities for both companies and jobs.

### Job Applications

- Allows users to apply for jobs and tracks their application history.

### Testing

- Includes comprehensive unit and integration tests to ensure robust functionality and maintainable codebase.

### Documentation

- Extensively documented codebase with clear explanations of functions and routes.

## Setup

### Backend Setup

1. Clone the repository: `git clone <repository-url>`
2. Navigate to the backend directory: `cd backend`
3. Install dependencies: `npm install`
4. Set up environment variables as required (e.g., database configuration, JWT secret).
5. Run tests using: `npm test`
6. Start the server: `npm start`

## Technologies Used

### Backend

- Node
- Express
- PostgreSQL
- JWT
- Jest
