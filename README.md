# Exercise Tracker Backend

A simple Node.js backend project for an Exercise Tracker application. This project provides a RESTful API to manage exercises, users, and workout logs.

## Features

- **User Management**: Create, update, and delete user profiles.
- **Exercise Logging**: Log exercises with details such as type, duration, and date.
- **Workout History**: Retrieve workout logs for a specific user within a date range.
- **Data Persistence**: Uses MongoDB to store user profiles and exercise logs.

## Getting Started

### Prerequisites

Make sure you have the following installed before setting up the project:

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/) (Node Package Manager)
- [MongoDB](https://www.mongodb.com/) (Make sure it's running locally or provide connection details)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/fishonamos/exercisetracker.git
   ```

2. Change into the project directory:
   ```bash
   cd exercise-tracker-backend
   ```

3. Install dependencies:
   ```bash
   npm install
   ```

4. Create a `.env` file and configure MongoDB connection:
   ```
   MONGODB_URI=your-mongodb-connection-string
   ```

5. Start the server:
   ```bash
   npm start
   ```

Now, your Exercise Tracker Backend is ready to handle exercise and user data.

## API Endpoints

- **POST /api/users**: Create a new user.
- **GET /api/users/:id**: Retrieve user details.
- **POST /api/exercises**: Log a new exercise for a user.
- **GET /api/exercises/:id**: Retrieve exercise logs for a user.

Refer to the API documentation or source code for additional details on available routes.

## Possible Uses

1. **Fitness Apps**: Integrate the backend into fitness applications to track user exercises.
2. **Workout Platforms**: Build a workout platform allowing users to log and analyze their workout history.
3. **Health and Wellness Services**: Incorporate exercise tracking features into health and wellness services.

Feel free to customize and extend this backend to suit the specific needs of your exercise-related application.
