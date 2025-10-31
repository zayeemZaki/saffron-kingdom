# Saffron Kingdom — Cinematic Website

A beautiful, animated static website showcasing the Saffron Kingdom film with an embedded YouTube video, about section, and links to Daffodil Studios.

## 🌐 Live Site

Visit: **https://www.saffronkingdomfilm.com/**

Alternative: https://zayeemzaki.github.io/saffron-kingdom/

## ✨ Features

- Elegant typography with Playfair Display and Inter fonts
- Animated gradient background with floating shapes
- Glass morphism effects (frosted glass UI)
- Responsive design for all devices
- Dark mode support
- Smooth scroll animations
- SEO optimized with Open Graph meta tags

## 🚀 Deployment

This site is automatically deployed to GitHub Pages via GitHub Actions whenever changes are pushed to the `main` branch.

### Manual Deployment Setup

1. Go to your repository settings on GitHub
2. Navigate to **Settings** → **Pages**
3. Under "Build and deployment":
   - Source: **GitHub Actions**
4. Push to main branch - the workflow will deploy automatically

### Custom Domain Setup

The site is configured to use **www.saffronkingdomfilm.com**. To complete the setup:

1. **Configure DNS** (at your domain registrar - e.g., Squarespace, Namecheap, etc.):
   ```
   Type: CNAME
   Host: www
   Value: zayeemzaki.github.io
   TTL: 3600 (or Auto)
   ```

2. **Add Apex Domain (optional)** - For `saffronkingdomfilm.com` to redirect to `www`:
   ```
   Type: A Records (add all 4)
   Host: @
   Value: 185.199.108.153
   Value: 185.199.109.153
   Value: 185.199.110.153
   Value: 185.199.111.153
   ```

3. **Enable HTTPS** in GitHub Pages settings after DNS propagates (15-60 minutes)

4. **Verify** in GitHub:
   - Go to Settings → Pages
   - Under "Custom domain", enter: `www.saffronkingdomfilm.com`
   - Check "Enforce HTTPS" once available

## 💻 Local Development

Run locally using Python's built-in HTTP server:

```bash
cd saffron-kingdom-site
python3 -m http.server 8000
# Open http://localhost:8000
```

Or use any static server:
```bash
npx serve saffron-kingdom-site
```

## 📁 Files

- `index.html` — Main page with semantic HTML
- `styles.css` — Advanced CSS with animations and gradients
- `favicon.svg` — Custom SVG favicon with saffron crown
- `README.md` — This file

## 🎨 Design

- **Color Palette**: Saffron oranges and golds (#d97706, #fbbf24)
- **Typography**: Playfair Display (headings), Inter (body)
- **Animation**: CSS-only floating shapes and gradients
- **Theme**: Cinematic elegance with depth and motion

## 📺 Video

Embedded YouTube video ID: `Mcz-Ke_W4ow`

## 🔗 External Links

- Production company: https://www.daffodilstudios.org/
