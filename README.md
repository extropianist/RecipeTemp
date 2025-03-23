# README.md
# TastyHub App

## Description
TastyHub is a web application designed to help users discover, create, and manage recipes, as well as schedule their cooking activities. It features a unique Gantt chart visualization to assist users in timing and coordinating the various steps involved in preparing a meal.

## Features
* **Recipe Discovery:** Browse a wide variety of recipes.
* **Recipe Creation:** Create and share your own recipes.
* **Cooking Schedule:** Plan your cooking activities with a calendar.
* **Gantt Chart Assistant:** Visualize recipe steps and timing with an interactive Gantt chart.
* **User Profiles:** Manage your recipes, schedules, and profile.
* **Search:** Easily find recipes using the search functionality.

## Technologies
* Frontend: React
* Backend: Node.js, Express
* Database: MongoDB (or PostgreSQL)
* Gantt Chart: React Gantt Component

## Setup
### Prerequisites
* Node.js and npm installed
* MongoDB or PostgreSQL database set up

### Installation
1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd TastyHub
   ```
2. Install backend dependencies:
   ```bash
   cd backend
   npm install
   ```
3. Set up environment variables:
   * Create a `.env` file in the `backend` directory.
   * Add the following variables, replacing the values with your actual configuration:
     ```
     PORT=3001
     MONGODB_URI=mongodb://username:password@host:port/database_name
     # or for PostgreSQL
     # DB_HOST=your_host
     # DB_USER=your_user
     # DB_PASSWORD=your_password
     # DB_NAME=your_database_name
     JWT_SECRET=your_jwt_secret_key # Used for authentication
     ```
4. Start the backend server:
   ```bash
   npm run start # or npm run dev for development
   ```
5. Install frontend dependencies:
   ```bash
   cd ../frontend
   npm install
   ```
6. Start the frontend application:
   ```bash
   npm start
   ```

## Usage
* **Browse Recipes:** Use the "Discover Recipes" section on the home page.
* **Create Recipes:** Go to "My Recipes" to add your own recipes.
* **View Recipe Details:** Click on a recipe to see ingredients and steps, including the Gantt chart.
* **Manage Schedule:** Use the "Cooking Schedule" to plan your cooking.
* **View Profile:** See your recipes and settings in your "Profile".

## Contributing
1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature/your-feature-name`
3. Make your changes.
4. Commit your changes: `git commit -m "Add your feature"`
5. Push to the branch: `git push origin feature/your-feature-name`
6. Submit a pull request.

## License
MIT License
