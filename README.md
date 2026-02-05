# Complaint / Issue Tracker API

A simple REST API built using Node.js and Express.js to manage complaints.  
This project demonstrates clean backend architecture using routes, controllers, and middleware without using any database.

## Tech Stack
- Node.js
- Express.js
- JavaScript (ES Modules)

## Folder Structure
├── app.js
├── server.js
├── package.json
├── Routes/
├── Controllers/
└── Middleware/

## Complaint Object
```json
{
  "id": 1,
  "title": "string",
  "description": "string",
  "status": "open | resolved"
}
How to Run
npm install
npm start

API Endpoints

GET /complaints – Fetch all complaints

POST /complaints – Create a complaint

PUT /complaints/:id/resolve – Resolve a complaint (Protected)

DELETE /complaints/:id – Delete a complaint (Protected)

Middleware

Logger Middleware (logs HTTP method & URL)

Auth Middleware (protects resolve & delete routes)
