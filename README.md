# Rosemallow Intern - 3D Periodic Table Visualization

A 3D interactive visualization displaying data in multiple formats (Table, Sphere, Double Helix, Grid) using Three.js and Google Sheets API integration.

## Features

- **Google Sheets Integration**: Real-time data loading from Google Sheets
- **Google Authentication**: Secure OAuth 2.0 login
- **4 Visualization Modes**:
  - Table: 20x10 grid layout
  - Sphere: 3D spherical arrangement
  - Double Helix: Two intertwined spirals
  - Grid: 5x4x10 3D grid
- **Color-coded tiles** based on Net Worth:
  - 🔴 Red: < $100,000
  - 🟠 Orange: $100,000 - $200,000
  - 🟢 Green: > $200,000

## Live Demo

[View Live Demo](https://YOUR_USERNAME.github.io/rosemallow_intern/)

## Setup

1. Clone this repository
2. Configure Google Cloud Project:
   - Create OAuth 2.0 Client ID
   - Enable Google Sheets API
   - Add authorized origins and redirect URIs
3. Update `index.html` with your credentials:
   - CLIENT_ID
   - API_KEY
   - SPREADSHEET_ID
4. Open `index.html` in a web browser

## Technologies Used

- Three.js - 3D graphics
- Google Sheets API - Data source
- Google OAuth 2.0 - Authentication
- CSS3D Renderer - 3D DOM elements
- TWEEN.js - Smooth animations

## Assignment

This project was created as part of the Rosemallow internship evaluation process.

## License

© 2026 - Educational Project
