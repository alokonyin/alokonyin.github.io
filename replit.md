# Garang Stephen - Portfolio Website

## Overview
This is a personal portfolio website for Garang Stephen, a Computer Science student at Stanford University. The portfolio showcases education, work experience, projects, skills, and contact information.

**Current State:** Fully functional and deployed on Replit.

## Project Architecture

### Technology Stack
- **Frontend:** Static HTML with inline CSS
- **Styling:** Custom CSS with responsive design
- **Server:** Python 3.11 with built-in HTTP server
- **Deployment:** Static site hosting

### File Structure
```
.
├── index.html           # Main portfolio page with all content
├── style.css            # Empty (CSS is inline in index.html)
├── server.py            # Python HTTP server for development
├── images/              # Profile and project images
│   ├── anyuon.jpg
│   ├── anyi.jpg
│   ├── stephenmakuol.jpg
│   └── pic01.jpg
├── CNAME                # Custom domain: anyuon.tech
└── replit.md            # This file
```

### Key Features
- Responsive design for mobile and desktop
- Smooth scrolling navigation
- Animated sections and cards
- Professional gradient styling
- Social media links (GitHub, LinkedIn, Email)

## Development

### Running Locally
The workflow is configured to automatically run the Python HTTP server on port 5000:
```bash
python server.py
```

The server includes:
- Cache-Control headers to prevent caching issues
- Binds to 0.0.0.0:5000 for Replit compatibility
- Serves all static files from the root directory

### Making Changes
1. Edit `index.html` to update content
2. Changes will be visible after a browser refresh
3. The server automatically serves updated files

## Deployment
This project is configured for static deployment on Replit. The deployment serves files from the root directory (`.`) directly.

## Recent Changes
- **December 3, 2025:** Initial import from GitHub
  - Set up Python HTTP server for Replit environment
  - Configured workflow for automatic server startup
  - Configured static deployment settings
  - Added cache-control headers to prevent caching issues

## Contact Information
- **Email:** any14483@stanford.edu
- **GitHub:** https://github.com/alokonyin
- **Custom Domain:** anyuon.tech
