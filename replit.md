# Timestamp Microservice

## Overview
This is a FreeCodeCamp Timestamp Microservice project - a Node.js/Express API that converts dates between different formats. The project serves a simple frontend interface and provides API endpoints for timestamp conversion.

## Project Architecture
- **Framework**: Express.js (Node.js)
- **Main Entry**: `index.js`
- **Frontend**: Static HTML served from `views/index.html` with CSS from `public/style.css`
- **Dependencies**: Express, CORS

## Recent Changes
- **2025-11-29**: Initial Replit environment setup
  - Configured server to bind to 0.0.0.0:5000 for Replit environment
  - Set up workflow to run the Express server
  - Enhanced .gitignore for Node.js best practices

## Structure
```
/
├── index.js          # Main Express server
├── package.json      # Dependencies and scripts
├── public/           # Static assets
│   └── style.css
├── views/            # HTML templates
│   └── index.html
└── sample.env        # Environment variable template
```

## Development
- **Start Server**: `npm start`
- **Port**: 5000 (configured for Replit)
- **Host**: 0.0.0.0 (required for Replit environment)

## API Endpoints
- `GET /`: Serves the main HTML page
- `GET /api/hello`: Test endpoint returning a greeting
- Additional timestamp endpoints to be implemented per FreeCodeCamp requirements

## User Preferences
None documented yet.
