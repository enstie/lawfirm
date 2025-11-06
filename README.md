# Crest Immigration Law Firm Website

A professional, responsive website for Crest Immigration Law Firm, founded by Attorney Samuel Bookman.

## Website Features

- **Responsive Design**: Fully optimized for mobile, tablet, and desktop devices
- **Professional Styling**: Modern design with navy blue (#1a2a4e) and gold (#d4a574) color scheme
- **Typography**: Elegant fonts - Merriweather for headers, Open Sans for body text
- **Four Main Pages**:
  - Home: Hero section with firm introduction and service overview
  - About: Detailed information about Samuel Bookman and firm values
  - Services: Comprehensive list of immigration law services
  - Contact: Contact form and Google Maps integration

## Technology Stack

- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Google Fonts (Merriweather, Open Sans)

## Project Structure

```
lawfirm/
├── index.html          # Home page
├── about.html          # About page
├── services.html       # Services page
├── contact.html        # Contact page
├── assets/
│   ├── css/
│   │   └── style.css   # Main stylesheet
│   ├── js/
│   │   └── script.js   # JavaScript for navigation and form handling
│   └── images/         # Image assets directory
└── README.md           # This file
```

## Contact Information

- **Attorney**: Samuel Bookman
- **Phone**: +31 97005033157
- **Email**: lawsamchambers@email.com
- **Firm**: Crest Immigration Law Firm

## Deployment on GitHub Pages

This website is designed to be deployed on GitHub Pages. Follow these steps:

1. Push the repository to GitHub
2. Go to the repository Settings
3. Navigate to Pages section
4. Under "Source", select the branch you want to deploy (e.g., `main` or `master`)
5. Click Save
6. Your website will be available at: `https://[username].github.io/[repository-name]/`

## Local Development

To run the website locally:

1. Clone the repository
2. Open a terminal in the project directory
3. Start a local web server:
   ```bash
   # Using Python 3
   python3 -m http.server 8080
   
   # Using Python 2
   python -m SimpleHTTPServer 8080
   
   # Using Node.js (requires http-server package)
   npx http-server -p 8080
   ```
4. Open your browser and navigate to `http://localhost:8080`

## Features

### Responsive Navigation
- Desktop: Horizontal navigation bar
- Mobile: Hamburger menu with smooth transitions

### Contact Form
- Client-side validation
- Required fields: Name, Email, Message
- Phone number is optional
- Success/error messages via JavaScript alerts

### Google Maps Integration
- Embedded map with Amsterdam location (placeholder)
- Can be customized to show actual office location

## Browser Compatibility

The website is compatible with modern browsers:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

© 2023 Crest Immigration Law Firm. All rights reserved.
