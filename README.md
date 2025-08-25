# Premier Property Management - Hugo Site

A modern, responsive website for a property management company built with Hugo static site generator.

## 🏠 About This Site

This is a professional landing page for "Premier Property Management," a fictional property management company. The site showcases the company's services, team, and provides contact information for potential clients.

## ✨ Features

### Design & User Experience
- **Modern, Professional Design**: Clean, modern interface with a professional color scheme
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Fast Loading**: Static site generation ensures fast page loads
- **SEO Optimized**: Proper meta tags, structured content, and semantic HTML

### Content Sections
- **Hero Banner**: Eye-catching hero section with property images and call-to-action
- **Services Overview**: Comprehensive list of property management services
- **Company Statistics**: Trust indicators with key metrics
- **About Section**: Company story, mission, and team information
- **Contact Form**: Lead generation form with property-specific fields

### Technical Features
- **Bootstrap 5**: Modern CSS framework for responsive design
- **Font Awesome Icons**: Professional iconography throughout the site
- **Google Fonts**: Inter font family for modern typography
- **Custom CSS**: Tailored styling for property management industry
- **Hugo Templates**: Modular template system for easy maintenance

## 🚀 Getting Started

### Prerequisites
- Hugo installed on your system (version 0.80.0 or higher)
- Git for version control

### Installation

1. **Clone the repository**:
   ```bash
   git clone <repository-url>
   cd rentalmanagement
   ```

2. **Install Hugo** (if not already installed):
   - **Windows**: Download from [Hugo Releases](https://github.com/gohugoio/hugo/releases)
   - **macOS**: `brew install hugo`
   - **Linux**: `sudo apt-get install hugo`

3. **Run the development server**:
   ```bash
   hugo server --buildDrafts
   ```

4. **View the site**: Open your browser and navigate to `http://localhost:1313`

### Building for Production

To build the site for production:

```bash
hugo --minify
```

The built site will be in the `public/` directory.

## 📁 Project Structure

```
rentalmanagement/
├── content/                 # Site content (Markdown files)
│   ├── about.md            # About page
│   ├── contact.md          # Contact page
│   └── services.md         # Services page
├── themes/
│   └── property-management/ # Custom theme
│       ├── assets/
│       │   └── css/
│       │       └── main.css # Custom styles
│       ├── layouts/
│       │   ├── _default/
│       │   │   ├── baseof.html    # Base template
│       │   │   └── single.html    # Single page template
│       │   └── index.html         # Home page template
│       └── hugo.toml              # Theme configuration
├── hugo.toml               # Site configuration
└── README.md              # This file
```

## 🎨 Customization

### Colors
The site uses CSS custom properties for easy color customization. Edit the variables in `themes/property-management/assets/css/main.css`:

```css
:root {
    --primary-color: #2563eb;
    --secondary-color: #1e40af;
    --accent-color: #f59e0b;
    --text-dark: #1f2937;
    --text-light: #6b7280;
    --bg-light: #f8fafc;
}
```

### Company Information
Update company details in `hugo.toml`:

```toml
[params]
  company_name = "Your Company Name"
  phone = "(555) 123-4567"
  email = "info@yourcompany.com"
  address = "123 Business Ave, City, State 12345"
```

### Images
Replace the placeholder images with your own:
- Hero banner image: Update the URL in `themes/property-management/layouts/index.html`
- About section image: Update the URL in the same file
- All images are currently using Unsplash placeholder URLs

### Content
Edit the content files in the `content/` directory:
- `content/about.md` - Company information
- `content/services.md` - Service descriptions
- `content/contact.md` - Contact information and form

## 📱 Responsive Design

The site is fully responsive and optimized for:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: Below 768px

## 🔧 Development

### Adding New Pages
1. Create a new Markdown file in the `content/` directory
2. Add front matter with title, description, and date
3. The page will automatically use the single page template

### Modifying Styles
Edit `themes/property-management/assets/css/main.css` for custom styling.

### Adding New Sections
Modify the appropriate template files in `themes/property-management/layouts/`.

## 📊 Performance

The site is optimized for performance:
- Static site generation for fast loading
- Optimized images and CSS
- Minimal JavaScript dependencies
- CDN-hosted external resources

## 🌐 Deployment

The site can be deployed to any static hosting service:

- **Netlify**: Drag and drop the `public/` folder
- **Vercel**: Connect your Git repository
- **GitHub Pages**: Push to a GitHub repository
- **AWS S3**: Upload the `public/` folder contents

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally with `hugo server`
5. Submit a pull request

## 📞 Support

For questions or support:
- Create an issue in the repository
- Contact the development team

---

**Built with ❤️ using Hugo**
