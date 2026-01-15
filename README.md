# 🚦 Indore Route Pathfinder

# React Node.js MongoDB

# 

# A simple web application to plan routes between stations in Indore using Dijkstra's Algorithm

# 

# 🚀 Live Demo

# 

# ✨ What it does

# 📍 Add Stations: Create new stations/locations

# 🔗 Connect Stations: Link stations with distance and cost

# 🧭 Find Routes: Calculate shortest path by distance OR cheapest path by cost

# 📊 View All: See all stations and connections in one place

# 🛠️ Tech Stack

# Frontend: React.js, Tailwind CSS

# Backend: Node.js, Express.js

# Database: MongoDB

# Algorithm: Dijkstra's Shortest Path

# 🏃‍♂️ Quick Start

# 1\. Clone \& Install

# git clone https://github.com/Rajkumar1212-coder/indore-route-planner.git

# cd indore-route-planner

# 

# \# Backend

# cd backend \&\& npm install

# 

# \# Frontend  

# cd ../frontend \&\& npm install

# 2\. Setup Environment

# Create .env in backend folder:

# 

# MONGO\_URI=your\_mongodb\_connection\_string

# PORT=5000

# 3\. Run Application

# \# Start backend (Terminal 1)

# cd backend \&\& npm run dev

# 

# \# Start frontend (Terminal 2)  

# cd frontend \&\& npm run dev

# Open http://localhost:3000 🎉

# 

# 🎯 How to Use

# Add Stations: Enter station name and click "Add Station"

# Connect Stations: Select two stations, enter distance (km) and cost (₹), click "Add Connection"

# Find Route: Choose start/end stations, select "Distance" or "Cost" optimization, click "Find Route"

# View Results: See the optimal path with total distance and cost

# 📁 Project Structure

# indore-route-planner/

# ├── frontend/          # React app

# │   ├── src/

# │   │   └── App.jsx    # Main component

# │   └── package.json

# ├── backend/           # Express API

# │   ├── models/        # MongoDB schemas  

# │   ├── routes/        # API routes

# │   ├── utils/         # Dijkstra algorithm

# │   └── server.js      # Main server

# └── README.md

# 🔌 API Endpoints

# GET    /api/stations     # Get all stations

# POST   /api/stations     # Add new station

# GET    /api/connections  # Get all connections  

# POST   /api/connections  # Add new connection

# POST   /api/route        # Calculate optimal route

# 🧮 Algorithm

# Uses Dijkstra's Algorithm to find:

# 

# Shortest Distance: Minimum total kilometers

# Cheapest Cost: Minimum total rupees

# 🚀 Deployment

# Frontend: Deploy to Vercel : https://indore-metro.vercel.app

# Backend: Deploy to Render : https://indore-metro.onrender.com

# Set environment variables in deployment platforms

# 🤝 Contributing

# Fork the repository

# Create feature branch: git checkout -b feature-name

# Commit changes: git commit -m 'Add feature'

# Push branch: git push origin feature-name

# Open Pull Request

# 📬 Contact

# Made by Rajkumar Singh

# 

# 📧 Email: rajkumarsingh1292004@gmail.com

# 💻 GitHub: Rajkumar1212-coder

# 📄 License

# MIT License - feel free to use this project!



