# Real-Time Tracking-System

## Overview

This project showcases real-time location updates on a map using EJS for templating, Leaflet for mapping functionality, and Socket.io for WebSocket-based communication between clients and servers. Users can see their own and others' live locations updated dynamically on the map.

## Features

- Real-time updating of markers on the map based on user locations.
- WebSocket-based communication for efficient and instant data transmission.
- User-friendly interface with EJS templates for dynamic content rendering.

## Technologies Used

- **Frontend**:
  - EJS: Templating engine for generating dynamic HTML content.
  - Leaflet: JavaScript library for interactive maps.
  - HTML/CSS: Basic structure and styling.
  - JavaScript: Handling real-time updates and interactions.

- **Backend**:
  - Node.js: Server-side JavaScript runtime.
  - Express.js: Web application framework for Node.js.
  - Socket.io: Real-time bidirectional event-based communication library.

## Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/swabhi16s/Tracking-System.git
   cd Tracking-System
2.**Install dependencies:**

bash
Copy code
npm install
Run the server:

bash
Copy code
npm start
This will start the server, and your application will be accessible at http://localhost:3000.

##Usage
**Access the application:**

Open your web browser and navigate to http://localhost:3000.

Grant geolocation permissions:

When prompted, grant permission for the application to access your device's location.

##View real-time updates:

The map will display your current location and the locations of other connected users.
As users move, their markers will update in real-time on the map.

##Known Issues
Geolocation permissions may not work consistently across all browsers and devices.
Network latency can affect the real-time updating experience.
