# The WatCL Lab Website

A modern, responsive academic website for the Waterloo Computational Learning (WatCL) Lab at the Cheriton School of Computer Science, University of Waterloo.

## 🚀 Features

- **Modern Design**: Clean, professional academic website design
- **Responsive Layout**: Optimized for all devices and screen sizes
- **Accessibility**: WCAG compliant with proper semantic HTML and ARIA labels
- **Performance**: Optimized loading with lazy images and efficient CSS
- **SEO Optimized**: Built-in meta tags, sitemap, and structured data
- **Interactive Elements**: Smooth animations and modern user interactions
- **Mobile First**: Designed with mobile users in mind

## 🛠️ Technology Stack

- **Jekyll 4.3+**: Static site generator
- **Bootstrap 5**: Modern CSS framework
- **Font Awesome 6**: Icon library
- **Google Fonts**: Inter and JetBrains Mono typography
- **Modern JavaScript**: ES6+ with progressive enhancement
- **CSS Custom Properties**: Modern CSS with variables and animations

## 📁 Project Structure

```
watcl.github.io/
├── _config.yml          # Jekyll configuration
├── _data/               # Data files (team, publications, news)
├── _includes/           # Reusable HTML components
├── _layouts/            # Page layout templates
├── _pages/              # Content pages
├── css/                 # Stylesheets
├── js/                  # JavaScript files
├── images/              # Images and media
└── Gemfile              # Ruby dependencies
```

## 🚀 Getting Started

### Prerequisites

- Ruby 2.7+ (recommended: Ruby 3.0+)
- RubyGems
- Bundler

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/opallab/watcl.github.io.git
   cd watcl.github.io
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Start the development server**
   ```bash
   bundle exec jekyll serve
   ```

4. **Open your browser**
   Navigate to `http://localhost:4000`

### Building for Production

```bash
bundle exec jekyll build
```

The built site will be in the `_site` directory.

## 📝 Content Management

### Adding Team Members

Edit `_data/graduate_members.yml` to add new team members:

```yaml
- name: "John Doe"
  photo: john.jpg
  info: "PhD student"
  duration: "September 2024 - Now"
  email: "john.doe@uwaterloo.ca"
  number_educ: 2
  education1: "B.Sc. in Computer Science, University of Example"
  education2: "M.Sc. in Computer Science, University of Example"
```

### Adding Publications

Edit `_data/publist.yml` to add new publications:

```yaml
- title: "Your Publication Title"
  image: publication_image.png
  description: "Brief description of the publication"
  authors: "Author 1, Author 2, Author 3"
  link:
    url: "https://example.com/paper"
    display: "Paper Link"
  highlight: 1
  code:
    url: "https://github.com/example/code"
    display: "(Code)"
  preprint:
    url: "https://arxiv.org/abs/1234.5678"
    display: "(Preprint)"
```

### Adding News

Edit `_data/news.yml` to add news items:

```yaml
- date: "15 January 2025"
  headline: "Your news headline with <a href='link'>optional link</a>"
```

## 🎨 Customization

### Colors and Theme

Edit CSS variables in `css/main.css`:

```css
:root {
  --primary-color: #2c3e50;
  --secondary-color: #3498db;
  --accent-color: #e74c3c;
  /* ... more variables */
}
```

### Layouts

Customize page layouts in the `_layouts/` directory. Each layout extends the base `default.html` layout.

### Styling

Modify styles in `css/main.css`. The CSS is organized into logical sections:

- Base styles and typography
- Header and navigation
- Page layouts and components
- Team member cards
- Publication displays
- Responsive design
- Utility classes

## 📱 Responsive Design

The website is built with a mobile-first approach and includes:

- Responsive navigation with mobile menu
- Flexible grid system
- Optimized typography for all screen sizes
- Touch-friendly interactive elements
- Optimized images for different devices

## ♿ Accessibility

The website follows WCAG 2.1 AA guidelines:

- Semantic HTML structure
- Proper heading hierarchy
- ARIA labels and roles
- Keyboard navigation support
- High contrast ratios
- Screen reader compatibility
- Skip navigation links

## 🚀 Performance

Optimizations include:

- Minified CSS and JavaScript
- Optimized images
- Lazy loading for images
- Efficient CSS with custom properties
- Minimal HTTP requests
- Progressive enhancement

## 🔧 Development

### Adding New Pages

1. Create a new markdown file in `_pages/`
2. Add front matter with layout and metadata
3. Add navigation link in `_includes/header.html`

### Adding New Layouts

1. Create a new layout file in `_layouts/`
2. Extend the base layout or create a custom one
3. Update page front matter to use the new layout

### JavaScript Modules

The main JavaScript file (`js/main.js`) is organized into modules:

- Navigation functionality
- Smooth scrolling
- Animations and effects
- Accessibility features
- Search functionality
- Form validation

## 📊 Analytics

Google Analytics is included via `_includes/analytics.html`. Update the tracking ID in the include file.

## 🌐 Deployment

### GitHub Pages

The site is configured for GitHub Pages deployment. Simply push to the main branch to deploy.

### Other Hosting

For other hosting providers:

1. Build the site: `bundle exec jekyll build`
2. Upload the `_site` directory contents to your web server

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test locally
5. Submit a pull request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 📞 Contact

For questions about the website or lab:

- **Lab Director**: Kimon Fountoulakis
- **Email**: kimon.fountoulakis@uwaterloo.ca
- **Website**: https://watcl.ca

## 🙏 Acknowledgments

- Built with [Jekyll](https://jekyllrb.com/)
- Styled with [Bootstrap](https://getbootstrap.com/)
- Icons from [Font Awesome](https://fontawesome.com/)
- Typography from [Google Fonts](https://fonts.google.com/)

---

**The WatCL Lab** - Machine learning and artificial intelligence.
