# Real Estate App

A full-stack real estate application that allows users to browse, search, and list properties. The front end is built using React with TailwindCSS for styling, while the back end is powered by Express and MongoDB.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Environment Variables](#environment-variables)
- [API Endpoints](#api-endpoints)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

The Real Estate App provides an intuitive interface for browsing property listings, viewing property details, and managing user listings. It supports user authentication, property search with filters, and property management features.

---

## Features

- **User Authentication:** Secure sign-up, login, and session management.
- **Property Listings:** Browse and search properties by location, price, and other filters.
- **Responsive UI:** Built with React and TailwindCSS for a modern, mobile-first design.
- **Property Management:** Users can add, update, or delete their listings.
- **RESTful API:** Express server provides API endpoints for front-end consumption.
- **Database Integration:** MongoDB stores user data and property information.

---

## Tech Stack

- **Front End:** React, TailwindCSS
- **Back End:** Express.js, Node.js
- **Database:** MongoDB
- **Authentication:** JWT (JSON Web Tokens)
- **Other:** Axios for API calls, dotenv for environment configuration

---

## Project Structure

/real-estate-app ├── /front-end │ ├── /public │ └── /src │ ├── /assests │ ├── /components │ ├── /context │ ├── /Pages │ ├── /services │ ├── App.jsx │<br> ├── /backend │ ├── /controllers │ ├── /models │ ├── /routes │ ├── /uploads │ ├── server.js │ └── config.js │ ├── .env # Environment variables ├── package.json # Project metadata and dependencies └── README.md # Project documentation

---

## Getting Started

### Prerequisites

- **Node.js** (v14 or later)
- **MongoDB** (running locally or a remote instance)
- **npm** or **yarn**

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/real-estate-app.git
   cd real-estate-app
   Install server dependencies:
   ```

cd server
npm install

# or

yarn install
Install client dependencies:

cd ../client
npm install

# or

yarn install
Configure environment variables:

Create a .env file in the /server directory with the following variables:

PORT=5000
MONGO_URI=your-mongodb-connection-string
JWT_SECRET=your_jwt_secret
Run the application:

Start the server:

cd ../server
npm run start

# or

yarn start
Start the client:

bash
Copy
Edit
cd ../client
npm start

# or

yarn start
The client will run on http://localhost:3000 and the server on http://localhost:5000.

Environment Variables
The application uses environment variables to store sensitive information. Below are the main variables used:

PORT: The port on which the Express server runs.
MONGO_URI: MongoDB connection string.
JWT_SECRET: Secret key for signing JWT tokens.
Ensure that these are set correctly in the .env file.

📜 License
This project is licensed under the MIT License.

🌟 Show Your Support
If you find this repository useful, please give it a ⭐️ and share with others!