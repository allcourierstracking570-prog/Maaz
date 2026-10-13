# Maaz Ahmad - Graphic Designer Portfolio

Responsive portfolio website built with plain **HTML, CSS and JavaScript** (no frameworks).

## Pages
- `index.html` - Home (hero, about, services preview)
- `services.html` - Services
- `skills.html` - Skills, software, languages
- `experience.html` - Experience and education
- `contact.html` - Contact (email + WhatsApp)

## Features
- Mobile and desktop friendly
- Click on email opens the mail app (`mailto:`), click on WhatsApp opens chat (`wa.me`)
- Contact form can send the message by Email or WhatsApp
- Floating WhatsApp button on every page

## Change contact details
Edit the numbers/email in `js/main.js` (`CONTACT` object) and in the HTML links.

## Run locally
Open `index.html` in a browser.

## Publish on GitHub Pages
1. Create a new repository on GitHub (e.g. `portfolio`).
2. Push this folder (see commands below).
3. Repository -> Settings -> Pages -> Source: `main` branch, `/ (root)`.
4. Site will be live at `https://YOUR-USERNAME.github.io/portfolio/`.

```bash
git remote add origin https://github.com/YOUR-USERNAME/portfolio.git
git branch -M main
git push -u origin main
```
