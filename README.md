# Display x Design - Portfolio Website

A sleek, minimal black and white portfolio website for Display x Design custom fabrication business.

## Overview

Display x Design specializes in custom fabrication, shelving, framing, and art installation services. This website showcases their services and provides a platform for potential clients to learn about their work and get in touch.

## Features

- **Sleek Design**: Minimal black and white aesthetic with clean typography
- **Responsive**: Fully responsive design that works on all devices
- **Performance**: Optimized for fast loading with minimal dependencies
- **SEO Friendly**: Proper meta tags and semantic HTML structure
- **Contact Form**: Ready-to-use contact form (requires backend integration)
- **Portfolio Ready**: Structure in place for showcasing work samples

## Technologies Used

- HTML5 with semantic markup
- CSS3 with modern features (Grid, Flexbox, Custom Properties)
- Vanilla JavaScript for interactions
- Feather Icons for consistent iconography
- Inter font from Google Fonts

## Setup Instructions

### For GitHub Pages Deployment

1. Fork or clone this repository
2. Enable GitHub Pages in repository settings
3. Set source to "Deploy from a branch" and select "main"
4. Your site will be available at `https://yourusername.github.io/repository-name`

### Custom Domain Setup

1. Purchase your desired domain name
2. Update the `CNAME` file with your domain (currently set to `displayxdesign.com`)
3. Configure your domain's DNS settings:
   - Add a CNAME record pointing to `yourusername.github.io`
   - Or add A records pointing to GitHub Pages IPs:
     - 185.199.108.153
     - 185.199.109.153
     - 185.199.110.153
     - 185.199.111.153

### Customization

#### Update Contact Information
Edit the contact details in `index.html`:
- Replace `info@displayxdesign.com` with your email
- Add your phone number
- Update service area if different from NYC

#### Add Portfolio Images
1. Create an `images` folder in the repository
2. Add your project photos
3. Update the portfolio section in `index.html` to display your work
4. Replace the placeholder with actual gallery code

#### Customize Colors and Fonts
- Main styles are in `styles.css`
- Current color scheme uses pure black (#000) and white (#fff)
- Font can be changed by updating the Google Fonts import in `index.html`

#### Contact Form Integration
The contact form is currently static. To make it functional:
1. Use a service like Formspree, Netlify Forms, or EmailJS
2. Update the form action and add necessary configuration
3. Or integrate with your own backend API

## File Structure

