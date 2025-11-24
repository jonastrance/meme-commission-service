# Meme Commission Service

Create custom memes based on clients' inside jokes, companies, or weird requirements for $5-25 per meme.

## Overview

A professional static website for a meme commission service offering custom meme creation at three pricing tiers:
- **Basic ($5)**: Single image meme with standard template
- **Premium ($15)**: Multi-panel meme with custom templates
- **Deluxe ($25)**: Complex designs with original artwork

## Website Structure

- **index.html** - Landing page with pricing tiers and service overview
- **portfolio.html** - Portfolio showcase with 5 example memes
- **request-form.html** - Request form for meme commissions (includes Google Form integration option)
- **social-media-templates.html** - 7 ready-to-use social media promotion templates
- **styles.css** - Responsive styling with purple gradient theme

## How to Use

### Local Development

1. Clone the repository
2. Open any HTML file in a web browser, or
3. Run a local web server:
   ```bash
   python3 -m http.server 8080
   ```
4. Navigate to `http://localhost:8080`

### Customization

#### Google Form Integration
To add your own Google Form:
1. Create a form at [forms.google.com](https://forms.google.com)
2. Click "Send" → Select the embed option (`</>`)
3. Copy the iframe code
4. Paste it into `request-form.html` in the Google Form section

#### Updating Content
- **Pricing**: Update pricing information in `index.html` and `request-form.html`
- **Portfolio**: Edit meme examples in `portfolio.html`
- **Templates**: Modify social media templates in `social-media-templates.html`
- **Styling**: Adjust colors and design in `styles.css` (main brand colors: #667eea to #764ba2)

## Features

- ✅ Responsive design (mobile, tablet, desktop)
- ✅ Three pricing tiers with detailed feature lists
- ✅ Portfolio with 5 diverse meme examples
- ✅ Custom request form with validation
- ✅ Google Form integration option
- ✅ 7 social media promotion templates
- ✅ Copy-to-clipboard functionality with fallback support
- ✅ Professional purple gradient theme
- ✅ No dependencies or build process required

## Browser Compatibility

The website works on all modern browsers. The copy-to-clipboard feature includes fallback support for older browsers that don't support the Clipboard API.

## Deployment

Since this is a static website, you can deploy it to:
- GitHub Pages
- Netlify
- Vercel
- Any static hosting service
- Any web server

Simply upload all files to your hosting provider.

## License

All rights reserved.
