# Incident Management Dashboard

A full-stack incident management system with a Node.js/Express backend and Next.js frontend, supporting CSV bulk upload and real-time incident tracking.

## Overview
Manages IT incidents through a REST API with CRUD operations, CSV import for bulk data loading, and a Next.js dashboard with incident creation, listing, and detail views.

## Features
- RESTful incident API (Express.js)
- CSV bulk upload and parsing
- Next.js frontend dashboard
- Incident create, view, and list pages
- Input validation and error handling
- One-command startup scripts (bat/sh)

## Technologies Used
- **Backend:** Node.js, Express.js
- **Frontend:** Next.js, React
- **Data:** JSON store, CSV parsing
- **Tooling:** npm workspaces

## Project Structure
```
backend/
+-- server.js                    # Express server entry point
+-- src/
    +-- app.js                   # App configuration and middleware
    +-- routes/incidents.routes.js
    +-- services/incidents.service.js
    +-- store/incidents.store.js
    +-- utils/csv.js, validate.js

frontend/
+-- pages/
¦   +-- index.js                 # Home / redirect
¦   +-- dashboard.js             # Incidents dashboard
¦   +-- bulk-upload.js           # CSV upload page
¦   +-- incidents/[id].js        # Incident detail
+-- services/api.js
```

## Getting Started
```bash
# Install all dependencies
cd backend && npm install
cd ../frontend && npm install

# Start both servers
./app-start.sh   # or app-start.bat on Windows
```

## Screenshots

> _Screenshots coming soon_

## Author
Kandy Kochar
