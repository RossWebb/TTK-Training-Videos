# Trenem Tingting Kos (TTK) – Critical Thinking Course

Trenem Tingting Kos is a small Progressive Web App (PWA) that provides a structured critical thinking video course for Vanuatu learners, organised into modules and lessons and playable via YouTube embeds.

## Features

- 📱 Installable as a PWA on Android, iOS and desktop
- 🔌 Works offline for the main shell after first load (HTML, manifest, basic assets cached)
- 🎬 Clean menu-based UI with modules and individual lesson videos (YouTube embeds)
- 🧭 Mobile‑friendly responsive layout
- ❤️ Simple, dependency‑free HTML/CSS/JavaScript

## Project Structure

- `index.html` – Main application shell, navigation, YouTube player, and PWA install banners  
- `manifest.json` – Web app manifest (name, icons, theme color, start URL, etc.)  
- `sw.js` – Service worker for basic offline caching of core files  

GitHub Pages serves everything over HTTPS, which is required for PWA features and YouTube embeds. [web:71]

## Running Locally

You can run the app locally for development using any static HTTP server, for example with Python:

```bash
python -m http.server 8000
# then open http://localhost:8000 in your browser
