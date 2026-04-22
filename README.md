# Camel Club Narvik 2026 - Event Program PWA

A Progressive Web App displaying the event program for Camel Club Narvik 2026 (April 23-26).

## Features

- Progressive Web App (PWA) - can be installed on mobile devices
- Offline support via Service Worker
- Responsive design for all devices
- Beautiful background image
- Clean, readable schedule layout

## Deployment to GitHub Pages

1. Create a new repository on GitHub
2. Initialize git in this directory:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Camel Club Narvik 2026 PWA"
   ```

3. Add your GitHub repository as remote:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   ```

4. Push to GitHub:
   ```bash
   git branch -M main
   git push -u origin main
   ```

5. Enable GitHub Pages:
   - Go to your repository on GitHub
   - Click on "Settings"
   - Scroll down to "Pages" in the left sidebar
   - Under "Source", select "main" branch
   - Click "Save"

6. Your PWA will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPO_NAME/`

## Installing as PWA

Once deployed, users can install the app on their devices:

- **iOS/Safari**: Tap the Share button, then "Add to Home Screen"
- **Android/Chrome**: Tap the menu (⋮), then "Add to Home Screen" or "Install App"
- **Desktop/Chrome**: Click the install icon in the address bar

## Local Development

To test locally, you need to serve the files over HTTP (not just opening index.html):

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000` in your browser.
