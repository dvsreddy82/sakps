# Sri Ankalamma Kennels and Pet Store

A modern, responsive Jekyll website for Sri Ankalamma Kennels and Pet Store, optimized for GitHub Pages.

## Features

- 🎨 Modern, responsive design
- 📱 Mobile-friendly interface
- 🗺️ Integrated Google Maps
- ⚡ Fast loading and optimized
- 🌐 GitHub Pages ready with Jekyll
- 🔧 Easy to customize via `_config.yml`

## Website Sections

1. **Hero Section** - Welcome banner with call-to-action
2. **About Section** - Information about the kennels and services
3. **Services Section** - Detailed list of services offered
4. **Contact Section** - Location information with embedded Google Maps

## Technologies Used

- Jekyll (Static Site Generator)
- HTML5
- CSS3 (with CSS Grid and Flexbox)
- Vanilla JavaScript
- Google Maps Embed API

## Jekyll Structure

```
sakps/
├── _config.yml          # Jekyll configuration
├── _layouts/
│   └── default.html     # Main layout template
├── _includes/           # Reusable components
│   ├── navigation.html
│   ├── footer.html
│   ├── hero.html
│   ├── about.html
│   ├── services.html
│   └── contact.html
├── assets/
│   ├── css/
│   │   └── styles.css
│   └── js/
│       └── script.js
├── index.html           # Homepage
├── Gemfile              # Ruby dependencies
└── README.md
```

## Setup for GitHub Pages

This Jekyll website is ready to be published on GitHub Pages. GitHub Pages will automatically build and deploy your Jekyll site.

1. **Push to GitHub** (already done)
   ```bash
   git add .
   git commit -m "Convert to Jekyll"
   git push origin main
   ```

2. **Enable GitHub Pages**
   - Go to your repository on GitHub: `https://github.com/dvsreddy82/sakps`
   - Click on "Settings"
   - Scroll down to "Pages" section
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

3. **Access Your Website**
   - Your website will be available at: `https://dvsreddy82.github.io/sakps/`
   - GitHub Pages will automatically build your Jekyll site
   - It may take 1-2 minutes for the site to be live

## Local Development

To run the website locally with Jekyll:

1. **Install Ruby and Bundler** (if not already installed)
   ```bash
   # macOS (using Homebrew)
   brew install ruby
   
   # Or use system Ruby
   ```

2. **Install Jekyll and dependencies**
   ```bash
   bundle install
   ```

3. **Run the Jekyll server**
   ```bash
   bundle exec jekyll serve
   ```

4. **View the website**
   - Open your browser and go to: `http://localhost:4000/sakps/`
   - The site will auto-reload when you make changes

## Customization

### Site Configuration
Edit `_config.yml` to change:
- Site title and description
- Services and features
- Google Maps URLs
- Site variables

### Styling
- Edit `assets/css/styles.css` to change colors, fonts, and styling
- CSS variables are defined at the top of the file for easy customization

### Content
- Edit `_includes/` files to modify sections
- Edit `index.html` to change page structure
- Edit `assets/js/script.js` to modify interactive features

### Adding New Services
Add services in `_config.yml`:
```yaml
services:
  - icon: "🏠"
    title: "New Service"
    description: "Service description"
```

## Location

Sri Ankalamma Kennels and Pet Store  
Bangalore, Karnataka, India

[View on Google Maps](https://www.google.com/maps/place/Sri+Ankalamma+Kennels+and+pet+store/@12.9884181,77.7855768,980m/data=!3m2!1e3!4b1!4m6!3m5!1s0x3bae0f52774168cf:0xcf0214c7b0308586!8m2!3d12.9884129!4d77.7881517!16s%2Fg%2F11y48pmsdb)

## License

© 2025 Sri Ankalamma Kennels and Pet Store. All rights reserved.
