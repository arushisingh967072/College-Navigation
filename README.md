📍 College Navigation System

A smart, map-based solution for navigating large college campuses with ease. Features include real-time routing, indoor room-level navigation, 3D building views, and a faculty search system.

🚀 Overview

This system helps students, faculty, and visitors navigate the campus efficiently. It integrates 3D models, real-time directions, and searchable directories to improve the user experience.

🔥 Key Features

🗺️ Campus Map: View all buildings, hostels, and key areas

🏢 Indoor Navigation: Locate rooms, labs, and faculty offices

📍 Live Directions: Turn-by-turn routes using Dijkstra's algorithm

🎮 3D Visualization: Explore the campus in 3D

🔍 Smart Search: Find faculty and places using Fuse.js

📅 Event Integration: View announcements and event locations

📱 Responsive Design: Works well on all devices

🛠 Installation Guide

Backend Setup

git clone https://github.com/yourusername/college-navigation.git
cd college-navigation/backend
npm install
npm start

Frontend Setup

cd ../frontend
npm install
npm run dev

⚙️ Dependencies

Backend

{
  "bcrypt": "^5.1.1",
  "cors": "^2.8.5",
  "dotenv": "^16.4.5",
  "express": "^4.21.1",
  "fuse.js": "^7.0.0",
  "leaflet": "^1.9.4",
  "mongoose": "^8.7.1",
  "socket.io": "^4.8.1",
  "socket.io-client": "^4.8.1"
}

Frontend

{
  "@react-google-maps/api": "^2.20.3",
  "axios": "^1.7.7",
  "dijkstrajs": "^1.0.3",
  "fuse.js": "^7.0.0",
  "leaflet": "^1.9.4",
  "leaflet-control-geocoder": "^2.4.0",
  "leaflet-routing-machine": "^3.2.12",
  "mapbox-gl": "^3.7.0",
  "react": "^18.3.1",
  "react-leaflet": "^4.2.1",
  "react-router-dom": "^6.26.2"
}

🙏 Acknowledgements

OpenStreetMap, Google Maps, Mapbox – Mapping APIs

React, Vite, TailwindCSS – UI frameworks

Leaflet, Three.js, GSAP – Visualization tools

