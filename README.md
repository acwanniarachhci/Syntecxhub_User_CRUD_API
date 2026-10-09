# Syntecxhub User CRUD API

A RESTful API for managing users, built with Node.js, Express, and MongoDB (Mongoose).
Created as part of the Syntecxhub Back-End Development Internship (Week 1, Project 1).

## Features

- Create, Read, Update, Delete (CRUD) operations for a User resource
- Input validation (required fields, email format, age range)
- Duplicate email detection
- Proper HTTP status codes and error messages
- MongoDB ID validation

## Tech Stack

- Node.js
- Express
- MongoDB + Mongoose
- dotenv
- nodemon (dev)

## Getting Started

### Prerequisites

- Node.js installed
- MongoDB running locally, or a MongoDB Atlas connection string

### Installation

1. Clone the repository
```bash
   git clone https://github.com/<your-username>/Syntecxhub_User_CRUD_API.git
   cd Syntecxhub_User_CRUD_API
```

2. Install dependencies
```bash
   npm install
```

3. Create a `.env` file in the root folder