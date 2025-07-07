# Display x Design Portfolio Website

## Overview

This repository contains a sleek, minimal portfolio website for Display x Design, a custom fabrication business specializing in shelving, framing, and art installation services. The website features a black and white aesthetic with clean typography, built using modern web technologies for optimal performance and user experience.

## System Architecture

### Frontend Architecture
- **Pure Static Site**: Built with vanilla HTML5, CSS3, and JavaScript
- **No Framework Dependencies**: Lightweight approach using native web technologies
- **Component-Based Structure**: Modular CSS and JavaScript organization
- **Mobile-First Design**: Responsive layout using CSS Grid and Flexbox

### Technology Stack
- **HTML5**: Semantic markup with proper SEO meta tags
- **CSS3**: Modern features including custom properties, Grid, and Flexbox
- **Vanilla JavaScript**: Client-side interactions and navigation
- **External Dependencies**:
  - Inter font from Google Fonts
  - Feather Icons for consistent iconography

## Key Components

### Navigation System
- Fixed navigation bar with smooth scrolling
- Mobile hamburger menu with toggle functionality
- Active section highlighting based on scroll position
- Click-outside-to-close mobile menu behavior

### Hero Section
- Large typography with responsive scaling using clamp()
- Call-to-action button for lead generation
- Optimized for various screen sizes

### Services Section
- Grid-based layout showcasing three main services:
  - Design & Fabrication
  - Framing
  - Artwork Installation

### Portfolio Section
- Structured for future work showcases
- Ready for image galleries and project details

### Contact System
- Contact form structure in place
- Ready for backend integration
- Includes business contact information

## Data Flow

### Static Content Delivery
1. HTML structure defines semantic layout
2. CSS provides styling and responsive behavior
3. JavaScript enhances user interactions
4. External fonts and icons loaded from CDNs

### User Interactions
1. Navigation clicks trigger smooth scrolling
2. Mobile menu toggles on hamburger click
3. Form submissions (requires backend integration)
4. Scroll position updates active navigation state

## External Dependencies

### CDN Resources
- **Google Fonts**: Inter font family for typography
- **Feather Icons**: Consistent iconography system
- **GitHub Pages**: Static hosting platform

### Third-Party Integrations
- Contact form backend integration needed
- Analytics tracking can be added
- Domain management through DNS providers

## Deployment Strategy

### Current Setup
- **Platform**: GitHub Pages
- **Domain**: displayxdesign.com (configured via CNAME)
- **Deployment**: Automatic from main branch
- **SSL**: Provided by GitHub Pages

### DNS Configuration
- CNAME record pointing to GitHub Pages
- Alternative A records for GitHub Pages IPs:
  - 185.199.108.153
  - 185.199.109.153
  - 185.199.110.153
  - 185.199.111.153

### Performance Optimizations
- Minimal external dependencies
- Optimized font loading with preconnect
- Semantic HTML for better SEO
- Responsive images (when portfolio added)

## Changelog

```
Changelog:
- July 07, 2025. Initial setup
```

## User Preferences

```
Preferred communication style: Simple, everyday language.
```