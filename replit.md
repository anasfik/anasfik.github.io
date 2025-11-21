# Static Portfolio Website

## Overview
A raw, minimalist portfolio website built with pure HTML and JavaScript. No CSS styling is used - the site displays with browser default styles only. Built for Anas Fikhi (Gwhyyy), a Flutter developer from Morocco.

## Features

### Content Sections
- **About Me Section**: "Who I Am" with typing animation effect
- **Skills Section**: "My Skills - If You Want Me to Build Something for You" with real-time search functionality (searches names and descriptions)
  - Hover tooltips showing skill descriptions
  - Google search icons for each skill
- **Portfolio Section**: List of projects with descriptions and links
  - Real-time GitHub star badges using shields.io API
- **Contact Section**: Contact information with clickable email links
- **Social Media Section**: Links to social profiles

### Interactive Features (Vanilla JavaScript)
1. **Typing Animation**: Smooth typing effect for the About section text
2. **Visit Counter**: Tracks page visits using localStorage (persists per browser)
3. **Live Morocco Time**: Real-time clock showing current time in Africa/Casablanca timezone, updates every second
4. **Years of Experience Calculator**: Auto-calculates years from start date (2018)
5. **Click-to-Copy**: Copy buttons for email and GitHub username with visual feedback
6. **Random Dev Quote**: Displays a random developer quote on each page load
7. **Last Updated Timestamp**: Shows when content was last updated in footer

## Technology Stack
- HTML5
- Vanilla JavaScript (no libraries or frameworks)
- localStorage for visit persistence
- shields.io API for GitHub star badges
- No CSS (intentionally raw/unstyled for minimalist aesthetic)

## Structure
- `index.html` - Main portfolio page with all sections and JavaScript functionality
- `server.py` - Simple Python HTTP server to serve the static site

## User Information
- Name: Anas Fikhi
- Brand: Gwhyyy
- Location: Morocco
- Email: work@gwhyyy.com
- GitHub: anasfik
- Experience Since: 2018
- Last Updated: November 21, 2025

## Recent Changes
- 2025-11-21: Added seven interactive features (typing animation, visit counter, Morocco time, experience calculator, click-to-copy, random quote, last updated)
- 2025-11-21: Added real-time GitHub star badges to portfolio projects
- 2025-11-21: Made email addresses clickable with mailto links
- 2025-11-21: Added hover tooltips and Google search icons to skills
- 2025-11-21: Initial creation with all sections and interactive skills search

## User Preferences
- Raw HTML without any CSS styling (minimalist aesthetic)
- Vanilla JavaScript only (no frameworks or libraries)
- Emphasis on "effective simplicity" to attract employers
- All interactive features must be functional and professional
