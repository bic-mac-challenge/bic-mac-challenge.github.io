# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a GitHub Pages landing page for the Big Cross-Modal Attenuation Correction (BIC-MAC) Challenge, a MICCAI challenge. The website will link to:
- GitHub repository
- Codabench project

Reference site for design inspiration: https://fomo25.github.io/

## Design Requirements

- **Visual Design**: Attention-catching and aesthetically pleasing but keep it simple
- **Content Strategy**: Use placeholder images and lorem ipsum text - do NOT hallucinate specific challenge details, dates, or organization information
- **Placeholders**: Include placeholders for organization logos and other assets
- **Layout**: Focus on creating the structure and styling first

## Repository Structure

This is a GitHub Pages site, which means:
- The main HTML file is `index.html` in the root directory
- Static assets (CSS, JS, images) can be organized in subdirectories
- The site will be served at `https://bic-mac-challenge.github.io/`

## Site Architecture

The landing page is a single-page application with the following sections:
- **Hero/Banner**: Main introduction with challenge title, tagline, and hero image placeholder
- **About**: Challenge overview with three feature cards and detailed description
- **Timeline**: Important dates displayed as timeline cards with color-coded borders
- **Organizers**: Organization logos (placeholders) and organizing committee members
- **Participate**: Call-to-action section with links to GitHub and Codabench
- **Footer**: Navigation links and resources

### Tech Stack
- **HTML5**: Single `index.html` file
- **Tailwind CSS**: Via CDN (no build process required)
- **Vanilla JavaScript**: Smooth scrolling navigation and scroll effects
- **Google Fonts**: Inter font family

### Design System
- **Colors**: Blue-purple gradient theme (`#2563eb` to `#7c3aed`)
- **Typography**: Inter font family, modern and minimal
- **Layout**: Responsive design with max-width containers (7xl, 5xl, 4xl)
- **Components**: Cards with rounded corners (rounded-2xl), subtle shadows, hover effects
- **Navigation**: Fixed header with backdrop blur, smooth scrolling to sections

## Development Workflow

### Local Testing
```bash
# Simple HTTP server
python -m http.server

# Or use any other local server
npx http-server
```

### Making Changes
- No build process required - edit `index.html` directly
- Changes pushed to the main branch will automatically deploy to GitHub Pages
- Test locally before pushing

### Customization Points
When replacing placeholders with real content:
1. Replace lorem ipsum text in all sections
2. Update hero image placeholder (aspect-video gradient background)
3. Add actual organization logos (currently SVG placeholders)
4. Update timeline dates (currently "TBD 2026")
5. Add real organizer information and photos
6. Update GitHub and Codabench URLs in the Participate section
