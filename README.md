# MindFlow Website

Static website for the MindFlow mobile app — app information, Privacy Policy, Terms of Service, and contact details.

## Files

```
docs/
├── assets/
│   └── app-icon.png  # App icon (from Android launcher)
├── index.html        # Home page
├── privacy.html      # Privacy Policy
├── terms.html        # Terms of Service
├── styles.css        # Shared Fluent-style stylesheet
└── README.md         # This file
```

## Deploy to GitHub Pages

1. Push this repository to GitHub.
2. Open **Settings → Pages**.
3. Under **Build and deployment**, set:
   - **Source:** Deploy from a branch
   - **Branch:** your default branch (e.g. `master` or `main`)
   - **Folder:** `/docs`
4. Save. The site will be published at:

   **https://netmedia-app.github.io/MindFlow/**

## Local preview

Open `index.html` in a browser, or serve the `docs` folder with any static file server.

## Tech

- Pure HTML and CSS
- No JavaScript
- No backend
- Mobile responsive
- Relative paths only
