# Personal Portfolio Website

## Overview

This is a modern, single-page personal portfolio website designed for a final-year B.Tech Computer Science student. The site features a clean "minimal tech geek" aesthetic with an "Amethyst Night" color theme, combining deep dark indigo backgrounds with vibrant purple accents. The website is fully responsive and designed to showcase the student's skills, projects, and contact information in a professional manner.

## User Preferences

Preferred communication style: Simple, everyday language.

## System Architecture

### Frontend Architecture
- **Single-page application**: All content is contained within a single HTML file with smooth scrolling navigation
- **Responsive design**: Mobile-first approach using CSS Grid and Flexbox
- **Static website**: No backend required, suitable for deployment on static hosting platforms
- **Modern CSS**: Utilizes CSS custom properties (variables) and modern features like backdrop-filter

### Technology Stack
- **HTML5**: Semantic markup structure
- **CSS3**: Modern styling with custom properties and advanced effects
- **Vanilla JavaScript**: Minimal JavaScript for enhanced interactivity (Feather Icons)
- **Google Fonts**: Inter font family for typography
- **Feather Icons**: Lightweight icon library loaded via CDN

## Key Components

### Navigation System
- Fixed-position navbar with backdrop blur effect
- Smooth scrolling navigation to page sections
- Responsive hamburger menu for mobile devices
- Highlighted resume button for emphasis

### Content Sections
1. **Hero Section**: Introduction with name, tagline, and call-to-action
2. **About Section**: Professional photo placeholder, bio, and skill badges
3. **Projects Section**: Grid layout showcasing 3 project cards with hover effects
4. **Contact Section**: Social media and contact links with large clickable icons
5. **Footer**: Simple branding and copyright information

### Design System
- **Color Palette**: Amethyst Night theme with CSS custom properties
  - Primary background: #161625 (deep dark indigo)
  - Secondary background: #1e1e32 (dark slate purple)
  - Accent color: #8b5cf6 (vibrant amethyst purple)
  - Text colors: White headings with lavender-grey body text
- **Typography**: Inter font family with multiple weights
- **Interactive Elements**: Hover effects with purple glow and elevation

## Data Flow

### Static Content Flow
- Content is hardcoded in HTML with placeholder text
- Styling applied through CSS custom properties for easy theming
- Navigation links trigger smooth scrolling to corresponding sections
- External resources (fonts, icons) loaded from CDNs

### User Interaction Flow
1. User lands on hero section
2. Navigation allows jumping to any section
3. Project cards provide external links to GitHub and live demos
4. Contact section enables direct communication through email/social links

## External Dependencies

### CDN Resources
- **Google Fonts**: Inter font family (weights 300-700)
- **Feather Icons**: Icon library for consistent iconography
- No additional JavaScript frameworks or libraries required

### Asset Requirements
- Profile photo placeholder in About section
- Project images for each project card
- Resume file for download link

## Deployment Strategy

### Static Hosting Options
- **Recommended**: GitHub Pages, Netlify, Vercel, or Replit hosting
- **Requirements**: Only static file serving needed
- **Domain**: Can be deployed with custom domain or subdomain

### File Structure
```
/
├── index.html          # Main HTML file
├── style.css           # All styling
└── assets/             # Images and resume (to be added)
    ├── profile-photo.jpg
    ├── project-images/
    └── resume.pdf
```

### Performance Considerations
- Minimal external dependencies
- Optimized for fast loading
- Mobile-responsive design
- Modern CSS features with fallbacks

### Maintenance Requirements
- Update project information and links
- Replace placeholder content with actual information
- Add actual images and resume file
- Customize color scheme through CSS variables if needed

## Development Notes

The current implementation provides a complete foundation with:
- Fully structured HTML layout
- Comprehensive CSS styling with modern features
- Responsive design patterns
- Accessibility considerations
- Easy customization through CSS custom properties

The website is ready for content population and can be immediately deployed to any static hosting platform.