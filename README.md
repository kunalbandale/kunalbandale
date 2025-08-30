# Modern Jekyll Website

A beautiful, responsive Jekyll website designed for GitHub Pages with modern UI/UX, blog functionality, and professional features.

## ✨ Features

- **Modern Design**: Clean, professional design with smooth animations
- **Responsive Layout**: Optimized for all devices and screen sizes
- **Blog System**: Full-featured blog with search, tags, and pagination
- **Portfolio Showcase**: Projects page with filtering and interactive elements
- **Contact Forms**: Functional contact form with validation
- **SEO Optimized**: Built-in SEO features and meta tags
- **Fast Performance**: Optimized CSS, JavaScript, and assets
- **GitHub Pages Ready**: Configured for easy deployment

## 🚀 Quick Start

### Prerequisites

- Ruby 2.4.0 or higher
- RubyGems
- GCC and Make (for native extensions)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/your-repo-name.git
   cd your-repo-name
   ```

2. **Install dependencies**
   ```bash
   bundle install
   ```

3. **Build and serve locally**
   ```bash
   bundle exec jekyll serve
   ```

4. **Open your browser**
   Navigate to `http://localhost:4000`

## 📁 Project Structure

```
├── _config.yml          # Jekyll configuration
├── _layouts/            # Layout templates
│   ├── default.html     # Main layout
│   └── post.html        # Blog post layout
├── _posts/              # Blog posts
├── _sass/               # Sass source files
├── assets/              # Compiled assets
│   ├── css/             # Stylesheets
│   └── js/              # JavaScript files
├── about/               # About page
├── blog/                # Blog listing page
├── contact/             # Contact page
├── projects/            # Projects/portfolio page
├── Gemfile              # Ruby dependencies
└── README.md            # This file
```

## ⚙️ Configuration

### Basic Settings

Edit `_config.yml` to customize your site:

```yaml
# Site settings
title: "Your Awesome Website"
description: "A modern Jekyll website built for GitHub Pages"
author: "Your Name"
email: "your-email@example.com"
url: "https://yourusername.github.io" # Change this to your GitHub Pages URL

# Social media
social:
  github: yourusername
  twitter: yourusername
  linkedin: yourusername
  email: your-email@example.com
```

### Customization

- **Colors**: Modify CSS variables in `_sass/main.scss`
- **Fonts**: Change font families in the SCSS file
- **Layout**: Customize layouts in `_layouts/` directory
- **Content**: Update pages in their respective directories

## 📝 Adding Content

### Blog Posts

Create new posts in `_posts/` with the naming convention:
```
YYYY-MM-DD-title.md
```

Example post front matter:
```yaml
---
layout: post
title: "Your Post Title"
date: 2024-01-15
author: "Your Name"
description: "Post description for SEO"
tags: [tag1, tag2]
read_time: true
---
```

### Pages

Create new pages by adding HTML or Markdown files to the root directory or subdirectories.

## 🎨 Styling

The website uses Sass for styling with a modular approach:

- **Variables**: Defined in `_sass/main.scss`
- **Components**: Organized by functionality
- **Responsive**: Mobile-first design with breakpoints
- **Animations**: Smooth transitions and hover effects

## 🔧 Development

### Local Development

```bash
# Start development server
bundle exec jekyll serve

# Build for production
bundle exec jekyll build

# Build with drafts
bundle exec jekyll serve --drafts
```

### File Watching

Jekyll automatically watches for file changes and rebuilds the site. The development server will show build errors in real-time.

## 🚀 Deployment

### GitHub Pages

1. **Push to GitHub**
   ```bash
   git add .
   git commit -m "Initial commit"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to repository Settings > Pages
   - Select source branch (usually `main`)
   - Choose theme (optional, as we have custom styling)

3. **Custom Domain** (Optional)
   - Add your domain in repository Settings > Pages
   - Update `_config.yml` with your domain
   - Configure DNS records

### Other Hosting

The site can be deployed to any static hosting service:
- Netlify
- Vercel
- AWS S3
- Any web server

## 📱 Responsive Design

The website is fully responsive with breakpoints:
- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🔍 SEO Features

- Meta tags and descriptions
- Open Graph tags
- Twitter Card support
- Sitemap generation
- RSS feed
- Structured data ready

## 🚀 Performance

- Optimized CSS and JavaScript
- Lazy loading for images
- Minified assets
- Efficient animations
- Fast loading times

## 🛠️ Customization

### Adding New Sections

1. Create new HTML files in the root directory
2. Use the existing layout structure
3. Add navigation links in `_layouts/default.html`
4. Style with existing CSS classes or add custom styles

### Modifying Layouts

- **Header**: Edit navigation in `_layouts/default.html`
- **Footer**: Update footer content and social links
- **Sidebar**: Add sidebar elements as needed

### Adding JavaScript

- Place custom JavaScript in `assets/js/main.js`
- Use existing event listeners and functions
- Follow the established code structure

## 📚 Dependencies

### Ruby Gems

- `jekyll`: Static site generator
- `jekyll-feed`: RSS feed generation
- `jekyll-seo-tag`: SEO optimization
- `jekyll-sitemap`: Sitemap generation
- `jekyll-paginate`: Blog pagination

### External Libraries

- **Font Awesome**: Icons
- **Google Fonts**: Typography
- **Modern CSS**: CSS Grid, Flexbox, Variables

## 🐛 Troubleshooting

### Common Issues

1. **Build Errors**
   - Check Ruby version compatibility
   - Verify all gems are installed
   - Review build logs for specific errors

2. **Styling Issues**
   - Check CSS compilation
   - Verify asset paths
   - Test in different browsers

3. **GitHub Pages Issues**
   - Ensure repository is public
   - Check branch name and settings
   - Wait for deployment (can take a few minutes)

### Getting Help

- Check Jekyll documentation
- Review GitHub Pages documentation
- Search existing issues
- Create a new issue with details

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🙏 Acknowledgments

- Built with [Jekyll](https://jekyllrb.com/)
- Hosted on [GitHub Pages](https://pages.github.com/)
- Icons by [Font Awesome](https://fontawesome.com/)
- Fonts by [Google Fonts](https://fonts.google.com/)

## 📞 Support

If you need help or have questions:

- Create an issue in this repository
- Check the documentation
- Contact us through the website

---

**Happy coding! 🎉**

Built with ❤️ using Jekyll and modern web technologies.
