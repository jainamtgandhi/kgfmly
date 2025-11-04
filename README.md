# kgfmly.in

A quiet note from the heart. A multi-page website expressing commitment, growth, and hope for understanding.

## Structure

This is a multi-page website with the following routes:

- **/** - Home page with hero and navigation to all sections
- **/our-journey** - Timeline of how the relationship grew
- **/what-ive-learned** - Reflections on growth and lessons learned
- **/what-she-means** - What Preksha means to Jainam
- **/express-and-promise** - Acknowledgment, promises, and commitment
- **/who-i-am-today** - Personal values, family, and career
- **/vision-forward** - Future plans and closing note

## Features

- **Clean URLs**: Each route has its own folder with index.html for clean URLs
- **Responsive Design**: Works beautifully on all devices
- **Modern UI**: Elegant design with smooth animations
- **Respectful Tone**: Mature, thoughtful content addressing family concerns

## Local Development

### Option 1: Direct File Opening
Simply open `index.html` in your browser. Note: Some features work better with a local server.

### Option 2: Local Server (Recommended)
```bash
# Using Python
python -m http.server 8000

# Using Node.js (http-server)
npx http-server

# Using PHP
php -S localhost:8000
```

Then visit `http://localhost:8000` in your browser.

## Deployment

### GitHub Pages

1. Push your code to a GitHub repository
2. Go to Settings > Pages
3. Select your branch (usually `main` or `master`)
4. Your site will be live at `https://yourusername.github.io/repository-name`

### Custom Domain (kgfmly.in)

The `CNAME` file is already configured for `kgfmly.in`. 

1. Make sure the `CNAME` file contains `kgfmly.in`
2. Point your domain's DNS to GitHub Pages:
   - Add a CNAME record pointing to `yourusername.github.io`
3. Wait for DNS propagation (can take up to 48 hours)

## Customization

### Content
- Update dates and details in each page's HTML files
- Personalize the timeline in `/our-journey/index.html`
- Adjust promises and commitments in `/express-and-promise/index.html`
- Add photos by replacing placeholder divs with `<img>` tags

### Styling
- Colors: Update CSS variables in `styles.css` (`:root` section)
- Fonts: Change Google Fonts imports in HTML `<head>` sections
- Layout: Modify grid and spacing in `styles.css`

## Browser Support

Works on all modern browsers:
- Chrome
- Firefox
- Safari
- Edge

## Notes

- The website uses a respectful, mature tone throughout
- All navigation links use absolute paths for GitHub Pages compatibility
- Each page is self-contained but shares common CSS and JS files
- The structure allows for easy content updates and additions

---

Made with ❤️ and respect for family
