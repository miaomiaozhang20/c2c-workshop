# Coast-to-Coast Doctoral Workshop Website

A modern, minimal website for the C2C Doctoral Workshop - a community for junior scholars in AI, innovation, management, and organizations.

## Local Development

To view the website locally:

1. Simply open `index.html` in your web browser
2. Or use a local server (recommended for best experience):
   ```bash
   # If you have Python installed:
   python -m http.server 8000
   # Then visit http://localhost:8000
   ```

## File Structure

```
C2C/
├── index.html          # Main HTML file
├── styles.css          # CSS styling
└── README.md          # This file
```

## Deployment Options

### Option 1: GitHub Pages (Recommended - Free)

1. Create a new GitHub repository called `c2c-workshop`
2. Push your files:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: C2C workshop website"
   git branch -M main
   git remote add origin https://github.com/YOUR_USERNAME/c2c-workshop.git
   git push -u origin main
   ```
3. Go to repository Settings > Pages
4. Select "main" branch as source
5. Your site will be live at `https://YOUR_USERNAME.github.io/c2c-workshop`

### Option 2: Netlify (Free, Easy)

1. Go to [netlify.com](https://www.netlify.com/)
2. Drag and drop the C2C folder
3. Your site will be live instantly with a custom URL

### Option 3: Custom Domain

If you want a custom domain (like `c2c-workshop.org`):
- Purchase domain from Namecheap, Google Domains, etc.
- Point it to your GitHub Pages or Netlify site
- Follow their domain configuration guides

## Customization

### Colors

Edit the CSS variables in `styles.css` (lines 10-19):
```css
:root {
    --primary-color: #2c3e50;    /* Main text and headings */
    --secondary-color: #3498db;   /* Accents and links */
    --accent-color: #e74c3c;      /* Call-to-action elements */
    /* ... */
}
```

### Adding Content

- **New Members:** Add entries to the people grid in `index.html`
- **Past Events:** Add timeline items in the timeline section
- **New Sections:** Copy an existing section and modify

### Adding Pages

To add new pages (e.g., Resources, Events Archive):
1. Create new HTML file (e.g., `resources.html`)
2. Copy the navbar from `index.html`
3. Add link in navbar of all pages
4. Link pages together

## Features

- ✅ Fully responsive (mobile, tablet, desktop)
- ✅ Modern minimal design
- ✅ Smooth scrolling navigation
- ✅ Hover effects and animations
- ✅ No dependencies (pure HTML/CSS)
- ✅ Fast loading
- ✅ SEO friendly

## Browser Support

Works on all modern browsers:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## Contact

Website created for:
- **Amanda Prat** (Stanford MS&E)
- **Miaomiao Zhang** (Harvard Business School)

Co-leaders of the Coast-to-Coast Doctoral Workshop

---

Built with ❤️ for the C2C community
