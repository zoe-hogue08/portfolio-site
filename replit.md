# Replit.md

## Overview

This is a static HTML/CSS learning project consisting of multiple standalone web pages. The project appears to be an educational portfolio created by a student learning web development fundamentals. It includes various practice pages covering topics like recipes (Asian food), personal interests (books, music, art), color theory, and a personal portfolio page. There is no backend, database, or dynamic functionality - it's purely static HTML and CSS.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Technology**: Pure HTML5 and CSS3 with no JavaScript frameworks
- **Structure**: Flat file structure with HTML pages at the root level and assets in a dedicated folder
- **Styling Approach**: Mix of inline styles within HTML files and external CSS stylesheets
- **Design Pattern**: Each page is self-contained with its own styling, resulting in inconsistent design across pages

### File Organization
- Root level contains all HTML pages (recipes, personal projects, practice exercises)
- `/assets` folder contains shared CSS files:
  - `personal.css` - Styles for the main portfolio/index page
  - `solution.css` - CSS practice exercise solutions
  - `style.css` - Minimal base styles
  - `script.js` - Empty JavaScript file (unused)

### Page Types
1. **Portfolio Page** (`index.html`) - Main landing page with navigation, hero section, about section, and projects
2. **Recipe Pages** (`duck.html`, `beef.html`, `rice.html`, `recipes.html`) - Collection of Asian food recipes
3. **Practice Pages** (`css practice.html`, `color.html`, `favorite artwork.html`, `favorite_quote.html`) - Various HTML/CSS learning exercises
4. **Project Pages** (`morse code project.html`) - Topic exploration pages

### CSS Architecture
- No CSS preprocessors or build tools
- Gradient backgrounds are commonly used (`linear-gradient`)
- Flexbox used for layout in the portfolio page
- No responsive design framework - basic viewport meta tags only

## External Dependencies

### Third-Party Services
- **External Images**: Several pages load images from external CDNs:
  - `tornadoughalli.com` - Recipe food images
  - `christieathome.com` - Food images
  - `decoart.com` - Color wheel image

### External Links
- Social media links (Instagram, Pinterest)
- Reference links (Wikipedia for Morse code)
- Video editing tools (CapCut)

### Local Assets
- Local images referenced but not present in repository (`peking-duck-2-1.jpg`, `paint.png`, `author.png`, `piano.png`, `music notes.png`)

### No Build Dependencies
- No package.json or build system
- No JavaScript libraries or frameworks
- No CSS frameworks (Bootstrap, Tailwind, etc.)