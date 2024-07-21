# Whoami Microservice

A Node.js microservice that provides information about the requestor's IP address, language, and software. This project uses Express to create a simple API that responds with details about the client's request.

## Features
- Returns the client's IP address.
- Provides the client's preferred language.
- Reports the client's user-agent (software) details.

## Endpoints
- `GET /api/whoami` - Returns a JSON object with the following fields:
  - `ipaddress`: The client's IP address.
  - `language`: The client's preferred language.
  - `software`: The client's user-agent string.

## Tech Stack
- Node.js
- Express
- CORS for cross-origin resource sharing

## Setup
1. Clone the repo.
2. Run `npm install` to install dependencies.
3. Start the application with `npm start` or `node index.js`.
4. Access the service at `http://localhost:3000`.

## Project Structure
- `index.js`: The main application file where the Express app is configured and routes are defined.
- `views/index.html`: The static HTML file served at the root route.

## Usage
Navigate to `/api/whoami` to get the client's IP address, language, and user-agent information in JSON format.
