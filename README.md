### WorldWise: Your Personal Travel Map

WorldWise is a web application that allows you to keep a visual diary of your travels. You can mark the cities and countries you've visited, add notes about your experiences, and see all your adventures displayed on an interactive map. This project uses a combination of modern frontend technologies to create a seamless and engaging user experience.

## Features

- Interactive Map: Utilizes Leaflet to display an interactive world map.
- Mark Visited Locations: Click on the map to add new cities you've visited.
- Geolocation: Automatically find your current location with the click of a button.
- Add Travel Notes: For each city, you can add the date of your visit and personal notes.
- Persistent Data: All your visited locations and notes are saved to a local backend powered by json-server.
- Protected Routes: The main application is behind a mock authentication system to demonstrate route protection.

## Tech Stack

This project is built with a modern frontend stack:

- Framework: React
- Routing: React Router
- State Management: React Context API
- Styling: CSS Modules
- Interactive Map: Leaflet & React-Leaflet
- Date Selection: React Date Picker
- Browser APIs: Geolocation API
- Local Backend: JSON Server

## Getting Started

To get a local copy up and running, follow these simple steps.

# Prerequisites

Make sure you have Node.js and npm installed on your machine.
Installation & Setup

- Clone the repository
- Install NPM packages:

```bash
  npm install
```

# Running the Application

This project requires two terminals running concurrently: one for the React development server (frontend) and one for the JSON server (backend).

Terminal 1: Start the Frontend. In your first terminal, run the following command to start the React application:

```bash
npm run dev
```

This will start the development server, and you should be able to view the application at http://localhost:5173 (or another port if 5173 is busy).

Terminal 2: Start the Backend JSON Server
In a new, separate terminal window, run the following command to start the JSON server that will act as your database:

```bash
npm run server
```

This will start the backend server, typically on http://localhost:8000. The application will make requests to this server to fetch and store data.
Once both servers are running, you can open your browser to the frontend URL and start exploring the WorldWise app!
