# Bridge 2 Bitcoin Website

A simple, fast static website for Bridge 2 Bitcoin.

## Pages

- **index.html** - Home page with hero, stats, features, benefits
- **about.html** - About page with team and podcast appearances  
- **contact.html** - Contact form using Formspree + social links

## Deploy to GitHub Pages

1. Create a new repository on GitHub (e.g., `bridge2bitcoin-website`)

2. Push this folder to GitHub:
   ```bash
   cd Bridge2Bitcoin-Website
   git init
   git add .
   git commit -m "Initial commit"
   git remote add origin https://github.com/YOUR_USERNAME/bridge2bitcoin-website.git
   git push -u origin main
   ```

3. Go to Repository Settings → Pages

4. Under "Build and deployment", select:
   - Source: Deploy from a branch
   - Branch: main
   - Folder: / (root)

5. Your site will be live at: `https://YOUR_USERNAME.github.io/bridge2bitcoin-website/`

## Custom Domain

To use bridge2bitcoin.com:

1. Go to your repository → Settings → Pages
2. Enter your custom domain under "Custom domain"
3. Create an A record pointing to GitHub's IPs, or a CNAME to your username.github.io

## Formspree

The contact form uses [Formspree](https://formspree.io) for free email submissions. 

To set up:
1. Sign up at formspree.io
2. Create a new form
3. Replace `https://formspree.io/f/xpwzgvqa` in contact.html with your form's URL

## Tech

- Pure HTML/CSS (no frameworks)
- Mobile responsive
- Fast loading
- Bitcoin orange (#f7931a) accent color
