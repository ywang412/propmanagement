# Premier Property Management - Hugo Site

A modern, responsive landing page for a property management company built with Hugo static site generator.

## Features

- **Modern Design**: Clean, professional design with Bootstrap 5
- **Responsive Layout**: Mobile-friendly design that works on all devices
- **Hero Section**: Eye-catching banner with property imagery
- **Services Showcase**: Highlighting residential, commercial, and consulting services
- **About Section**: Company information and key benefits
- **Contact Section**: Easy ways to get in touch
- **Fast Performance**: Static site generation for optimal speed

## Technology Stack

- **Hugo**: Static site generator
- **Bootstrap 5**: CSS framework for responsive design
- **Font Awesome**: Icons
- **Google Fonts**: Typography (Inter font family)

## Getting Started

### Prerequisites

- Hugo installed on your system
- Git for version control

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd rentalmanagement
```

2. Start the Hugo development server:
```bash
hugo server --buildDrafts
```

3. Open your browser and navigate to `http://localhost:1313`

### Building for Production

To build the site for production:

```bash
hugo --minify
```

The built site will be in the `public/` directory.

## Customization

### Site Configuration

Edit `hugo.toml` to customize:
- Company name and contact information
- Site title and description
- Navigation menu items

### Content

- Main content is in `content/_index.md`
- Theme templates are in `themes/property-management/layouts/`
- Styling is in the base template

### Images

The site uses Unsplash images for the hero section and about section. You can replace these with your own images by:
1. Adding images to `static/images/`
2. Updating the image URLs in the templates

## Project Structure

```
rentalmanagement/
├── content/
│   └── _index.md          # Main landing page content
├── themes/
│   └── property-management/
│       └── layouts/
│           ├── _default/
│           │   └── baseof.html    # Base template
│           └── index.html         # Landing page template
├── hugo.toml              # Site configuration
└── README.md              # This file
```

## License

This project is open source and available under the [MIT License](LICENSE).

## Support

For questions or support, please contact the development team.
# propmanagement
