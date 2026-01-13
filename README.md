# ToolboxLabs - Coming Soon

A modern, vibey startup landing page with smooth animations and mysterious vibes.

## Features

- Animated gradient backgrounds
- Floating orb effects
- Mouse parallax interactions
- Responsive design (mobile-friendly)
- Email signup form
- Smooth fade-in animations

## Deploy to GitHub Pages with Custom Domain

### 1. Push to GitHub
```bash
git add .
git commit -m "Add coming soon landing page"
git push origin main
```

### 2. Configure GitHub Pages
1. Go to your repository settings
2. Navigate to "Pages" in the left sidebar
3. Under "Source", select your main branch
4. Select "/ (root)" as the folder
5. Click "Save"

### 3. Configure Custom Domain (toolboxlabs.dev)
1. In GitHub Pages settings, enter `toolboxlabs.dev` in the Custom domain field
2. Wait for DNS check to complete
3. Enable "Enforce HTTPS" once DNS is configured

### 4. Configure DNS at Your Domain Registrar
Add these DNS records for toolboxlabs.dev:

**A Records** (point to GitHub Pages):
```
185.199.108.153
185.199.109.153
185.199.110.153
185.199.111.153
```

**Or use a CNAME record** (if using www subdomain):
```
www.toolboxlabs.dev -> [your-username].github.io
```

Your site will be live at: `https://toolboxlabs.dev`

## Local Development

Simply open `index.html` in your browser to view the page locally.

## Color Palette

- Dark Navy: `#1A1A2E`
- Surface Dark: `#25253D`
- Accent Orange: `#f97116`
- Deep Navy: `#0f1729`
- Light Gray: `#eff1f2`

## License

All rights reserved © 2026 ToolboxLabs
