# School Management API

A Node.js and MySQL backend project for managing schools.

## Features

- Add new schools
- List schools sorted by proximity

## Tech Stack

- Node.js
- Express.js
- MySQL
- Thunder Client

## API Endpoints

### Add School

POST /addSchool

Request Body:

{
  "name": "ABC School",
  "address": "Pune",
  "latitude": 18.5204,
  "longitude": 73.8567
}

### List Schools

GET /listSchools?latitude=18.5204&longitude=73.8567

## Run Locally

npm install

npm run dev