# Prolici - Proyectos Ligeros Civiles

Corporate website for Prolici, a Dominican construction company specializing in lightweight construction projects and high-quality finishes.

## Description

Prolici (Proyectos Ligeros Civiles) is a Dominican construction company founded by entrepreneur Armando Diaz and architect Ronny A. Cruz. This repository contains the corporate website showcasing the company's services, completed projects, team, and contact information. The site is deployed via Firebase Hosting.

## Features

- Responsive corporate website
- Service showcase with detailed descriptions
- Project gallery
- Team section
- Contact form with client-side validation
- Firebase Hosting deployment configuration
- SEO-optimized meta tags
- Mobile-first design

## Tech Stack

- **HTML5** - Semantic markup
- **CSS3** - Flexbox, Grid layouts, custom properties
- **JavaScript** - Vanilla JS for interactivity
- **Font Awesome** - Icon library
- **Google Maps** - Location embedding
- **Firebase Hosting** - Deployment platform

## Getting Started

### Prerequisites

- A modern web browser
- Firebase CLI (for deployment)

### Local Development

Simply open `Prolici.do/index.html` in your browser, or serve with any static file server:

```bash
cd Prolici.do
python3 -m http.server 8080
```

### Deployment

```bash
cd Prolici.do
firebase deploy
```

### Environment Variables

No environment variables required for the static site. Firebase project configuration is in `firebase.json`.

## Project Structure

```
Prolici/
└── Prolici.do/
    ├── index.html          # Homepage
    ├── nosotros.html       # About us
    ├── servicios.html      # Services
    ├── proyectos.html      # Projects gallery
    ├── contacto.html       # Contact form
    ├── css/                # Stylesheets
    ├── js/                 # JavaScript files
    ├── img/                # Images and assets
    ├── public/             # Firebase public directory
    ├── firebase.json       # Firebase configuration
    └── README.md           # Subdirectory documentation
```

## Contributing

PRs welcome. Please open an issue first to discuss proposed changes.

## License

MIT License - see [LICENSE](LICENSE) for details.

## Credits

Built by Armando Diaz Silverio
