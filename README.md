# Bus Tracker

Welcome to the Bus Tracker project! This web application allows users to conveniently track the location of buses in real-time. Built with a modern tech stack, including HTML, CSS, JavaScript, React.js for the frontend, and Node.js, Express, and MongoDB for the backend. The application uses the Mapbox API to provide accurate bus location tracking.

## Table of Contents

- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation](#installation)

## Features

- **Real-time Bus Tracking**: Track buses in real-time on an interactive map.
- **User-friendly Interface**: Clean and intuitive design for ease of use.
- **Map Integration**: Utilizes the Mapbox API for accurate and interactive mapping.
- **Secure Backend**: Robust backend using Node.js, Express, and MongoDB.

## Technologies Used

### Frontend

- **HTML**: Markup language for structuring web content.
- **CSS**: Stylesheet language for designing web pages.
- **JavaScript**: Programming language for web development.
- **React.js**: JavaScript library for building user interfaces.
- **Create Next App**: Boilerplate for setting up a React application with Next.js.

### Backend

- **Node.js**: JavaScript runtime for server-side development.
- **Express**: Minimalist web framework for Node.js.
- **MongoDB**: NoSQL database for storing bus and user data.

### APIs

- **Mapbox API**: Provides map services for real-time bus location tracking.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/yourusername/bus-tracker.git
   cd bus-tracker
   ```

2. **Install dependencies**:
   - For the frontend:
     ```bash
     cd frontend
     npm install
     ```
   - For the backend:
     ```bash
     cd backend
     npm install
     ```

3. **Set up environment variables**:
   - Create a `.env` file in the `backend` directory and add the following variables:
     ```env
     MONGO_URI=your_mongodb_connection_string
     MAPBOX_ACCESS_TOKEN=your_mapbox_access_token
     ```

4. **Start the development servers**:
   - For the backend:
     ```bash
     cd backend
     npm start
     ```
   - For the frontend:
     ```bash
     cd frontend
     npm run dev
     ```

