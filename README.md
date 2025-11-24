# TriForge Studio Website

A modern, minimalist single-page website for TriForge Studio - custom business software solutions.

## Overview

TriForge Studio specializes in creating custom, cloud-based business applications for small and medium-sized businesses. This website showcases our services, portfolio, and provides a contact form for potential clients.

## Features

- **Modern Minimalist Design**: Clean, professional aesthetic with smooth animations
- **Fully Responsive**: Optimized for desktop, tablet, and mobile devices
- **Single-Page Layout**: Easy navigation with smooth scrolling between sections
- **Service Showcase**: Detailed information about industry-specific solutions
- **Portfolio Section**: Highlighting key applications (Winesoft, ConstructPro, Mechanic Shop, MicroMSP)
- **Contact Form**: Email integration for client inquiries
- **Accessibility**: Semantic HTML and ARIA labels where appropriate

## Tech Stack

- **HTML5**: Semantic markup
- **CSS3**: Custom properties, Grid, Flexbox, and modern animations
- **Vanilla JavaScript**: No dependencies, lightweight and fast
- **Google Fonts**: Inter font family for clean typography

## Color Scheme

- **Primary Color**: RGB(50, 160, 175) - Teal accent
- **Text**: Black (#000000) and shades of gray
- **Background**: White (#FFFFFF) with subtle gray tones

## Deployment to GitHub Pages

### Initial Setup

1. **Navigate to your repository**: Go to `https://github.com/TriForgeStudio360/triforgestudio.github.io`

2. **Upload files**: Copy all files from this project to the root of your repository:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`

### Option 1: Using Git Command Line

```bash
# Initialize git in your local directory (if not already initialized)
git init

# Add the remote repository
git remote add origin https://github.com/TriForgeStudio360/triforgestudio.github.io.git

# Add all files
git add .

# Commit the changes
git commit -m "Initial commit: TriForge Studio website"

# Push to GitHub
git push -u origin main
```

### Option 2: Using GitHub Web Interface

1. Go to your repository on GitHub
2. Click "Add file" > "Upload files"
3. Drag and drop all website files
4. Commit the changes

### Enable GitHub Pages

1. Go to your repository settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select the branch (usually `main`)
4. Select the root folder (`/`)
5. Click "Save"

### Access Your Website

Your website will be live at: `https://triforgestudio360.github.io/`

Note: It may take a few minutes for the site to go live after the initial deployment.

## File Structure

```
triforgestudio.github.io/
│
├── index.html          # Main HTML file
├── styles.css          # All CSS styles
├── script.js           # JavaScript functionality
└── README.md           # Documentation
```

## Sections

1. **Home/Hero**: Eye-catching introduction with tagline and call-to-action
2. **About**: Company overview and core values (Custom, Affordable, Accessible)
3. **Services**: Industry-specific solutions with detailed descriptions
4. **Portfolio**: Showcase of key applications with features
5. **Contact**: Contact form and company email
6. **Footer**: Quick links and contact information

## Customization

### Updating Content

- **Company Information**: Edit the text directly in `index.html`
- **Portfolio Projects**: Modify the portfolio cards in the `#portfolio` section
- **Services**: Update service cards in the `#services` section
- **Contact Email**: Change the email address in both the HTML and JavaScript

### Styling Changes

- **Colors**: Update CSS custom properties in `styles.css` (`:root` section)
- **Fonts**: Change the Google Fonts import in `index.html`
- **Layout**: Modify grid and flexbox properties in `styles.css`

### Adding Features

- **Analytics**: Add Google Analytics or other tracking code before `</head>`
- **Logo**: Replace the text-based `.nav-brand` with an `<img>` tag
- **Additional Pages**: Create new HTML files and update navigation links

## Contact Form

The contact form uses a `mailto:` link fallback since GitHub Pages doesn't support server-side processing. When users submit the form, their default email client will open with pre-filled information.

For a more robust solution, consider integrating with:
- [Formspree](https://formspree.io/)
- [Netlify Forms](https://www.netlify.com/products/forms/)
- [Google Forms](https://www.google.com/forms/about/)

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## Performance

- No external dependencies (except Google Fonts)
- Minimal JavaScript
- Optimized CSS with modern properties
- Fast load times suitable for GitHub Pages hosting

## Maintenance

### Regular Updates

- Update portfolio projects as new work is completed
- Keep contact information current
- Review and update service descriptions as offerings change
- Check for broken links periodically

### Future Enhancements

- Add a blog section for company news
- Integrate testimonials from satisfied clients
- Create case study detail pages
- Add more interactive elements (calculators, configurators)

## License

Copyright © 2025 TriForge Studio. All rights reserved.

## Support

For questions or issues with this website, contact: info@triforgestudio.com
