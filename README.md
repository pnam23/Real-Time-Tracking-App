# Real-Time Device Tracking Application

A real-time device tracking application built with **Node.js**, **Express**, **Socket.IO**, and **Leaflet**. This application allows users to track their devices' locations on a map in real-time using geolocation.

## Live Demo

Check out the live version of the application [here](https://real-time-tracking-app-i2tm.onrender.com/).

## Features
- **Real-time location tracking**: Track devices in real time using WebSocket communication.
- **Interactive map interface**: Display device locations on an interactive map with **Leaflet**.
- **Custom markers**: Each user location is represented by a unique marker.
- **Responsive design**: Provides a seamless user experience on different devices.

## Technologies Used
- **Node.js**: JavaScript runtime environment for building the backend server.
- **Express**: Web framework for Node.js to manage routes and requests.
- **Socket.IO**: Enables real-time, bidirectional communication between the client and server.
- **Leaflet**: Lightweight, open-source JavaScript library for creating interactive maps.
- **HTML/CSS**: For building and styling the frontend.

## Getting Started

### Prerequisites
Ensure the following software is installed on your machine:
- **Node.js**: Download and install from [here](https://nodejs.org/).
- **npm**: Node package manager, which comes bundled with Node.js.

### Installation
1. Clone the repository to your local machine:
   ```bash
   git clone <repository-url>
   cd <project-directory>
2. Install project dependencies:
   ```bash
   npm install express ejs
   npm install socket.io
### Running the Application
To start the application and enable automatic reloading during development, follow these steps:
1. Install nodemon globally (if you haven't already):
   ```bash
   npm install -g nodemon
2. Run the application:
   ```bash
   npx nodemon app.js
3. Open your browser and navigate to http://localhost:3000 to view the real-time tracking interface.
