# AI Gateway for SAP - Landing Page

A professional landing page for AI Gateway, a product that connects AI agents to SAP systems via Model Context Protocol (MCP).

## Quick Start

Simply open `index.html` in your browser, or deploy to any static hosting platform.

## Deployment Options

### GitHub Pages

1. Push this folder to a GitHub repository
2. Go to **Settings** → **Pages**
3. Select your branch (e.g., `main`) and folder (`/landing-page` or root)
4. Click **Save**
5. Your site will be available at `https://username.github.io/repo-name`

### Vercel

1. Install Vercel CLI: `npm i -g vercel`
2. Navigate to this directory: `cd landing-page`
3. Run: `vercel`
4. Follow the prompts

Or connect your GitHub repository directly at [vercel.com](https://vercel.com).

### Netlify

1. Go to [netlify.com](https://netlify.com) and sign in
2. Drag and drop the `landing-page` folder onto the deploy area
3. Your site is live instantly

Or connect your GitHub repository for automatic deployments.

### Any Static Host

This is a single HTML file with no dependencies. Upload `index.html` to any web server or static hosting service:

- AWS S3 + CloudFront
- Google Cloud Storage
- Azure Static Web Apps
- Cloudflare Pages
- Firebase Hosting
- Render
- Railway

## File Structure

```
landing-page/
├── index.html    # Complete landing page with embedded CSS
├── README.md     # This file
└── .gitignore    # Git ignore patterns
```

## Customization

### Colors

Edit the CSS custom properties in the `<style>` section:

```css
:root {
    --primary: #00d4aa;        /* Teal/mint - main accent */
    --accent: #f0ab00;         /* SAP gold */
    --bg-dark: #0a0f14;        /* Main background */
    --bg-card: #111820;        /* Card backgrounds */
}
```

### Contact Information

Search and replace these placeholders:
- `wouter@lemaire.tech` - Email address for contact forms
- `https://github.com/lemaiwo/AIGateway` - GitHub repository URL

### Fonts

The page uses Google Fonts:
- **Outfit** - Body text and headings
- **JetBrains Mono** - Code and terminal mockup

To change fonts, update the Google Fonts link in the `<head>` and the CSS variables.

## Features

- Fully responsive design (mobile, tablet, desktop)
- Dark theme with technical aesthetic
- No build tools or dependencies required
- Single HTML file with embedded CSS
- Smooth scroll navigation
- Accessible markup
- Performance optimized (no external JavaScript)

## Browser Support

Tested and working in:
- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)
- Mobile browsers

## License

MIT License - feel free to use and modify for your own projects.
