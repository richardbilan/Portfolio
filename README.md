# Portfolio Website

A modern, responsive portfolio website built with HTML, CSS, and JavaScript.

## Features

- **Responsive Design**: Works perfectly on desktop, tablet, and mobile devices
- **Modern UI**: Clean, professional design with smooth animations
- **Interactive Navigation**: Smooth scrolling and mobile-friendly hamburger menu
- **Project Showcase**: Grid layout for featured projects with hover effects
- **Skills Section**: Organized display of technical skills
- **Contact Form**: Functional contact form with validation
- **Dark Mode**: Toggle between light and dark themes
- **Scroll Animations**: Elements fade in as you scroll
- **Social Links**: Easy integration with social media profiles

## Sections

1. **Hero Section**: Eye-catching introduction with call-to-action buttons
2. **About Section**: Personal information and background
3. **Skills Section**: Technical skills and technologies
4. **Projects Section**: Featured work with live demos and GitHub links
5. **Contact Section**: Contact form and information

## Technologies Used

- HTML5 Semantic Elements
- CSS3 with Custom Properties (CSS Variables)
- Vanilla JavaScript (ES6+)
- Font Awesome Icons
- Google Fonts (Inter)
- Responsive Grid & Flexbox Layouts

## Customization

### Personal Information
Update the following in `index.html`:
- Your name in the hero section and navigation
- Job title and description
- Contact information
- Social media links
- Project details and links

### Styling
The CSS uses custom properties defined in `:root` for easy theme customization:
- `--primary-color`: Main brand color
- `--secondary-color`: Secondary accent color
- `--text-primary`: Main text color
- `--bg-primary`: Main background color

### Adding Projects
To add more projects, duplicate the `.project-card` structure in the projects section:

```html
<div class="project-card">
    <div class="project-image">
        <img src="your-image.jpg" alt="Project Name">
    </div>
    <div class="project-content">
        <h3>Project Name</h3>
        <p>Project description</p>
        <div class="project-tech">
            <span class="tech-tag">Technology</span>
        </div>
        <div class="project-links">
            <a href="#" class="project-link">
                <i class="fas fa-external-link-alt"></i> Live Demo
            </a>
            <a href="#" class="project-link">
                <i class="fab fa-github"></i> GitHub
            </a>
        </div>
    </div>
</div>
```

## Getting Started

1. Clone or download the files
2. Open `index.html` in your web browser
3. Customize the content with your information
4. Deploy to your hosting service

## Browser Support

- Chrome (Latest)
- Firefox (Latest)
- Safari (Latest)
- Edge (Latest)

## Performance

- Optimized images with lazy loading
- Minified CSS and JavaScript (for production)
- Efficient scroll event handling with debouncing
- Smooth animations using CSS transforms

## License

This project is open source and available under the MIT License.
