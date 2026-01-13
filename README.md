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

### 4. Configure DNS on Namecheap

1. Log in to your Namecheap account
2. Go to "Domain List" and click "Manage" next to toolboxlabs.dev
3. Go to the "Advanced DNS" tab
4. Click "Add New Record" and add these **4 A Records**:

   | Type | Host | Value | TTL |
   |------|------|-------|-----|
   | A Record | @ | 185.199.108.153 | Automatic |
   | A Record | @ | 185.199.109.153 | Automatic |
   | A Record | @ | 185.199.110.153 | Automatic |
   | A Record | @ | 185.199.111.153 | Automatic |

5. Add a **CNAME Record** for www subdomain:

   | Type | Host | Value | TTL |
   |------|------|-------|-----|
   | CNAME Record | www | [your-github-username].github.io. | Automatic |

6. **Remove any conflicting records** (like default parking page A records or URL Redirect Records)
7. Click "Save All Changes"

**Note:** DNS propagation can take 5-30 minutes. You can check status at https://dnschecker.org

Your site will be live at: `https://toolboxlabs.dev`

## Local Development

Simply open `index.html` in your browser to view the page locally.

## Files Overview

- `index.html` - Main landing page with SEO optimization
- `404.html` - Custom 404 error page
- `robots.txt` - Search engine crawler instructions (allows AI crawlers)
- `sitemap.xml` - XML sitemap for search engines
- `humans.txt` - Credits and site information
- `CNAME` - Custom domain configuration for GitHub Pages
- `.nojekyll` - Disables Jekyll processing
- `.gitignore` - Git ignore rules

## SEO Features

- Optimized for construction management and permit management keywords
- Structured data (JSON-LD) for search engines
- Open Graph tags for social media sharing
- Twitter Card support
- AI crawler friendly (GPTBot, ChatGPT, etc.)
- Mobile-responsive design
- Fast loading with optimized assets

## Color Palette

- Dark Navy: `#1A1A2E`
- Surface Dark: `#25253D`
- Accent Orange: `#f97116`
- Deep Navy: `#0f1729`
- Light Gray: `#eff1f2`

## License

All rights reserved © 2026 ToolboxLabs
